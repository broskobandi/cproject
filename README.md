# cproject
A simple shell script to automate the creation, building, and testing of projects written in C.

## Installation
```bash
sudo ln -s /full/path/to/cproject /usr/bin/
```

## Usage

Usage:
	cproject new [PROJECT_NAME] [OPTIONS]	= Create new project in current directory
	cproject build				= Build project found in current directory
	cproject run				= Run project in current directory
	cproject test				= Test project in current directory

Options:
	cproject new [PROJECT_NAME] -l | --lib	= Setup project as library
	cproject new [PROJECT_NAME] -g | --git	= Setup project as git repo
	cproject -h | --help			= Print this message
