# Lab 1 Report - Remote Access and Filesystem (Week 1) - Joseph Pak

**Instructions:**
For each of the commands cd, ls, and cat, and using the workspace you created in this lab:

1. Share an example of using the command with no arguments.
2. Share an exmaple of using the command with a path to a directory as an argument.
3. Share an example of using the command with a path to a file as an argument.

So that’s 9 total examples (3 for each command). For each, include:

- A screenshot or Markdown code block showing the command and its output
- What the working directory was when the command was run
- A sentence or two explaining why you got that output (e.g. what was in the filesystem, what it meant to have no arguments).
- Indicate whether the output is an error or not, and if it’s an error, explain why it’s an error.

You will upload your submission by publishing the page on Github Pages, then printing the page to PDF and uploading to the Lab Report 1 assignment on Gradescope.


## The "cd" Command

#### 1. Share an example of using the "cd" command with no arguments.
<img width="565" alt="CDexample1" src="https://github.com/jpak0/cse15l-lab-reports/assets/48459170/a61e2e44-91ae-4763-8508-2d567a4a5c77">

- The working directory at the time of the command being run was /Users/josephpak (default home directory).
- The working directory before the command was even run was /Users/josephpak. After the cd command was run it remained on the same directory because the cd command takes you to the home directory, but it was already on their home directory so nothing changed because there was no need to. And essentially what it means to run a command without any arguments is just calling the most basic form of the command itself, by itself with no additional information/requests. 
- The output was not an error because the directory was already in the right place, and the cd command did its job properly.

#### 2. Share an example of using the "cd" command with a path to a directory as an argument.
<img width="571" alt="CDexample2" src="https://github.com/jpak0/cse15l-lab-reports/assets/48459170/58f92dd1-f442-4db4-a8f6-b285eb05796f">

- The working directory at the time of the command being run was /Users/josephpak/Desktop or my Desktop folder directory.
- The working directory was /Users/josephpak as default when I first opened the terminal on Mac. Then to engage a different example I used the cd command to navigate to the Desktop folder. And when I ran the cd command it directed us back to the default home directory of Users/josephpak.
- The output was not an error because the purpose of the cd command is to take us back to the home location no matter what current file directory we are at.

#### 3. Share an example of using the "cd" command with a path to a file as an argument.
<img width="570" alt="CDexample3fixed" src="https://github.com/jpak0/cse15l-lab-reports/assets/48459170/59d29cf5-87c1-4346-9f89-026df690103b">

- The working directory at the time of the command being run was /Users/josephpak/Desktop and /Users/josephpak/Downloads or both my Downloads and Desktop folder directories were attempted to be used.
- I got the output shown above by using CD to navigate to my Downloads directory and then trying to access a file directly. Then I also used the argument of Downloads (the folder) to use the cd command to navigate into there.
- Using cd to go to a direct specific file is an error. But what the output said isn't an error. Basically, the cd command can only be used to change the directory or path not to a specific exact file. 


## The "ls" Command

#### 1. Share an example of using the "ls" command with no arguments.
<img width="566" alt="LSexample1" src="https://github.com/jpak0/cse15l-lab-reports/assets/48459170/4c00a8d1-8e23-4480-8079-024425e6834b">

- The working directory at the time of the command being run was /Users/josephpak which is the default home directory.
- One thing that led me to my output was my choice to run the ls command on the default home directory by not using cd to re-direct to a different directory. Because there was no argument it was going to go off the default home directory anyway. Having no argument it just is the most basic run of the command where it shows everything within the current directory.
- The output was not an error because it correctly showed everything which is the files and directories within the current default directory because we didn't provide an argument to specify which directory.

#### 2. Share an example of using the "ls" command with a path to a directory as an argument.
<img width="562" alt="LSexample2" src="https://github.com/jpak0/cse15l-lab-reports/assets/48459170/c89df43f-e61e-42a0-87c3-6aab9e366fe4">

- The working directory at the time of the command was /Users/josephpak/Downloads which is my Downloads folder directory.
- The thing that led to my output was running the default no argument ls command on the default home directory. So it essentially showed all files and directories that exist on my default home directory of /Users/josephpak.
- The output was not an error because it showed all the files and directories that existed in my home directory.

#### 3. Share an example of using the "ls" command with a path to a file as an argument.
<img width="567" alt="LSexample3" src="https://github.com/jpak0/cse15l-lab-reports/assets/48459170/4829b4af-c621-4382-8fbe-f48cd46c7c97">

- The working directory at the time of the command is /Users/josephpak/Downloads/Screenshots or my screenshot folder within the directory of my Downloads folder.
- The primary thing that affected my output was the use of an argument with my ls command. It specified exactly what directories, subdirectories, and lastly exact single file to go to. So the ls command was run on a single file and it listed it back in the terminal of the file I requested.
- The output was not an error because it showed the singular file that I requested through the argument specifying which directories to go through. 

## The "cat" Command

#### 1. Share an example of using the "cat" command with no arguments.
<img width="572" alt="CATexample1" src="https://github.com/jpak0/cse15l-lab-reports/assets/48459170/6e280bf9-342b-4682-94ad-e9193fa69c97">

- The working directory at the time of the command is /Users/josephpak or the default home directory.
- The cat command was run without arguments on the home directory. This simple command call basically made it so it just copied exactly what I input into the terminal, so it just repeated everything I communicated to the terminal.
- The output was not an error because it copied my input, so input=output which is correct.

#### 2. Share an example of using the "cat" command with a path to a directory as an argument.
<img width="572" alt="CATexample2" src="https://github.com/jpak0/cse15l-lab-reports/assets/48459170/2492cb59-88a1-454a-b051-df434843a5d8">

- The working directory at the time of the command is my Downloads folder directory.
- The argument I had alongside the cat command which affected my output was having the command go to a directory of my /Downloads folder.
- The output was an error because it just repeated "Is a directory" instead of having a usable output. I found out that the cat command cannot be used for directories but it must be for specific files.
  
#### 3. Share an example of using the "cat" command with a path to a file as an argument.
<img width="568" alt="CATexample3" src="https://github.com/jpak0/cse15l-lab-reports/assets/48459170/3003575e-503b-4a26-be61-1af8781e9706">

- The working directory at the time of the command was my Downloads directory.
- The argument I had alongside the cat command was a specified singular .txt file within my Downloads directory.
- The output was correct because it read the contents of the file I put in and displayed the contents of the .txt file back onto the terminal screen. 
