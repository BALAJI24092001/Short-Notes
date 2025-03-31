# BASH - Bourne Again Shell

<!--Made in 1989-->

BASH is the programming language used to interact with the Operating System.

As with any programming language, the first baby step in learning this programming language is to print the string "Hello World" to the colsole.

## Introduction

```Shell
echo "Hello World!"
```

let's say we saved this code in a file named first_code.sh, with the extension `.sh`. Now we have the run all the lines in this file from the terminal. Use the below code.

```Shell
bash first_code.sh
```

The file by itself is not exectuetable file, so we need to add exectuetable permissions to the file. Do it useing the code below.

```Shell
chmod +x first_code.sh
```

**Exercise problem**

1. Create a .sh file that prints three statements on the console and each takes 3 seconds before the next line prints. Also add the exectuetable permissions tot he file so it can run independently without explicitly run by the bash command.
   S
   Put this in a file with extension .sh

```Shell
echo "Hi there, nice to meet you!"
sleep 3
echo "How is your family, it's been a while since we last met, isn't it?"
sleep 3
echo "Anyways, got to go now, see you around."
```

## Variables

How to get a user input and save it into a variable and use it later when we need it.

```Shell
echo "Enter your name"
read name
echo "I'm going to print what you've given as input. You've given input as : $name"
```

Other way to make use of variables is to get them as arguments when the user runs the file

```Shell
name=$1
echo "I'm going to print what you've given as input. You've given input as : $name"
```

<!-- NOTE: the code is case sensitive and character sensitive, no additional characters are supposed to be there -->

running the file with the argument

```Shell
bash first_code.sh balaji
```
