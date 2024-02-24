# ACTIVITY TASKS 3:

- Add individual files to the folder TASK3 in [Onedrive](https://ubcca-my.sharepoint.com/:f:/g/personal/gema_rodriguezperez_ubc_ca/EpftLkZNoEFLslShzZ2T5uABbUxK5NO5qGsM8lY8YEZpBw?e=NeaKJS)


## Description T3-1

After running python3 T3-1.py, the program copies all files and  directories under the data directory to output directory. In the process directory or file names containing dates are renamed such that the date is reformatted from yyyy-mm-dd format to dd-mm-yyyy format.

* Example Output 

```
$ python3 T3-1.py 

$ ls data 
Photos_2019-03-22 ccc.txt data-02-01-1994.txt 'mybook at 2020-04-01.txt’ 

$ ls data/Photos_2019-03-22 
Personal '2019-03-21 22.30.png’ 

$ ls output 
Photos_22-03-2019 ccc.txt data-02-01-
1994.txt 'mybook at 01-04-2020.txt’ 

$ ls output/Photos_22-03-2019 Personal 
'21-03-2019 22.30.png'
```


## Description T3-2

After running python3 T3-2.py, the program looks at all the subdirectories in the data directory. In the process, the directories with .txt files in them are processed by concatenating all .txt files into one .txt file in the output directory, ordered in alphanumeric order of the filenames, and named by the directory name. The directories with .json files in them are processed by concatenating all the lists represented in JSON .json files into one list and then saved as a .json file in the output directory,ordered in alphanumeric order of the filenames, and named by the directory name. You are also required to re-number the "id" field for each object in the list with the first object starting from 1.

For directories without .txt or .json files, ignore them.

* Example Output 
```
$ python3 T3-2.py 
$ ls data 
filelist roster todo 
$ ls output 
filelist.txt 
roster.json
```
