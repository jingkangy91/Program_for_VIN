# Please read me

## Requirements

1. Homebrew
2. iTerm2
3. Anaconda3
4. ImageMagick
5. Oh-My-Zsh
6. Teamviewer

## Python packages

1. pandas
2. requests
3. bs4
4. pypdf2

## How to use

1. Open folder 'FastVIN', paste the CSV file of VIN list inside the folder 'list', if the folder does not exist, create it.
2. Right click 'Program_for_VIN', in Services at the bottom, select 'New iTerm2 Window Here'.
3. To download VIN pictures, type './1_download_vin.py' in terminal, then type the file name of VIN list, 'vin_list.csv' is the default.
4. To convert VIN pictures to pdfs, type './2_convert_vin.py' in terminal, then type the file name.
5. After conversion, it will combine all pdfs into one, if you want to print it, please type 'Y'.