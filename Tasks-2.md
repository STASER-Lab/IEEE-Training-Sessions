# ACTIVITY TASKS 2:

- Add video recordings to: [dropbox](https://www.dropbox.com/request/iA0SqQuOCbJmgP3uf4WQ)


## Description T2-1
After running python3 T2-1.py, the  program delete the first and the last column in a CSV file data.csv and  save to another file output.csv in directory output/.

* Example Output
```
$ python3 main.py 
$ less output/output.csv 
first_name,last_name,email,gender 
Merry,MacKettrick,mmackettrick0@latimes.com,Male 
Calla,Truin,ctruin1@surveymonkey.com,Female 
```

## Description T2-2
After running python3 T2-2.py, the program trims the heading and trailing whitespaces and blank lines for all text files under data, normalizes newlines to \n (LF), and converts text files from encoding ISO-8859-15 to  encoding UTF-8. For other file types, do nothing. Save everything to the output directory.

* Example Output
``` 
$ python3 main.py 
$ ls output aaa.txt bbb.txt ccc.txt ddd.png 
$ cd output 
$ file aaa.txt aaa.txt: ASCII text 
$ file bbb.txt bbb.txt: UTF-8 Unicode text 
$ file ccc.txt ccc.txt: UTF-8 Unicode text
```
