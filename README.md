## ATTOM analyzer

### You can analysis raw data via simple command
### Copy analyzer.py to the raw data directory & run command
```shell
%python analyzer.py
```

### RunNo.csv will be created after running analyzer.py
#### Run No., Sample Name
```shell
16697,Blank
16698,Blank
16699,1ppt
16700,1ppt
16701,1ppt
16702,1ppt
16703,1ppt
16704,Blank
16705,Blank
16706,10ppt
16707,10ppt
16708,10ppt
16709,10ppt
16710,10ppt
16711,Blank
16712,Blank
16713,100ppt
16714,100ppt
16715,100ppt
16716,100ppt
16717,100ppt
16718,Blank
16719,Blank
16720,1ppb
16721,1ppb
16722,1ppb
16723,1ppb
16724,1ppb
16725,Blank
16726,Blank
```
### Plese select the command in analyzer.py
```shell
attom = attom()
attom.run_no()
attom.binary2txt()
attom.txt2xls()
attom.txt2png()
```
#### Create RunNo. file
#### raw binary file to .txt file
#### Compile .txt to Excel format
#### Create .png file from .txt file
