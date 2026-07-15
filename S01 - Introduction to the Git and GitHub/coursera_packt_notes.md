# Coursera | Complete Git Guide: Understand and Master Git and GitHub Specialization

[Specialization Link](https://www.coursera.org/specializations/packt-complete-git-guide-understand-and-master-git-and-github)


## Course 1 | Git Fundamentals – Getting Started with Git and GitHub
[Course 1 Link](https://www.coursera.org/learn/packt-git-fundamentals-getting-started-with-git-and-github-rf1ze?specialization=packt-complete-git-guide-understand-and-master-git-and-github)

### Module 1: Intro & Course Structure.     
[Repo](https://github.com/skibodaria/Coursera-Packt-Complete-Git-Guide)

1. **Introduction to Git and GitHub**: In this module, we will introduce you to Git and GitHub, covering their significance in version control and software development. We’ll also distinguish between Git and GitHub, shedding light on their distinct roles. This section will set the foundation for your journey through Git and GitHub, focusing on the core concepts you'll need to understand.

2. **Installation of Git and Configuration of the Shell**: In this module, we will guide you through the installation process of Git on various operating systems, ensuring smooth setups on macOS, Windows, and Linux. Additionally, we’ll configure the shell environment, enhancing your Git experience on macOS with iTerm2 and Zsh for improved terminal functionality.

3. **Basic Shell Commands**: In this module, we will introduce you to essential shell commands used in Git workflows, focusing on directory and file management. By the end of this section, you'll be able to navigate the command line, create, copy, move, and delete files—all vital skills for managing your Git repositories.

4. **How Git Works Under the Hood**: In this module, we will explore Git’s internal mechanisms, including the object model and the contents of the .git folder. You’ll dive deep into how Git stores and manages data, gaining a comprehensive understanding of objects like blobs, trees, and commits. We’ll also cover Git's use of hash functions to ensure data integrity and prevent collisions.

5. **Basic Git Operations**: In this module, we will cover the basic Git operations that are essential for version control. From creating your first commit to understanding the file lifecycle, we’ll ensure you are comfortable managing files, making commits, and navigating your Git project. This section lays the groundwork for more advanced Git workflows.

6. **Git Branches and `HEAD`**: In this module, we will focus on Git branches and the `HEAD` reference, which are critical for managing different lines of development. You’ll learn how to create, manage, and switch between branches, as well as explore how these concepts fit into a version control workflow. This section will help you navigate Git’s branching model with confidence.

### Module 2: Git and GitHub
1. **Git** is distributed version-control system; hashes the file/folders versions; keep them all; doesn't need internet connection; allows to get access to all historical versions of files;
2. **Git-Hub** is a hosting platform; perfect for collaborations; has features beyond just version control (e.g., one can host a web-site on GitHub); allows restore the repo even if it was removed locally.

### Module 3: Shell Commands
```bash
pwd             # current directory
ls              # list files / folders in the current directory
ls -l           # in table format
ls -la          # including hidden files
ls -a           # hidden files, no table

cd              # change to home folder
cd Desktop      # change directory to Desktop
cd ~            # changes directory to Home

clear           # clear tetminal

mkdir <name>    # create directory with name <name>

touch <file.xxx>    # create a file with name <file> and format <.xxx>

..              # alias for parent directory
cd ..           # changes directory to parent
.               # alias for current pirectory

open .          # opens current directory (MAC!)
start .         # opens current directory (WINDOWS!)

~ cd Desktop/new-folder  # change directory according to the path given (if exists)

nano                    # opens terminal text editor
vim                     # another text editor (also inside the shell)

nano test.txt           # opens this file in nano (PICO!)
control + o             # write changes
enter                   # commit
control + x             # exit

Tab                     # autocompletes the statement
TabTab                  # shows more options

echo                    # print to terminal
echo Hello, World!      # prints Hello, World! in terminal
echo 'Hello World!'     # also prints
echo "Hello World\!"     # will work with "" but needs to escape \!

man                     # manual on specific command
man clear               # gives manual for HELP command
man touch               # manual about TOUCH including all the options

help                    # lists possible commands/options

>                       # write to the file
echo "ANOOOOOOOOTHER FILE" > new_test.txt

>>                      # append to the file
echo "HELLO WOOOOOOOOOOOORLD" >> test.txt
echo "one more line just to check" >> test.txt

cat                     # list contents of the file
cat new_test.txt

rm <file_name>          # remove a file
rm -rf <name_of_folder> # removes a folder (stands for recursively remove + force)
```

**Relative Path**: if you don't start with `/` the path is **always relative** to the current directory.

**Absolute Path** always starts with `/`.

**Nota Bene**: With `man nano` I get manual for `pico`. Whyy?

### Module 4 | How Git Works Under the Hood

### Module 5 | Basic Git Operations


### Module 6 | Git Branches and `HEAD``

## Course 2 | Master Version Control – Branching, Merging, Collaboration
[Course 2 Link](https://www.coursera.org/learn/packt-master-version-control-branching-merging-collaboration-psnjz?specialization=packt-complete-git-guide-understand-and-master-git-and-github)


## Course 3 | Advanced Git and GitHub – Optimization and Automation
[Course 3 Link](https://www.coursera.org/learn/packt-advanced-git-and-github-optimization-and-automation-cfv1x?specialization=packt-complete-git-guide-understand-and-master-git-and-github)