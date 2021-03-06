<img src="https://raw.githubusercontent.com/Team-AlvarezChoque/DemonDrive/master/web/images/dd.png" width="200">

# DemonDrive

Project part of Principles of Operating Systems (IC6600) course. That has the aim to learn about client-server scheme and simulate a File System (to perform some functions about it).

[GitHub Page](https://team-alvarezchoque.github.io/DemonDrive/)

## Developers

Adrián Álvarez Calderón [@adalvarez](https://github.com/adalvarez)

Michael Choque Núñez [@Feymus](https://github.com/Feymus)

---

## What is it?

Its about a project of the course Principles of Operating Systems (IC6600) in Technological Institute of Costa Rica that wants to develop a web-server aplication to emulate a File System.

The purpose of this project is to implement a Web drive for files. The intention is to put into practice knowledge about File Systems. For this, the functions of the File System that are broken down later will be implemented. It is a Web application where users can request a space for file storage. All the information management of the files is achieved from a .json file.

#### Functions

* **Create Drive**
* **Enter Drive**
* **Create file**
* **Create directory**
* **Change directory**
* **List directories**
* **Modify file**
* **Show properties**
* **Show file**
* **Copy**
    * **RV**: Means, copy a actual file to virtual file (virtual file system).
    * **VR**: Means, copy a virtual file to actual file.
    * **VV**: Means, copy a virtual file into another directory.
* **Move**
* **Delete**
* **Share**

<img src="https://raw.githubusercontent.com/Team-AlvarezChoque/DemonDrive/master/docs/img/1.PNG" >

#### Requirements

* [Commons IO](https://commons.apache.org/proper/commons-io/download_io.cgi) *
* [Java JSON](http://www.java2s.com/Code/Jar/j/Downloadjavajsonjar.htm) *
* Java EE with Glassfish

*Means that the requirement is inside this project.

#### Important

This project is develop for a Windows enviroment, because require of the followings files (included):
* C:/drive/id.txt: With a number to identify each file, recommended inital 1.
* C:/drive/drive.json: With the following structure:
```
{
    "accounts":{
        
    }
}
```