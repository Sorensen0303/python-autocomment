# Python-comment-script   
Commenting source code couldn't be easier!

#### Developed by [Derek Laker](http://github.com/dereklaker) at MTU with consulting from [Shane Sorensen](http://github.com/Sorensen0303)

### Overview   
Python-comment-script  will format and insert "side-bar" comments into your C source code. It's a simple as running the code, commenting what lines do, and ta-da! Commented source code.

## Running   
REQUIRES PYTHON 3 (for Python 2 support, goto branch "[Legacy-python2]()")   
`$ python3 comment_code.py`

## Features   
* Line-by-line comments
* Uniform tab length for all comments
* Preserves original source code
* Won't show anything if you don't put anything

## Changelog
###### Version 1.0
* Initial release


###### Released under MPL-2.0
### Sample Output
$python3 comment_code.py hello.c 


include <stdio.h>

Describe this line of code: include statements




Describe this line of code: 


int main(void) {

Describe this line of code: main function


	printf("Hello World!\n");

Describe this line of code: print statement


}

Describe this line of code: 

Your outputfile is named: hello.c

The source file is now renamed to: hello.c.src

$



