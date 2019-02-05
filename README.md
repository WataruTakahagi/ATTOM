## ATTOM analyzer

### You can analysis raw data via simple command
#### Copy analyzer.py to the raw data directory & run command
```shell
%python analyzer.py
```

### RunNo.csv will be created after running analyzer.py
```shell
16697,Elix
16698,Elix
16699,1ppt
16700,1ppt
16701,1ppt
16702,1ppt
16703,1ppt
16704,Elix
16705,Elix
16706,10ppt
16707,10ppt
16708,10ppt
16709,10ppt
16710,10ppt
16711,Elix
16712,Elix
16713,100ppt
16714,100ppt
16715,100ppt
16716,100ppt
16717,100ppt
16718,Elix
16719,Elix
16720,1ppb
16721,1ppb
16722,1ppb
16723,1ppb
16724,1ppb
16725,Elix
16726Elix
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
