# CSE 15L: Servers and Bugs

## Intro:

Hello, my name is Brian Ponce. In this second lab report, I will be going over the following:

* The web-server: StringServer
* One of the bugs from lab #3

## String Server:

Code for StringServer:

![code](https://raw.githubusercontent.com/bponce04/cse15l-lab-reports/main/StringServer%20code.png)

Screenshot #1: 

![screenshotOne](https://github.com/bponce04/cse15l-lab-reports/blob/main/sc%20One.png?raw=true)

Methods used:

* `.getPath()`: used to get the URL Path
* `.getQuery()`: used to get the query component of the URI (returns null if none found)
*  The most important arguments in each of the two screenshots are checking whether the query equals `null` and if it starts with `s=`, if so then it can concatenate the old and new Strings together using `\n`
