# waveform_pipeline
Look for waveform files with given start, end and bed information.

1. to identify the waveform stp files with given start, end and bed information
output: list target waveform files paths in the output csv file `output1.csv`
with the following columns:
```bed, start, end, isExist, path, start_stp, end_stp```

2. to check coverage of the waveform files with given bed information
output: a list of waveform files with the given bed information and the coverage information
output: a list of waveform files with the given bed information and the coverage information in the output csv file `output2.csv`
with the following columns:
```bed, start, end, isExist, path, start_stp, end_stp, coverage(%)```

3. download 
output: actual stp files in folder `output3_stp_files`

4. process the stps with https://github.com/hulab-ucsf/wftools
output: stp files that in adbin format, also trimmed and aligned to the requested bed information in the input csv file
output: actual adibin files in folder `output4_adibin_files`


