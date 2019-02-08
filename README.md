## ATTOM analyzer

### You can analysis raw data via simple command
### Copy analyzer.py to the raw data directory & run command
```shell
%python analyzer.py
```

### RunNo.csv will be created after running analyzer.py
#### Run No., ID, Sample Name
```shell
Run No.,ID,Name
16697,blank ,Elix
16698,blank ,Elix
16699,sample,1ppt
16700,sample,1ppt
16701,sample,1ppt
16702,sample,1ppt
16703,sample,1ppt
16704,blank ,Elix
16705,blank ,Elix
16706,sample,10ppt
16707,sample,10ppt
16708,sample,10ppt
16709,sample,10ppt
16710,sample,10ppt
16711,blank ,Elix
16712,blank ,Elix
16713,sample,100ppt
16714,sample,100ppt
16715,sample,100ppt
16716,sample,100ppt
16717,sample,100ppt
16718,blank ,Elix
16719,blank ,Elix
16720,sample,1ppb
16721,sample,1ppb
16722,sample,1ppb
16723,sample,1ppb
16724,sample,1ppb
16725,blank ,Elix
16726,blank ,Elix
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
