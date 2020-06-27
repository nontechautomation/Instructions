## Install Python3 on Windows Machine
___

### Prerequisites
1. Check OS variation on the windows machine. If OS is 32 bit(X86) then get 32 bit version of python else get the 64 bit version. 

___

### Step1: Download Python 3

**Python2 is not supported since Jan 2020**

1. Navigate to official python website to [download the installer](https://www.python.org/downloads/windows/) for windows. 
2. Download installer based on the operating system. 
3. Navigate to the location where the installer is downloaded (Usually Downloads folder), then double click on the installer. 
4. Make sure to check ```Add python 3.X to PATH``` while installing on the first step as shown in the screenshot. 
5. After that follow the installer with all default options till end. If there is no option displayed then by the end of the installer, your system should have python installed. 

___

### Verify python3 installation

1. Naviage to command prompt on windows machine. ```Win + R``` to open ```Run``` and type ```cmd``` and press ```Enter```.
2. In command prompt type command ```python -V```. Make sure to use upper case V. 
3. If this command should return ```Python 3.X.X``` then you have successfully insalled python. Here ```X``` is the version associated with your install.  
4. If ```command not found``` error appears then make sure to add python in ```Windows Environment Variables``` and try again. 
5. Close and restart command after making environment variable changes. 

___

### Installing Automagica 

Python3 ships with pip to manage packages associated with python packages. Syntax to add a python package at global level is ```pip install <package name>```.

Automagica is an opensource library to automate common tasks which includes automating excel workflows, email workflows, web related automation etc. 

Command to install automagica:
```pip install automagica```

More information on this package can be found on [this link](https://pypi.org/project/Automagica/).

___

### Installing ipythonkernel 

```ipythonkernel``` is important to run automation in notebook environment. More information on this package can be found on [this link](https://ipython.readthedocs.io/en/stable/install/kernel_install.html)

```pip install ipykernel ```

### Setting up development environment

Till this point, all the required libraries and python has been installed on your machine. Now it is time to setup an editor which will be used to create scripts for automation. 

We are going to use neteract for development. But any editor supporting python shall work. I recommend using either nteract or jupyter notebook to use excercise files provided in the repo. 

1. Download [ntereact for windows](https://github.com/nteract/nteract/releases)
2. CLick on the installer and use default option to install nteract. 
3. After installation, open ntract. From ```Runtime``` in menubar, select ```Python3```
___

### Conclusion

So far we have installed all the tools to start automation. If you have any questions, then feel free to ask community through stackoverflow, telegram or quora. Since python has a huge community, people will always provide some sort of help on these websites. 