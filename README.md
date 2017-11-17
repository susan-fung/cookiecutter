# cookiecutter
A command-line utility that creates a directory structure for data analysis projects.

Created by Susan Fung.

Version 1.0 released on November 17, 2017

Licensed under BSD.

## Directory structure
The following items will be created:
  - Root directory:
    - `README`: overview of the project
    - `LICENSE`: legal agreement between the author and the user
    - `Makefile`: list of shell commands that will replicate your data analysis
  - `data` directory: raw, un-wrangled data and metadata
  - `doc` directory: text files such as documentation and manuscript
  - `result` directory: cleaned data sets, intermediate and final results/presentations
  - `src` directory: project source code, such as shell scripts, `.R` and `.py`

## How it works
1.	Clone the repository on Github
2.	Open your command line tool
3.	Navigate to the folder you want to create the directories
4.	Run the following command:
``` bash <directory where you cloned the cookiecutter repository>/cookiecutter.sh```
