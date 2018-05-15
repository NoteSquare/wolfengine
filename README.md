# WolfEngine
## About
**WolfEngine** is an open source task process optimizing engine for exploratory data analysis using workflow design. 
With an automated system operation, combining dynamic optimization and asynchronous parallel calculation techniques give rise to faster calculation speed. Wolf Engine  also enables you to automatically optimize your software without revising original source code.

WolfEngine is being actively developed by NoteSquare Inc. which first started the idea to combine many different machine learning algorithms in different libraries. Now, NoteSquare Inc. uses WolfEngine in many task-oriented jobs in various environment.

Keep up with the latest news, release announcements by subscribing to [wolfengine@notesquare.co.kr]().

## Characteristics
* Dramatically increase calculation speed 
* Effectively decrease time in development cycle
* Efficiently utilize computer resources 
* Considerably reduce hardware maintenance costs
* **No NEED** to revise original source code 
* **No NEED** to learn optimization skills 

## How does it works?
![Pipeline](https://github.com/NoteSquare/wolfengine/blob/master/Pipeline_Wolf_Engine.gif?raw=true)

## Features
* Auto-Parallelization 
    *  
* Auto-Generator
    * Using asynchronous parallel calculation techiniques to avoid deadlock
    * Enabling the software to use low memory footprint for heavy input data
    * Duplicating list as inputs in order to match parallelized User-tasks
    * Combining duplicated list from parallelized User-tasks    
* Auto-IO-Cache
    * Caching the task based on its input and output data ensures the fast computation 
    * Pausing and continuing automatically in the long-running task workflow
    * Using efficient decompression algorithms makes faster reading and operating time 
* Auto-Scheduler 
    * Scrutinizing the most adaptive optimization techniques based on user's computing environment.

## WolfEngine GUI
**WolfEngine GUI** enables users to easily apply **WolfEngine Features** into their exploratory data analysis projects.

**Functions and Systems**

* Flowchart Function
    * Automade flowchart based on the order of user's original source code 
    * Customization flowchart by drag and drop on source code
        * Auto-Parallelization 
        * Auto-Generator 
* Debugging Function
    * Output Console
    * Processors Controllers
* Monitoring Function 
    * Real-Time CPU Usage Graph
    * Real-Time RAM Usage Graph
    * Operating Time
    * Run History 
        * version 
        * operating time
        * processors used
* File System
    * Hierarchical File System 
        * .weproj file 
        * module file 
    * Versioning System

## Supportive Languages

* Python 
* R, MatLab will be added soon

## Installation 

## Contribution guidelines

If you want to contribute to **Wolf Engine**, be sure to read through our contribution guidelines.

We use GitHub issues for tracking requests and bugs. 

## License

[GNU Affero General Public License v3.0](LICENSE)



