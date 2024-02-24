# ACTIVITY TASKS 2:

- Add individual files to the folder TASK2 in [Onedrive](https://ubcca-my.sharepoint.com/:f:/g/personal/gema_rodriguezperez_ubc_ca/EpftLkZNoEFLslShzZ2T5uABbUxK5NO5qGsM8lY8YEZpBw?e=NeaKJS)


## Description T2-1
After running python3 T2-1.py, the program deletes the first and the last column in a CSV file data.csv and saves it to another file output.csv in the directory output/.

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
