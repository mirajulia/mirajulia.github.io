---
layout: default
---
### Command Line Course

This course was an introduction to command-line tools, aimed at linguists. During the course we learned to use the Unix command-line and perform various tasks. We learned the basics of Regular expressions, Python virtual environments and using version control. A more in depth description of the course can be found [here](https://courses.helsinki.fi/fi/KIK-LG219/129824412).

##### Week 1: Introduction to Command Line Environments

Starting at the very basics, we learned how to run a command-line environment on our personal computers and how to navigate the Unix environment. We practiced creating, moving and removing files and directories, and started getting familiar with some text editors on the command-line, such as Emacs. We also learned how to download files with `wget`.

I had previously used command-line in some of my courses, so the basic file managemen commands were somewhat familiar to me, even if I had mostly forgotten about them. Working on command-line, one of the significant aspects is definitely the lack of graphical user interface. It stroke me especially once we started editing files on Emacs. Remembering the key combinations for moving around the file efficiently and editing it felt very difficult.

##### Week 2: Navigating a UNIX System

On the second week we kept diving in deeper to the Unix system, learning more about it's structure, symbolic links, privacy and processes. We learned how to compress and decompress files and directories with `gzip` and `tar` and how to change file permissions with `chmod`. We also practiced forming a remote connection to a server.

The content of this week felt basic but important.

##### Week 3: Basic Corpus Processing

While the first 2 weeks focused on getting used to working with the Unix environment, on the third week we started to see what use it can be to linguists. We learned about character encodings and processing text files. We were introduced to many commands used for processing text files. Here is a small list of examples.

Command | Description
--- | ---
wc | Counts lines, words or bytes in a text file.
uniq | Removes repeated identical lines from a text file.
sort | Sorts lines in a text file to alphabetical or numerical order.
tr | Transforms specified characters into other characters, e.g. upper case letters to lower case letters.

We started getting familiar with Regular Expressions, and how to use them in text processing with the `grep`command. We also learned about formatted text files such as csv and tsv files.

This week things started getting more concrete. I had dabbled in processing text files in command-line before, so I was somewhat familiar with the concepts, but I definitely needed a refresher. The information about character encodings was really interesting, even though it took some time to wrap my head around it.

##### Week 4: Advanced Corpus Processing

Following the basics of corpus processing, we learned to pipe simple commands together to complex command pipelines. We also learned the `sed` command, which has a lot of usages in corpus processing.