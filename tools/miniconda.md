## MiniConda vs. Anaconda

- Anaconda comes with full Python and hundreds of packages. It is convinence for beginners, but over weight for project use. 
- MiniConda comes with core pakcage management and Python core runtimes. You have to install all packages needed yourself. It is faster and light weighted.

## MiniConda Cheat Sheet

Task Category | Command | Comments
------------- | --------|---------
Basic | conda info | Display installation information
Package Management | conda update conda | Update Conda to the latest version
 . | conda install --help | Display help information for install command
 . | conda install A-PACKAGE | Install a package in Conda
 . | conda update --help | Display help information for update command
 . | conda update A-PACKAGE | Update a package in Conda
Virtual Environments | conda env list | Display current virtual environments, active environment marked with *
 . | conda create --name py35 python=3.5 | Create a new virtual environment
 . | activate py35 | Switch current conda environment
 . | conda list | Display all packages in current environment
Jupyter | conda install jupyter | Install Jupyter into current environment (if not already installed)
 . | jupyter-notebook | Start Jupyter Notebook. (To specify root folder, go to the root folder in windows, before run this command)
 . | export jupyter as pdf | conda install nbconvert ; install MikTax in windows 
 
(MiniConda3 4.5.11 windows 64bit)


