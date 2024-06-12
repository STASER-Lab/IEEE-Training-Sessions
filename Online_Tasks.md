# Online tasks

## T1-01:
### Description: 
After running python3 T1-01.py, the program takes  a string as input and  checks whether it is a  palindrome,  and then prints  whether the input string is a palindrome or not. 
TIP: A palindrome is a word or phrase that reads the same forwards and backwards.

* Example Output
``` 
$ python3 T1-01.py 
Enter a string: Never odd or even 
The input string is a palindrome. 
```
```
$ python3 T1-01.py 
Enter a string: No lemon, no melon  
The input string is a a palindrome.
```

## T1-02:
### Description: 
After running python3 T1-02.py, the  program takes a string as an input and  counts the number of occurrences of each word. The program should store  the words counts in a dictionary and print the results. 

* Example Output 
``` 
$ python3 T1-02.py 
Enter a string: Hello world! 
hello again, World.         
'hello': 2, 
'world': 2, 
'again': 1
``` 

## T1-1:
### Description: 
After running python3 T1-1.py, the program first  randomly generates 100 lower-cased characters (a-z)  and randomly generates 100 integers (1-20 inclusive).  Pair the randomly generated characters and numbers together to form a dictionary, where the key is  characters and the value is the list of integers paired  with the character. Print out the dictionary content one key per line sorted by key (a-z), and also the list of numbers sorted in increasing order.

* Example Output 
``` 
$ python3 T1-1.py 
a 3 5 6 
b 1 1 2 4 5 
c 19 
... 
z 1 12 20
``` 

## T1-2:
### Description: 
After running python3 T1-2.py, the program prints the date and time one week from now in the GMT timezone, in the format of mm-dd-yyyy hh:mm (24hr format).

* Example Output 
``` 
$ python3 T1-2.py 
04-23-2020 16:33
```


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

