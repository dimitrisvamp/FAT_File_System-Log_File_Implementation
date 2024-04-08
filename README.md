# FAT_File_System-Log_File_Implementation

## University Project
A project from Computer Science and Engineering department of the University of Ioannina (UOI).

## Description
The goal of this project is to implement a log file for modifications to the FAT file system in the LKL (Linux Kernel Library).

Many operations of the FAT file system consist of multiple stages that must be completed for an operation to be considered successful. <br />
However, a sudden interruption of the system while performing an operation that has not been completed can lead the file system into an inconsistent state. <br />
For this reason, we log the operations to a file before updating the system's structures so that in case of failure or error, the operations stored in the log file can be repeated.

## Uploaded Files
This repository contains only the files that were modified for the project's needs and not the entire LKL sources and FAT file system.

## More Information
For more information regarding the project and its implementation, you can read the Report.pdf file that is uploaded. <br />
Notice that Report.pdf is written in Greek.
