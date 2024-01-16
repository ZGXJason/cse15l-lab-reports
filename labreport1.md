# lab report 1
## `cd`
**cd with no argument**

![Image](cd1.png)

  
The working directory is the home directory, which is usually represented by `/`
 
Since `cd` is executed without any arguments, the user is still returned to the home directory. 

There is no any error in this case. 

**cd with a path to a directory as an argument**

![Image](cd2.png)

The working directory when the command was run is the home directory `/`

Since the `cd` is used to switch the current working directory to the given path, the output should show that the working directory becomes ~/lecture1

There is no any error in this case.

**cd with a path to a file as an argument**

![Image](cd3.png)

The working directory when the command was run is the home directory `/`

There is a not a directory error in this case, since `cd` is used to switch the directory to another directory. However, a file itself cannot be considered as a directory. Therefore, there would not be an output. 

## `ls`
**ls with no argument**

![Image](ls1.png)

The working directory when the command was run is the home directory `/`

Since the `ls` list the files and folders the given path, and the given path is home directory, the output would be the only folder "lecture1" under the given path. 

There is no error in this case. 

**ls with a path to a directory as an argument**

![Image](ls2.png)

The working directory when the command was run is the home directory `/`

Since the given path is `/home/lecture1`, the output would be the files and folders under lecture1.

There is no error in this case. 

**ls with a path to a file as an argument**

![Image](ls3.png)

The working directory when the command was run is the home directory `/`

Since the given path is '/home/lecture1/Hello.java', the output would be Hello.java

There is no error in this case. 

## `cat`

**cat with no argument**

![Image](cat1.png)

The working directory when the command was run is the home directory `/`

Since cat is used to print the contents of files given by the path and the path is a directory, there wouldn't be any output

There is no error

**cat with a path to a directory as an argument**

![Image](cat2.png)

The working directory when the command was run is the home directory `/`

Also because the given path leads to a directory, there is no output.

There is no error.

**cat with a path to a file as an argument**

![Image](cat3.png)

The working directory when the command was run is the home directory `/`

Since the given path leads to a very specific file called Hello.java, the output would be the all content in that file.

There is no error in this case 
