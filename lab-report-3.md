# Lab Report 3 - Researching Commands

# The 'find' command

## 1. Finding a single file by name
 We can use the find command in order to find a certain file. While I was in the technical directory, I used the command:
 `find technical -name "chapter-1.txt"` in order to find the file `chapter-1.txt` for example. This is what the output was when running this command:
 ```
 technical/911report/chapter-1.txt
```
Another example of finding one specific file would be the following: `find technical -name "1468-6708-3-4.txt".` The following is the output:
```
technical/biomed/1468-6708-3-4.txt
```

In the above examples, `technical` is where the find command will start its search for these specific files. The `-name` specifies that we want to look for files with a specific name. This command is very useful when you know the specific file name you are looking for, but don't know where to find it. This is especially useful in a larger directory full of many files and folders where it's hard to keep track of all the files. 




## 2. Using * to find many files
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
Even this slight alteration to the command previously, offers a different use for the command `find`. This command can be useful if we 
wanted to look for all the reports or all the journal txt files. It is useful if we wanted to look for a group of files that all contain a similar word in the file name or those that contain a pattern, such as the examples above. It's useful when you don't know the exact name but rather a keyword such as "chapter" or "journal". 

## 3. Searching for empty files or directories
As I did my reasearch I found out that you can actually search for empty directories or files by including `-empty`. Before I created another txt file that was empty, I tried using `find technical -empty` on the file system. But because there were no empty files or directories, I didn't receive anything in my output:
```
```
I actually created an empty txt file in order to see what the output would be. I created a file with the name `chapter-empty.txt` in the `911report` folder. When running the command, `find technical -empty` again, I received: 
```
technical/911report/chapter-empty.txt
```
It provided me with the path of the empty file. I didn't know you can use the `find` command to look for these empty files or directories but it could be useful 
when trying to declutter and remove empty files from a file system. I also found that by tagging on `-delete` it would remove this said empty file. 

## 4. Finding specific files and deleting them

One of the ways you can use the `find` command is to search for a specific file and then delete it. The command that I used is 
```
find technical -type f -name "chapter-empty.txt" -exec rm -f {} \;
```
In this examples, I deleted the empty file that I made with my previous example. I didn't really recieve an output but rather saw that the file disappeared from this file system.

I wanted to delete other file that had already been in the file system previously so I used the command `find technical -type f -name "rr*.txt" -exec rm -f {} \;`
to delete the files with the pattern `rr*.txt` from my file system. This also didn't provide me with an output but instead deleted these files from my directory:
```
technical/biomed/rr73.txt
technical/biomed/rr74.txt
technical/biomed/rr171.txt
technical/biomed/rr167.txt
technical/biomed/rr166.txt
technical/biomed/rr172.txt
technical/biomed/rr37.txt
technical/biomed/rr196.txt
technical/biomed/rr191.txt
```
In the commands I gave above, I specified the file type by writing `-type f`. This would limit the search to only files and not directories. The word `-exec` allows us to execute a command on the files that were found. This command is useful if you wanted to delete a specific file or files with a patterned file name like I showed above. Honestly I think that this command is a little scary because it just deletes certain files without confirmation of anything but I can see why it would be useful if you knew what you wanted to delete. 

The sources that I used were:
[Source 1!](https://www.redhat.com/sysadmin/linux-find-command)
[Source 2!](https://www.tecmint.com/35-practical-examples-of-linux-find-command/)





