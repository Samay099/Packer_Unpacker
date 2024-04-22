# Text File Packer And Unpacker

#### A GUI tool to pack and unpack text files 

The GUI provides functionality to pack text files of a directory and unpack them. 

- In case of Packing activity we maintain one file which contains metadata and data of
multiple files from specified a directory.

- In case of Unpacking activity we extract all data from packed files and we create all files according to its
metadata 

## Dependencies 

First, make sure Java is installed

Open a termainal and type:

    java -version

If the output looks like this, you are good to go:

    openjdk 21.0.2 2024-01-16

If the output looks like this :

    Command 'java' not found

Then latest version of JDK can be found [here](https://www.oracle.com/java/technologies/downloads/)


## Installation

- Once you've verified that Java is installed 

- Download the Packer.java from this repository.

## Usage Examples

**Note**: First, make sure the Directory of which files you want to pack **OR** the file you want to unpack lies in the same directory as of the Packer.java  

#### Compile the classes :

    javac Packer.java

#### Run the class file:

    java Packer

#### Login

Default Credentials.

- **Username** : **Admin**
- **Password** : **Admin**

#### Main Frame

On Main Frame user is given choice between the packing and unpacking activity.

![Main Frame!](/assets/images/mainFrame.png "Main Frame")

#### Packer Frame

Packer Frame accepts a directory name which contains the files to be packed and the name of the packed file from the user

![Packer Frame](/assets/images/packerFrame.png "Packer Frame")

#### Unpacker Frame

Unpacker Frame accepts name of packed file from user and unpacks all the files in the current directory.

![Unpacker Frame](/assets/images/unpackerFrame.png "Unpacker Frame")

## API Documentation

Detailed description on APIs is available in [API.md](/API.md)
