# HomeWork_10_-Sort-6-Numbers
```
Sort 6 numbers using for loops, costom method calls, and now an array.
```
## Introduction
```
A single array variable can reference a large collectiion of data.
Here is the syntax for declaring an array avariable :
    elementType[] arrayRefVar
    such as:
    int [] A = new int[6];
I declare one array variable such as numbers and use 
      A[0] = 13;
      A[1] = 14;
      A[2] = 50;
    	A[3] = 20;
    	A[4] = 15;
    	A[5] = 24;
to represent individual variable. 

```
## Project outline
```
Main() method
declaring an array avariable
using for loops
print the output
```
## References & Literature
```
    liang,Y. Daniel. *Introduction to JAVA Programming: Comprehensive Version. 
    * 10th ed. n.p : Pearson, 201.print.

```
## Java Code
```

public class HomeWork_10 {
    public static void main(String[] args) {
	
        
    	int [] A = new int[6];
    	A[0] = 13;
    	A[1] = 14;
    	A[2] = 50;
    	A[3] = 20;
    	A[4] = 15;
    	A[5] = 24;
    	for (int k=1; k<=6; k++){
    		for(int i=0; i<5;i++){
    			int n1 = A[i];
    			int n2 = A[i+1];
    			if (n1>n2){
    				A[i] = n2;
    				A[i+1] = n1;
    				
    			}
    			
    		}
    		
    	}
    	System.out.println("\nThe sore array is: "+ "{" + A[0]+"," + A[1]+ ","
    	+ A[2] +","+ A[3]+"," + A[4]+ "," + A[5] + "}");
	}

}

```
## Console output
```

The sore array is: {13,14,15,20,24,50}

```
## Command Prompt
```
$1 Start a local ewpository
1. Navigate to the foler we just created.
--use dir to see what is on the directory.
2. Set up my local repository.
--use git init to start a local repository.
--use git add . to add all my files.


Microsoft Windows [Version 6.1.7601]
Copyright (c) 2009 Microsoft Corporation.  All rights reserved.

C:\Users\User>E:
E:\>dir
 Volume in drive E is YUANYUAN
 Volume Serial Number is 8A4A-E951

 Directory of E:\

11/05/2015  03:06 PM         1,226,240 hhhahhahahhhahhhhaha ??.doc
04/23/2015  08:51 PM    <DIR>          ???
04/23/2015  08:52 PM    <DIR>          ??????
11/04/2015  11:34 AM            92,218 unforgetabble expeience.docx
11/10/2015  06:54 PM            18,944 You Zeng Field Experience Packet.doc
05/18/2015  09:30 AM    <DIR>          ?????
05/18/2015  09:32 AM    <DIR>          ??????
05/18/2015  09:33 AM    <DIR>          ? ? ?
05/20/2015  10:10 AM    <DIR>          English
05/27/2015  03:55 PM    <DIR>          Skypee
07/21/2015  07:30 PM    <DIR>          ????
08/30/2015  06:11 PM    <DIR>          ????
08/30/2015  06:12 PM    <DIR>          SWOSU
10/02/2015  10:17 AM    <DIR>          Camon Workspace
10/08/2015  03:03 PM    <DIR>          Users
11/01/2015  05:47 PM    <DIR>          New folder
               3 File(s)      1,337,402 bytes
              13 Dir(s)  10,100,121,600 bytes free


E:\>cd SWOSU

E:\SWOSU>dir
 Volume in drive E is YUANYUAN
 Volume Serial Number is 8A4A-E951

 Directory of E:\SWOSU

08/30/2015  06:12 PM    <DIR>          .
08/30/2015  06:12 PM    <DIR>          ..
10/12/2015  08:30 AM           417,625 English????--??????_????.htm
08/31/2015  08:13 AM    <DIR>          CS1_Workspace
09/01/2015  09:58 AM    <DIR>          eclipse-java-mars-R-win32
09/18/2015  09:42 AM    <DIR>          Operating Systems Class
09/21/2015  05:28 PM    <DIR>          Computer Science I
09/08/2015  03:33 PM    <DIR>          Fund of English
10/12/2015  08:30 AM    <DIR>          English????--??????_????_files
               1 File(s)        417,625 bytes
               8 Dir(s)  10,099,064,832 bytes free

E:\SWOSU>cd Computer Science I

E:\SWOSU\Computer Science I>dir
 Volume in drive E is YUANYUAN
 Volume Serial Number is 8A4A-E951

 Directory of E:\SWOSU\Computer Science I

09/21/2015  05:28 PM    <DIR>          .
09/21/2015  05:28 PM    <DIR>          ..
10/19/2015  10:18 AM    <DIR>          .metadata
11/09/2015  07:05 PM    <DIR>          Listing 4.16
11/09/2015  07:05 PM    <DIR>          rhftghn
09/14/2015  05:02 PM            18,846 HW _ 2.docx
09/15/2015  12:04 PM            45,568 HW _3.doc
09/14/2015  05:44 PM            11,776 HW3.doc
08/31/2015  08:26 AM       189,603,416 jdk-8u60-windows-i586.exe
08/31/2015  08:27 AM       171,043,550 eclipse-java-mars-R-win32.zip
10/19/2015  10:10 PM            56,320 Pre_Exam.HW _ 7.doc
10/26/2015  10:51 AM            19,840 1412_Fun_With_Functions_Project.docx
11/02/2015  03:04 PM    <DIR>          .recommenders
11/09/2015  06:21 PM    <DIR>          HomeWork _9
11/09/2015  07:05 PM    <DIR>          Listing_4_16 project
11/09/2015  07:13 PM    <DIR>          GitHub_files
11/09/2015  07:13 PM            38,802 GitHub.htm
11/10/2015  10:29 AM    <DIR>          Test
09/22/2015  01:08 PM            18,613 HW_4.1.docx
09/22/2015  01:11 PM            21,498 HW_4.2.docx
09/19/2015  11:53 AM         2,331,164 This work is licensed under the Creative
Commons A.doc
11/09/2015  10:52 AM            12,651 public class strings111232435465.docx
09/30/2015  03:43 PM            18,517 HW_5.docx
10/08/2015  02:52 PM    <DIR>          eclipse-java-mars-R-win32
10/09/2015  02:07 PM    <DIR>          AdditionGame1214_Project
10/13/2015  11:14 AM            12,706 GIT.docx
10/13/2015  03:18 PM            56,832 AdditionGameHW_6.doc
              15 File(s)    363,310,099 bytes
              12 Dir(s)  10,096,107,520 bytes free

E:\SWOSU\Computer Science I>cd "HomeWork _10"

E:\SWOSU\Computer Science I\HomeWork _10>git init
Reinitialized existing Git repository in E:/SWOSU/Computer Science I/HomeWork _10
/.git/

E:\SWOSU\Computer Science I\HomeWork _10>git add .

$2 Connect our local respository to our global repository
--1. Open a brower of choice
--2. Go to Github and sign in: https://github.com/login
--3. Add a new repositoryby clicking the green button .
--4. Follow the introductions to …or create a new repository on the command line

echo # Hello-Candy >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:yuanyuan01/Hello-Candy.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin git@github.com:yuanyuan01/Hello-Candy.git
git push -u origin master

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

```
## Summary
```
When you declaring an array avariable,
the elementType can be any data type,
and all elements in the array will have same data type .
For example,
the following code declares a variable A that references an array of int element.
such as : int [] A;
Then I also use for loops to control sort 6 numbers in java programming. 
```
