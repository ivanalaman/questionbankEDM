# Question bank to EDM package

<p align="center">
  <span>English</span> |
  <a href="https://github.com/ivanalaman/questionbankEDM/tree/master/lang/portuguese_br">Portuguese-Brazil</a>
</p>

- [Introduction](https://github.com/ivanalaman/questionbankEDM#Introdução)
- [Standardization of the name of the question bank directories](https://github.com/ivanalaman/questionbankEDM#Standardization-of-the-name-of-the-question-bank-directories)
- [Standardizing file names](https://github.com/ivanalaman/questionbankEDM#Standardizing-file-names)
- [Building the question bank](https://github.com/ivanalaman/questionbankEDM#Building-the-question-bank)
  - [Workflow](https://github.com/ivanalaman/questionbankEDM#Workflow)

# Introduction
This repository is an attachment to the [EDM](https://github.com/ivanalaman/EDM) package of the [R](https://www.r-project.org/) software. The goal is a question bank storage location so that users can constantly share and update their assessments (evidence). We advise that when downloading the [EDM](https://github.com/ivanalaman/EDM) package, the graphical interface is used to create your question bank, in order to make it standardized among users and so that the [EDM](https://github.com/ivanalaman/EDM) package can correctly read such files.

## Standardization of the name of the question bank directories
When you create a question bank through the [EDM](https://github.com/ivanalaman/EDM) package, there is a standardization in the formation of the directory and subdirectories that are organized as follows:

![exes_br](https://github.com/ivanalaman/questionbankEDM/blob/master/images/exes_en.jpg)

It is important that this standardization is maintained.

## Standardizing file names
In order for your question bank to be shared with other users, there must be a standardization in the name of the files. This standardization is important, as it will allow the user to identify the source of the elaborated question. Below are some images of suggestions for how files should be named.

If your question is extracted from a book, with chapter and section, then a suggestion would be:

![ex1](https://github.com/ivanalaman/questionbankEDM/blob/master/images/ex1_en.jpg)

If the book has no section, just a chapter, then the file name can have the following format:

![ex2](https://github.com/ivanalaman/questionbankEDM/blob/master/images/ex2_en.jpg)

If the book has more than one author, then:

![ex3](https://github.com/ivanalaman/questionbankEDM/blob/master/images/ex3_en.jpg)

If the question is taken from a simulation or something, then the suggestion would be:

![ex4](https://github.com/ivanalaman/questionbankEDM/blob/master/images/ex4_en.jpg)

If the question elaborated is of its own authorship, then we would have:

![ex5](https://github.com/ivanalaman/questionbankEDM/blob/master/images/ex5_en.jpg)

## Forming the question bank
When you create a question bank through the application ([EDM](https://github.com/ivanalaman/EDM)), it is saved inside the standard folder created by the software [R](https: // www. r-project.org/) when installing an external package for the first time. If you don't remember or don't know where the folder is, type in the [R](https://www.r-project.org/) console the command `.libPaths ()`. In the Windows operating system, for example, the folder is usually created in **C:\Users\Yourname\Documents\R\win-library\4.0\EDM\questionbank\country\yourbank**.

To start forming your question bank, copy the folder created in the standard [R](https://www.r-project.org/) directory, as already mentioned in the previous paragraph, to another directory. This procedure is important because it will protect your bank of questions against any __bug__ that the software may present. As a suggestion, create a folder in your working directory called __question_bank__ and inside it paste the copied folder (your question bank). Also, inside the folder __question_bank__ create a file called __DESCRIPTION.md__ as shown in the image below.

![descr](https://github.com/ivanalaman/questionbankEDM/blob/master/images/descr_en.jpg)

The previous steps will keep your question bank organized and well documented. Every time you make a change to your question bank, change the numbering of the item __Version__ in the file __DESCRIPTION.md__.

### Workflow
With the question bank created in your working directory, it's time to start adding questions. The question format follows the standard of the [exams](https://cran.r-project.org/web/packages/exams/index.html) package. If you are familiar with the [LaTeX](https://www.latex-project.org/) program or [markdown](https://daringfireball.net/projects/markdown/), then check the official website of the package [exams](https://cran.r-project.org/web/packages/exams/index.html) at the following link: http://www.r-exams.org/. If you are not familiar with any of the aforementioned languages, don't worry, the [EDM](https://github.com/ivanalaman/EDM) package has prepared a graphical interface to make it easier to program your questions. See the [EDM](https://github.com/ivanalaman/EDM)  package page and see the various explanatory videos.

Once the question bank is formed, it's time to use it using the [EDM](https://github.com/ivanalaman/EDM) package. To do this, copy your question bank on your desktop into the library directory created by [R](https://www.r-project.org/). Note that you will do the reverse process of the one mentioned above, that is, copy from **C:\Users\Yourname\Documents\bank_of_name\yourbank** to **C:\Users\Yourname\Documents\R\win-library\4.0\EDM\questionbank\country\yourbank**.


