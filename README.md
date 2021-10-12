# sourceCode_of_python_modules

Ever wondered where all the pip installed modules go to, if that was a no then I got you.  
*Note: This only works for the modules that you have installed on your desktop Previously.* 

## Table of contents
⦿ [What's an module](#What-is-a-module)  
⦿ [path-of-modules](#path-of-modules)  
⦿ [pros-and-cons-of-modules](#pros-and-cons-of-modules)  
⦿ [single-function-importing](#single-function-importing)  
⦿ [renaming-module](#renaming-module)  
⦿ [user-defined-module](#user-defined-module)  
⦿ [builtins](#builtins)

## What-is-a-module
Before going into the topic let's know what's actually an module is ? 
Module is a normal python file which can be written by anyone and can also be accessed through other program's which reside in your local storage area.  
Module's can be compared to a function i.e reusable code, but on a large scale which includes everything that python can offer.
You can use modules in your program using below command.

	import module name
	
## path-of-modules

First import the module which you want to locate the path of.

	import module_name
	print(module_name.__file__)
	
	output:
		C:\Users\bhargav\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.9_qbz5n2kfra8p0\LocalCache\local-packages\Python39\site-packages\module_name

You can find the code for this in the attached python [file](https://github.com/BhargavKadali39/sourceCode_of_python_modules/blob/main/locateTheFile.py)

## renaming-module 
If the module name is too complex to repeat again and again we can use it's aliases by defining it as below command.

	import this_module-name_Iis_big as big
	
Here I used my alias as big but you can use words of your choice.


## pros-and-cons-of-modules
As we all know modules are reusable but also you can view it's source code and use part of it to make your code a little bit more optimized.  
Through modules we can use other program's functions at our ease but when you don't know what part is it actually going to be used  
then use can use below command to import all functions from module  

	from module_name import *

This will be very handy but increases the execution time, so I recommended you to use this only while testing phase.

## single-function-importing

When trying to design something we end up using more than enough amount of modules in our code which is a big no no.
To avoid doing it we can import single or multiple function of a module using the below command.

	from math import pi
	
By doing this your python interpreter won't load the whole module but only the part you asked for.

## user-defined-module
Yes, you heard me right we can create a module of our choice and the requirements are as below 

	⦿ Create a python code file with .py extension.
	⦿ Add relevant code to the program(module) and save it.
	⦿ import your module to any other program using the name of it.
and you're good to go.

## builtins
Ever wondered how commands like print and all works, it's because of the __builtins__ module which are pre-imported into your python file  
which means no import required for them as they are very commonly used.
