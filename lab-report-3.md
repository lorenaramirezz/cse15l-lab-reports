# Lab Report 3 - Researching Commands

# The 'find' command

## Finding a single file by name
 We can use the find command in order to find a certain file. While I was in the technical directory, I used the command:
 `find technical -name "chapter-1.txt"` in order to find the file `chapter-1.txt` for example. This is what the output was when running this command:
 ```
 technical/911report/chapter-1.txt
```
Another example of finding one specific file would be the following: `find technical -name "1468-6708-3-4.txt".` The following is the output:
```
technical/biomed/1468-6708-3-4.txt
```

This command is very useful when you know the specific file name you are looking for, but don't know where to find it. This is especially useful in a larger directory
full of many files and folders. 




## Using * to find many files
A variation that we can change about the command I used previously is to use the `*` to find a variety of files in the technical folder. 
For example, I ran the following command:
```
find technical -name "chapter-*.txt"
```
Even by changing the previous command slightly using `*`, we can substitute certain things. That command resulted in the output:
```
technical/911report/chapter-13.4.txt
technical/911report/chapter-13.5.txt
technical/911report/chapter-13.1.txt
technical/911report/chapter-13.2.txt
technical/911report/chapter-13.3.txt
technical/911report/chapter-3.txt
technical/911report/chapter-2.txt
technical/911report/chapter-1.txt
technical/911report/chapter-5.txt
technical/911report/chapter-6.txt
technical/911report/chapter-7.txt
technical/911report/chapter-9.txt
technical/911report/chapter-8.txt
technical/911report/chapter-12.txt
technical/911report/chapter-10.txt
technical/911report/chapter-11.txt
```
Let's say the I wanted to find the txt files with the word "journal" in file name. I ran the following command:
```
find technical -name "journal*.txt"
```
This resulted in the following:
```
technical/plos/journal.pbio.0030032.txt
technical/plos/journal.pbio.0020354.txt
technical/plos/journal.pbio.0020156.txt
technical/plos/journal.pbio.0020140.txt
technical/plos/journal.pbio.0020183.txt
technical/plos/journal.pbio.0020430.txt
technical/plos/journal.pbio.0020394.txt
technical/plos/journal.pbio.0020431.txt
technical/plos/journal.pbio.0020419.txt
technical/plos/journal.pbio.0020169.txt
technical/plos/journal.pbio.0020035.txt
technical/plos/journal.pbio.0030024.txt
technical/plos/journal.pbio.0020223.txt
technical/plos/journal.pbio.0020019.txt
technical/plos/journal.pbio.0020145.txt
technical/plos/journal.pbio.0020353.txt
technical/plos/journal.pbio.0020347.txt
technical/plos/journal.pbio.0020420.txt
technical/plos/journal.pbio.0020346.txt
technical/plos/journal.pbio.0020187.txt
technical/plos/journal.pbio.0020150.txt
technical/plos/journal.pbio.0020232.txt
technical/plos/journal.pbio.0030021.txt
technical/plos/journal.pbio.0020224.txt
technical/plos/journal.pbio.0020146.txt
technical/plos/journal.pbio.0020350.txt
technical/plos/journal.pbio.0020190.txt
technical/plos/journal.pbio.0020147.txt
technical/plos/journal.pbio.0030051.txt
technical/plos/journal.pbio.0020068.txt
technical/plos/journal.pbio.0020054.txt
technical/plos/journal.pbio.0020040.txt
technical/plos/journal.pbio.0030131.txt
technical/plos/journal.pbio.0020337.txt
technical/plos/journal.pbio.0020121.txt
technical/plos/journal.pbio.0030050.txt
technical/plos/journal.pbio.0020241.txt
technical/plos/journal.pbio.0020043.txt
technical/plos/journal.pbio.0030127.txt
technical/plos/journal.pbio.0020042.txt
technical/plos/journal.pbio.0020297.txt
technical/plos/journal.pbio.0030094.txt
technical/plos/journal.pbio.0020046.txt
technical/plos/journal.pbio.0020052.txt
technical/plos/journal.pbio.0030137.txt
technical/plos/journal.pbio.0030136.txt
technical/plos/journal.pbio.0020127.txt
technical/plos/journal.pbio.0020133.txt
technical/plos/journal.pbio.0020053.txt
technical/plos/journal.pbio.0020047.txt
technical/plos/journal.pbio.0030056.txt
technical/plos/journal.pbio.0030097.txt
technical/plos/journal.pbio.0020125.txt
technical/plos/journal.pbio.0020440.txt
technical/plos/journal.pbio.0020263.txt
technical/plos/journal.pbio.0020101.txt
technical/plos/journal.pbio.0030105.txt
technical/plos/journal.pbio.0020302.txt
technical/plos/journal.pbio.0020100.txt
technical/plos/journal.pbio.0020262.txt
technical/plos/journal.pbio.0030065.txt
technical/plos/journal.pbio.0020276.txt
technical/plos/journal.pbio.0020116.txt
technical/plos/journal.pbio.0020063.txt
technical/plos/journal.pbio.0030076.txt
technical/plos/journal.pbio.0030062.txt
technical/plos/journal.pbio.0020067.txt
technical/plos/journal.pbio.0020073.txt
technical/plos/journal.pbio.0020113.txt
technical/plos/journal.pbio.0020311.txt
technical/plos/journal.pbio.0030102.txt
technical/plos/journal.pbio.0020310.txt
technical/plos/journal.pbio.0020112.txt
technical/plos/journal.pbio.0020272.txt
technical/plos/journal.pbio.0020064.txt
technical/plos/journal.pbio.0020306.txt
technical/plos/journal.pbio.0030129.txt
technical/plos/journal.pbio.0020307.txt
technical/plos/journal.pbio.0020105.txt
technical/plos/journal.pbio.0020071.txt
technical/plos/journal.pbio.0020267.txt
technical/plos/journal.pbio.0020228.txt
technical/plos/journal.pbio.0020214.txt
technical/plos/journal.pbio.0020348.txt
technical/plos/journal.pbio.0020406.txt
technical/plos/journal.pbio.0020215.txt
technical/plos/journal.pbio.0020001.txt
technical/plos/journal.pbio.0020161.txt
technical/plos/journal.pbio.0020439.txt
technical/plos/journal.pbio.0020404.txt
technical/plos/journal.pbio.0020148.txt
technical/plos/journal.pbio.0020028.txt
technical/plos/journal.pbio.0020216.txt
technical/plos/journal.pbio.0020206.txt
technical/plos/journal.pbio.0020010.txt
technical/plos/journal.pbio.0020164.txt
technical/plos/journal.pbio.0020400.txt
technical/plos/journal.pbio.0020401.txt
technical/plos/journal.pbio.0020213.txt
technical/plos/journal.pbio.0020013.txt
technical/plos/journal.pbio.0020172.txt
technical/plos/journal.pbio.0020012.txt
```
Even this slight alteration to the command previously, it offers so much versatility and uses. 

