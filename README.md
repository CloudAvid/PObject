# Introduction

PObject introduces a method that called XObject. XObject defines a real world as a set of objects and their connections. This method help you to reduce complexity of design and to increase system flexibility and stability.

PObject is an object based on [XParam](https://github.com/CloudAvid/PParam/wiki/XParam) and [XISetParam](https://github.com/CloudAvid/PParam/wiki/XParam#22_XISetParam) featuers.

By PObject, developers define common attributes and abilities of an object that would be stored by [XISetParam](https://github.com/CloudAvid/PParam/wiki/XParam#22_XISetParam).

Any try to develop PObject is welcome.

# Installation
The first step is to get the lastest source and unzip it. run this command to configure PParam for your system:
```shell
$ ./configure
```
NOTE: if the configure file does not exist, run ./autogen.sh script.
The next step is building the various binary files. So, enter:
```shell
$ make
```
Then login as root and run:
```shell
$ make install
```
That's all ;-)

Use pkg-config to discover the necessary include and linker arguments. For instance,
```shell
$ pkg-config libpobject-1.0 --cflags –libs
```
# Documentation
Our wiki contains several [tutorials](https://github.com/CloudAvid/PObject/wiki) on how to use PObject.

# Contributing Code
If you are capable of contributing code changes, we encourage you to do so. You can help us in different fields:
* Develop new features
* Testing and bug reports
* Improving Documentation
* ... 

# Bugs
 Please use github [issues](https://github.com/CloudAvid/PObject/issues) to report bugs. 
# About
Copyright 2010-2020 [CloudAvid](https://www.cloudavid.com), released under the GPL license
