# Project Builder

This batch file create your web project folders.

All there is to know is commented in the file.

# Setting before use
Before all, edit the 10th line :
```
set  defaultPath="C:\xampp\htdocs"
```

It the folder where the piece of software will set your next projects.

By default it's *C:\xampp\htdocs* due to i work with XAMPP.



After, edit the 14th line :
```
set  keepOpen="TRUE"
```

Set `TRUE` if you want that the program open a cmd in your folder project.

Set `FALSE` if you want that the program close at end.

To finish, edit the 18th line
```
set git="TRUE"
```

Set `TRUE` if you want to init a git project else `FALSE`

# How to use
Simple. Open it and read.

It reminds you your default folder path and your existing projects in it.

It suggests you i f you want to change the the parent folder path.

Press **ENTER** if you don't want.

Next, it ask you the project name. If you just press **ENTER** the default name will be

*project_DATE_TIME*

And it show you what happen :
```
  Redirection to "C:\xampp\htdocs"
  Creation of the folder "Project_19022022_16482449"
  Redirection to "Project_19022022_16482449"

--- FOLDERS ---

  [Folder Created] : elements
  [Folder Created] : style   
  [Folder Created] : script       
  [Folder Created] : images       
  [Folder Created] : NOT_TO_UPLOAD

--- FILES ---

  [Files Created] : index.php
  [Files Created] : robots.txt 
  [Files Created] : sitemap.xml
  [Files Created] : style/style.css
  [Files Created] : script/script.js
  [Files Created] : elements/header.php
  [Files Created] : elements/footer.php
  [Files Created] : .htaccess
  [Files Created] : .gitignore
Initialized empty Git repository in C:/xampp/htdocs/Project_19022022_16482449/.git/
  [GIT INIT]
  [GIT ADD ALL]
```


Press any key to quit.

It will start a normal CMD in the project folder.
