---
layout: page
title: Install Python
permalink: /install-python/
nav_order: 3
---
# Installing Python
## Installing Python for windows

Python is an opensource programming lanugage which can be downloaded
freely from internet. The official web site of Python is [https://www.python.org/](https://www.python.org/){:target="_blank" rel="noopener"}

The download page for Windows
[https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/){:target="_blank" rel="noopener"}

Checking whether Python has been installed correctly. Open your command 
prompt in windows and type this command and press enter.
```
C:\Users\Krishnadas>py --version
```
This will output something like this, version number can be different depending upon the version you install.
```
Python 3.9.1
```

## Installing a code editor
### What is a code editor?
* It is specially designed for programming.
* It provides syntax highlighting over plain notepad kind of applications.
* It provides autocomplete features for many commonly used functions
in a particular programming language.
* Many code editors provide extra plugins/extensions which can be installed to add more features to that editor.

Some of the commonly used code editors for Python
* [Vscode](https://code.visualstudio.com/download){:target="_blank" rel="noopener"}
* [SublimeText](https://www.sublimetext.com/){:target="_blank" rel="noopener"}
* [Pycharm Community editon](https://www.jetbrains.com/pycharm/download/#section=windows){:target="_blank" rel="noopener"}
* [Atom](https://atom.io/){:target="_blank" rel="noopener"}

## Running python from commandline
Python file extension must be `.py` 

On Windows Enable Show File Extensions. Watch the below video if you 
want to know how to do that.

Running a python file named `main.py` from command line in Windows.
1. Create a file named `main.py`
2. Add the below code to it
```python
print("Hello world!")
```
3. Execute the program
```
C:\Users\Krishnadas>py main.py #windows path where file is created
$python main.py #linux/unix
```
4. This will output
```bash
Hello World!
```

## To run and test short codes you can use Python's inbuilt command line, type the below command in yout command prompt 
This is called `REPL`, Read Evaluate Print Loop. You can type a valid python command and after pressing enter it will be executed. If it is 
a block of code it will be executed once block is completed.
```bash
python-tutorials :✗ python # For Windows type py
Python 3.9.1 (v3.9.1:1e5d33e9b9, Dec  7 2020, 12:10:52) 
[Clang 6.0 (clang-600.0.57)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hi")
Hi
>>> exit() # Type this to exit from python shell or Ctrl + D
```
Video tutorial about installing and running Python on Windows
<iframe width="560" height="315" src="https://www.youtube.com/embed/nGFmxLG7pSA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
