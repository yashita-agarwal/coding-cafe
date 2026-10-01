1. pwd prints the currently open directory's path onto the terminal
2. 'ls -Force' shows hidden files that 'ls' doesnt.
3. mode shows the different types of files/items
4. It works from the parent folder because the parent folder contains the 'coding-cafe' folder. `coding-cafe\week02` is a relative path because it doesnt show the full path like '"C:\Users\YASHITA\OneDrive\Desktop\coding-cafe\week02"'
5. 'mv' first moved the README-backup.md file from the 'coding cafe' folder to the 'week01' folder
during the 2nd time, 'mv' moved the README-backup.md to old-readme.md, after this the README-backup.md didnt exist (unlike cp)
6. There are 17 folders in my path.
7. C:\Users\YASHITA\AppData\Local\Programs\Python\Python314\python.exe
8.usr/bin/python3 was her output.
 our outputs were different because we have python installed in different locations on our PCs.
9. pyton : The term 'pyton' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a
path was included, verify that the path is correct and try again.
At line:1 char:1
+ pyton
+ ~~~~~
    + CategoryInfo          : ObjectNotFound: (pyton:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
This means the shell could not find pyton in any of the folders listed in the path.
10:.venv did not appear with ls because .venv is a hidden folder
11:'.venv' appears in the source for python (C:\Users\YASHITA\OneDrive\Desktop\coding-cafe\.venv\Scripts\python.exe) showing that the virtual environment is active.
12: No, the paths are different. This tells me that Activate.ps1 changed my PATH so that python is found inside .venv
13:requests liek certifi, charset-normalizer,idna,urllib3 were added to the list
14: C:\Users\YASHITA\AppData\Local\Programs\Python\Python314\python.exe
15: -Recurse shows us all the subfolders and items too instead of just the folders present in the current directory
16: Ctrl+C interrupted the running session, while Ctrl+Z followed by Enter exited the session