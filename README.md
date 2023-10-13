# 0x00. AirBnB clone - The console 
Welcome to my readme file
## 0x00.Table of contents

+    0x01 Introduction
+    0x02 Environment
+    0x03 Installation
+    0x04 Testing
+    0x05 Usage
+    0x06 Authors

### 0x01 Introduction
Team project to build a clone of [AirBnB](https://www.airbnb.com/)

### The console will perform the following tasks:

+    create a new object
+    retrive an object from a file
+    do operations on objects
+    destroy an object

### Storage
All the file  in these resipository are handled by the *Storage* engine in the **FileStorage** Class.

### 0x02 Environment
[<img src="https://logos-world.net/wp-content/uploads/2020/11/GitHub-Symbol.png" width="50">](https://github.com)  [<img src="https://th.bing.com/th/id/OIP.Nl2NnLUSINXh-Iexj65F5QHaEK?pid=ImgDet&rs=1" width="50">](https://github.com) [<img src="https://th.bing.com/th/id/R.b1c66d2b33344feb0f619c5804026f44?rik=Z1uP%2bdIli64kfg&pid=ImgRaw&r=0" width="50">] 

All the development and testing was runned over an operating system Ubuntu 20.04 LTS using programming language Python 3.8.3. The editors used were VIM 8.1.2269, VSCode 1.6.1 and Atom 1.58.0  Control version using Git 2.25.1.

### 0x03 Installation

``` git clone https://github.com/Paulos-ui/AirBnB_clone.git ```

change to the *AirBnb* directory and run the command:
` ./console.py `

### Execution

In interactive mode:
```
$ ./console.py
(hbnb) help
EOF  help  quit
(hbnb)
(hbnb)
(hbnb) quit
$
```

In non interactive mode:

```
$ echo "help" | ./console.py
(hbnb)
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)
EOF  help  quit
(hbnb) 
$
```
### 0x04 Testing

All the test will be on the *test* folder

### 0x05 Usage

+ Start the console in interactive mode:

`$ ./console.py
(hbnb)`

# Authors:
* Khaoula Ouardi
* Jayeoba Tunmise
