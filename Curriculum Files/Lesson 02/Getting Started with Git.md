# Getting Started with Git

## Introduction

In this lesson, you will set up a GitHub profile and install the necessary software to manage your projects using the Git platform. Whether you are working on a science fair projects, school projects, personal projects, or even just work related to this course, the tools we will introduce in this lesson will be extremely valuable to your work. 

### What is Git?

Developed in 2005 by Linux operating system creator Linus Torvalds, Git is what is known as *version control software*. [1] It was developed to help coordinate the work done between teams of programmers and track changes to their code; however, it may be used to track changes between files of any type.

**Manual Version Control**

Consider this: let's say you are writing a book report, and decide to re-word one of your paragraphs. After the change, you decide you liked it better the way you had it before, so you use the *undo* button to go back to the way it was. In a way, the word processing software (like Microsoft Word, etc.) you were using handled a little bit of *version control* for you by storing a history of changes that you could revert to with the *undo* feature.

However, what if you had saved your file and closed the word processing software before going back to the earlier version. If you decided you wanted to go back to your previous paragraph then, you wouldn't have been able to rely on *undo* - that history is not saved along with the file. To avoid this happening in the future, you might start saving major versions of your program - "book_report_version_1.docx", "book_report_version_2.docx", "book_report_final.docx", etc. Now, you are handling your *own* implementation of version control. As long as you have saved all of your major changes in separate files, you can now go back to previous versions anytime you want, and you can even merge portions of previous work with your current versions... if you can find the version you are looking for.

**A Need for Version Control Software**

Using a system like this has its drawbacks: you have to keep track of each of your new versions manually, each version of your file takes up extra storage space on your computer, and it may be difficult to find the previous version you are looking for, should the need arise. If this were a collaborative project, however - let's say you were writing a report with a partner - this system would quickly become unmanageable and impractical, as you would each be keeping versions with your own edits with no easy way to determine who made which changes and whether or not you were working with the latest version of the report.

This is where version control systems like Git come in. Git manages your projects in the form of a *repository*, tracks changes to your documents via *commits,* and stores these previous versions efficiently in case you ever need to revert to a previous commit (version). It also provides you with tools to quickly and easily merge work with other collaborators on group projects, and allows you to *push* and *pull* your files to a remote location so that you can share files instantly via the Internet!

**Git Challenges**

As with any new software, there is a learning curve with Git. *Repositories*, *commits*, *pushes*, *pulls* - in some ways, it is a bit like learning a new language. However, once you start working with Git, it won't take long for you to start seeing the benefits and understanding the way it changes the way you think about your projects. The best advice I can offer at this stage is to not be afraid to get started, take things one step at a time, and not be afraid to ask questions!

### What is GitHub?

Git projects are broken into two main parts: a *remote repository*, which is a file storage location accessible by all of the collaborators on the project (typically somewhere on the Internet or a local server), and *local repositories* residing on the computers of each collaborator. There can be any number of local repositories, but each project has only one remote repository. 

GitHub (www.github.com) is a free hosting service for remote repositories; it is extremely popular in the open source community (a movement that started with open access to software *source code*, but has now grown to include a focus on open collaboration and open content across many fields, including scientific research). As of September 2019, GitHub reports having over 33 million users [2] and more than 100 million repositories [3], including at least 27 million public repositories [4], making it the largest host of source code in the world. [5]

I recommend using GitHub to host remote your remote repositories. It provides an easy-to-use public place to manage and showcase the content you create in a format that is recognized and respected by both academics and industry professionals. A well-curated GitHub profile is, in many ways, an even more impressive way of demonstrating your accomplishments than a résumé.

# Setting up Git

There are many ways to work with Git - some more user-friendly than others. The most direct way to work with Git is to install the Git software and run it through your computer's terminal. Although you will work with the Python programming language in the terminal later in this course, the commands needed to run Git can be hard to memorize and intimidating for new users. Instead, I highly recommend that you install a GUI (graphic user interface) client for Git. There are many options available, but the one I recommend is GitHub Desktop (https://desktop.github.com/) if you are a Mac or Windows user. For Linux users, I recommend Git Cola (https://git-cola.github.io/), although there are many options available (https://git-scm.com/downloads/guis).

These tools provide you with an easy way to set up repositories and perform the common Git operations you will be using throughout this course. 





## References

[1] "A short history of Git," *Pro Git*. Apress. 2014. [Online]. Available: https://git-scm.com/book/en/v2/Getting-Started-A-Short-History-of-Git. [Accessed: 27-Sep-2019]

[2] "Search - type:user," *GitHub*. [Online]. Available: https://github.com/search?q=type:user&type=Users. [Accessed: 27-Sep-2019]

[3] "GitHub passes 100 million repositories", *VentureBeat*. November 8, 2018. [Online]. Available: https://venturebeat.com/2018/11/08/github-passes-100-million-repositories/ [Accessed: 27-Sep-2019]

[4] "Search - is:public," *GitHub*. [Online]. Available: https://github.com/search?q=is:public. [Accessed: 27-Sep-2019]

[5] G. Gousios, *et al.*, "Lean GHTorrent: GitHub Data on Demand," *Proceedings of the 11th Working Conference on Mining Software Repositories*, pp. 384-387, June, 2014.