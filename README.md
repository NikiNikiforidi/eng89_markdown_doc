# Markdown documentation
## Repo/ Pycharm set up and Linux basics

### Setting up connection between pycharm and github

**Important: Changes made on git-hub must to downloaded to local**


# Heading 1: single hash # 
## Heading 2: double hash ## 
### Heading 3: triple hash ###
#### Heading 4: triple hash ####
##### Heading 5: triple hash #####
###### Heading 6: triple hash ######


- dash (-) makes bullet points


**To write anything in bold use ** at both end of your sentence, make sure to have no spaces**

- To print a single line of code, put code between two of `

`print('hello world')`

- To print multiple lines of code together, put between two pairs of ```

``` 
print(" Hello ")
print(" World ")
```

- To add a link or URL, use ['Title'] and then link. Example:
- [Python Basics] (https://github.com/khanmaster/eng89_markdown_documentation)

- To add an image: ![](path of the image)

### To initialise a repo in pycharm terminal 
#### If you have already set up a branch and want to push some updates/new files then only follow the steps with the *

- Initialises git *
- 'git init'
  
- List what files are going to be pushed (green for added, red for not), to ensure only required files are added to be sent
- 'git status'
  
- To add either all the files or selected files *
- 'git add. ' or 'git add name_of_file'

- To save changes and write a message *
- 'git commit -m "logical message" '

- Confirms and sets remote branch to main
- `git branch -M main`

- Adds remote to connect localhost with github repo (this line changes with every new repo)
- 'git remote add origin git@github.com:NikiNikiforidi/eng89_markdown_doc.git'

- Pushes the changes to github *
- `git push -u origin main`     

[MarkDown guides](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links)


## Linux basic commands that we can also use on Gitbach
### Commands we could use on Pycharm Terminal 

- who am I `pwd`
- where am I `uname` or `uname -a`
- Change directory `cd dir name with absolute path`
- Create file `touch file_name` or `nano file_name`
- how to save and exit nano `cntl + x` press `y` then `enter`
- to save and exit from `vi` or `vim` press `esc` then `:qw!` and `enter`
- Create dir `mkdir name_of_directory` 
- delete file `rm file_name` or force delete with `rm -rf name_file`  
- copy file `cp desination of file you want to copy` space `destination where to copy'`
- move file `mv destination of file you want to cut` space 'destination where to copy', also works to rename the file
- `ls` to list everything `ls -a` list everything including hidden files
- see content the file on terminal without opening the file `cat file_name`
  

  

