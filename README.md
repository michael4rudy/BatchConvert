# BatchConvert
- Converts excel files types (.xlsx) to .csv through subdirectories
- Converts .docx file types (.docx) to .txt through subdirectories
- Duplicates file before converting extension to preserve original data. 
- Output folder contains converted file types for all folders/subfolders processed.

## Executing Script
1. Copy and paste BatchConvert into working directory containing files/subdirectories
2. cd into directory containing BatchConvert (do not cd into Batch Convert)
3. Run the following command: 'python3 ./BatchConvert/convert.py'
4. Batch Convert Output folder will appear in working directory 

## General Purpose
- Converts .xlsx file types to .csv for programs that process unicode encoded files. 
- Portability allows users to process directories/subdirectories by simply copying and pasting.

## Futher Build
- Create function to decode ANSCI .txt files 
- Encode .docx/.txt files to UTF-8
