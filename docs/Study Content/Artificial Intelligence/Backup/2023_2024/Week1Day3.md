---
sort: 3
---

## __History of AI & GitHub__

### Week 1: Chapter overview

I. Philosophy of AI & Information literacy <br>
II. DataLab I: Creative Brief <br>
III. __History of AI & GitHub__ <br>
IV. Python programming <br>
V. DataLab II: Creative Brief & Presenting <br>

### 1. Introduction

Today's independent study material focuses on the history of AI. In particular, we will explore the famous article Computing Machinery and Intelligence by Alan Turing (1950). This is the first, and definitely not the last, research paper we will discuss in the program. As a data professional, it is important to stay up to date with new developments in the field. Furthermore, it is good to be familiar with the seminal works of AI. One way of doing so is by reviewing these scholarly texts. Finally, by the end of today, you will receive instructions on working with GitHub and have the opportunity to apply your newly acquired knowledge of version control by making your first 'commit' to GitHub.

__After this chapter, you will be able to:__

- [ ] List, and describe key moments in the history of AI
- [ ] Explain the procedure, and main objective of Turing's 'Imitation Game'
- [ ] Explain what version control is and why it can be useful
- [ ] Implement version control using 'GitHub Desktop,' a Graphical User Interface for GitHub 

__Homework exercises__

For the DataLab preparation (Week 1, Friday), you are expected fill in a Microsoft Teams Form called ```DataLab Preparation (Week 1, DataLab II)```:

ADD EMBEDDED MICROSOFT FORM

If the embedded Microsoft form does not work in your browser, click [here](ADD URL).

To avoid multiple submissions, answer the questions that pop up (:pencil:) as you navigate the content below in a text editor of your choice (e.g., Notepad ++, Word, etc.) before entering them into the Microsoft Form. 

__Questions or issues?__

If you have questions or issues regarding the course material, please post them in the Q&A channel of Microsoft Teams. 

***

### 2. History of Artificial Intelligence

#### 2.1 Timeline

The early beginnings of AI, can be traced to the Ancient Greek period when philosophers started to describe human thinking as a symbolic system. Additionally, one of the first notions of a 'robot' can be found in Greek mythology:

> THE FIRST “ROBOT” to walk the earth—in ancient Greek mythology— was a bronze giant called Talos. Talos was an animated statue that guarded the island of Crete, one of three wondrous gifts fashioned by Hephaestus, god of the forge and patron of invention and technology. These marvels were commissioned by Zeus, for his son, Minos, the legendary first king of Crete. The other two gifts were a golden quiver of drone-like arrows that never missed their mark and Laelaps, a golden hound that always caught its prey. The bronze automaton Talos was charged with the task of defending Crete against pirates. Talos patrolled Minos’s kingdom by marching around the perimeter of the large island three times each day. As an animated metal machine in the form of a man, able to carry out complex human-like actions, Talos can be spoken of as an imagined android robot, an automaton “constructed to move on its own.” Designed and built by Hephaestus to repel invasions, Talos was “programmed” to spot strangers and pick up and hurl boulders to sink any foreign vessels that approached Crete’s shores. Talos possessed another capability too, modeled on a human trait. In close combat, the mechanical giant could perform a ghastly perversion of the universal gesture of human warmth, the embrace. With the ability to heat his bronze body red-hot, Talos would hug victims to his chest and roast them alive. (Mayor, 2018)

Throughout the centuries, scholars from various disciplines have made significant contributions to the field of AI. To name a few of them: al-Jazari, Leonardo Da Vinci, Ada Lovelace, Norbert Wiener, and Alan Turing.

However, the field of 'artificial intelligence' was not formally founded until 1956. It was at a conference, held at Dartmouth College, New Hampshire, were John McCarthy first coined the term 'artificial intelligence', which he defined as '... the science and engineering of making intelligent machines, especially intelligent computer programs' ([Source](http://intelligentstory.com/the-quest-for-ai.html)).  

After some setbacks in the 1970s and 1980s, also referred to as the AI winters, the field of AI has seen rapid advancements due to, among others, the introduction of deep learning, big data and artificial general intelligence in the early 2000s.

:pencil: __2.1a__ Watch the video on the History of AI by YouTube´s AI with Alex.

<iframe width="896" height="504" src="https://www.youtube.com/embed/JjQGKSOTHa4?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

*Video 1. History of AI by YouTube´s AI with Alex.*

:pencil: __2.1b__ Read the article ['The Ancient Quest for AI'](http://intelligentstory.com/the-quest-for-ai.html) by Valerie Morignat and/or Chapter 1.3 of AIMA (p.35-45).

:pencil: __2.1c__ Find, and describe one 'milestone' in the history of AI. Be creative, so no 'milestones' by Alan Turing! No worries, we are going to extensively discuss his accomplishments in DataLab I, Week 2 :smiley:

#### 2.2 Alan Turing 

The rise of artificial intelligence forces us to rethink what robots mean to society and what their role is to be. They are far better at arithmetic, but are they really as intelligent as us? What constitutes intelligence? And should we fear being replaced by these digital machines in the future? Alan Turing was the first to examine the relationship between humans and digital machines.

<img src="./images/alan_turing.jpg" alt="Books banner" width="500"/>

*Figure 1. Portrait of Alan Turing made up by binary numbers.*

In the article Computing Machinery and Intelligence (1950), Turing lays the foundation for modern day AI. He introduces an behavioural test, the Turing Test, and discusses some objections raised in relation to this test. As a result of his contributions to the field, he also called one of the 'founding fathers' of AI.

:pencil: __2.2a__ Besides the Turing Test, Alan Turing is renowned for his work on:
\
1.
\
2.
\
3.

Fill in the blanks.

<div style="padding: 15px; border: 1px solid transparent; border-color: transparent; margin-bottom: 20px; border-radius: 4px; color: #a94442; background-color: #f2dede; border-color: #ebccd1;">
Alert: Whoever has the quirkiest fact on Alan Turing will receive a candy bar at the end of the workshop in DataLab I, Week 2.
</div>

:pencil: __2.2b__ Read Wikipedia's summary of [Computing Machinery and Intelligence](https://en.wikipedia.org/wiki/Computing_Machinery_and_Intelligence#:~:text=Computing%20Machinery%20and%20Intelligence%20From%20Wikipedia%2C%20the%20free,as%20the%20Turing%20test%20to%20the%20general%20public.)

:pencil: __2.2c__ Watch the video 'Turing Test: Can Machines Think?' by the highly popular podcast-making AI researcher Lex Fridman.

<iframe width="896" height="504" src="https://www.youtube.com/embed/MGW_Qcqr9eQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

*Video 3. 'Turing Test: Can Machines Think?' by Lex Fridman.*

Did you enjoy the summary and the video, and want to take a deeper dive into Turing's Computing Machinery and Intelligence? Check out the original article, which you can find, [here](https://academic.oup.com/mind/article/LIX/236/433/986238).

<div style="padding: 15px; border: 1px solid transparent; border-color: transparent; margin-bottom: 20px; border-radius: 4px; color: #8a6d3b;; background-color: #fcf8e3; border-color: #faebcc;">
Tip: If you are having difficulties reading the mathematical equations or understanding the main concept of a scholarly text, try to look for additional information online. YouTube (e.g.,
<a href="https://www.youtube.com/c/K%C3%A1rolyZsolnai/featured">Two Minute Papers</a>), StackOverfow, Quora, and Medium are examples of webpages that can help you in analysing these sources of information.
</div>

:pencil:__2.2d__ Describe the procedure, and main objective of Turing's 'Imitation Game'. Write your answer down

***

### 3. GitHub Desktop: Introduction to version control 

Today, you will be introduced to the basics of version control, understand why it is useful and implement basic version control for a plain text document using GitHub Desktop.

 <img src="./images/GitHub.png" alt="GitHub logo" width="400"/>

*Figure 4. GitHub.*

#### 3.1 What is version control and why use it?

It is helpful to understand what version control is and why it might be useful for the work you are doing prior to getting stuck into the practicalities. At a basic level version control involves taking 'snapshots' of files at different stages. Many people will have introduced some sort of version control systems for files. Often this is done by saving different versions of the files. Something like this:

```
mydocument.txt
mydocumentversion2.txt
mydocumentwithrevision.txt
mydocumentfinal.txt
```

The system used for naming files may be more or less systematic. Adding dates makes it slightly easier to follow when changes were made:

```
mydocument2016-01-06.txt
mydocument2016-01-08.txt
```

Though this system might be slightly easier to follow, there are still problems with it. Primarily this system does not record or describe the changes that took place between these two saves. It is possible that some of these changes were small typo fixes but the changes could also have been a major re-write or re-structuring of a document. If you have a change of heart about some of these changes you also need to work out which date the changes were made in order to go back to a previous version.

Version control tries to address problems like these by implementing a systematic approach to recording and managing changes in files. At its simplest, version control involves taking 'snapshots' of your file at different stages. This snapshot records information about when the snapshot was made but also about what changes occurred between different snapshots. This allows you to 'rewind' your file to an older version. From this basic aim of version control a range of other possibilities are made available.

#### *Why version control text documents?*

As research increasingly makes use of digital tools and storage it becomes important to consider how to best manage our research data. This becomes especially important when we want to collaborate with other people. Though version control was originally designed for dealing with code there are many benefits to using it to with text documents too. Though not all of these benefits will be covered in this lesson, version controlling your document allows you to:

- Track developments and changes in your documents
- Record the changes you made to your document in a way that you will be able to understand later
- Experiment with different versions of a document while maintaining the original version
- 'Merge' two versions of a document and manage conflicts between versions
- Revert changes, moving 'backwards' through your history to previous versions of your document

Version control is particularly useful for facilitating collaboration. One of the original motivations behind version control systems was to allow different people to work on large projects together, in the case of Git to manage the Linux kernel source code. Using version control to collaborate allows for a greater deal of flexibility and control then many other solutions. As an example it would be possible for two people to work on a document at the same time and then merge these documents. If there were 'conflicts' between the two versions version control systems would allow you to see these conflicts and make an active decision about how to 'merge' these different versions into a new 'third' document. With this approach you would also retain a 'history' of the previous version should you wish to revert back to one of these later on.

Version control will not be necessary for all of the documents you write. However there are times when version control will be very useful. For substantial work such as articles, books, or dissertations, version control makes a lot of sense.

The implementation of version control we are going to use in this lesson will be publicly available, but it is possible to use version control and keep your documents hidden permanently or until you decide to make them available.

#### 3.2 What are Git and GitHub?

Though often used synonymously, Git and GitHub are two different things. Git is a particular implementation of version control originally designed by Linus Torvalds as a way of managing the Linux source code. [Other systems](https://en.wikipedia.org/wiki/Comparison_of_version_control_software) of version control exist though they are used less frequently. Git can be used to refer both to a particular approach taken to version control and the software underlying it.

GitHub is a company which hosts Git repositories (more on this below) and provides software for using Git. This includes 'GitHub Desktop' which will be covered in this tutorial. GitHub is currently the most popular host of open source projects by [number of projects and number of users](https://en.wikipedia.org/wiki/Comparison_of_source_code_hosting_facilities#Popularity).

In this lesson the focus will be on gaining an understanding of the basic aims and principles of version control by uploading and version controlling a plain text document. This lesson will not cover everything but will provide a starting point to using version control.

#### *Why not use Dropbox or Google Drive?*

Dropbox, Google Drive and other services offer some form of version control in their systems. There are times when this may be sufficient for your needs. However there are a number of advantages to using a version control system like Git:

- Language support: Git supports both text and programming languages. As research moves to include more digital techniques and tools it becomes increasingly important to have a way of managing and sharing both the 'traditional' outputs (e.g., journal articles, books, etc.) but also these newer outputs (e.g., code, datasets, etc.)
- More control: a proper version control systems gives you a much greater deal of control over how you manage changes in a document
- Useful history: using version control systems like Git will allow you to produce a history of your document in which different stages of the documents can be navigated easily both by yourself and by others

#### 3.3 Getting started

GitHub Desktop will allow us to easily start using version control. GitHub Desktop offers a Graphical User Interface (GUI) to use Git. A GUI allows users to interact with a program using a visual interface rather than relying on text commands. Though there are some potential advantages to using the command line version of Git in the long run, using a GUI can reduce the learning curve of using version control and Git. 

#### *A note on terminology*

One of the trickiest aspects of using GitHub is the new terminology. Some of the commands are fairly self-explanatory, others less so. This tutorial will try and briefly summarise new terms. It may also be helpful to have a [glossary](https://help.github.com/articles/github-glossary/) on hand to refer to. But in general it can be best to pick up terminology through using GitHub rather than trying to understand all of the terms before you begin using it.

#### *Register for a GitHub account*

Since we are going to be using GitHub we will need to register for an account at [GitHub](https://github.com/).

<div style="padding: 15px; border: 1px solid transparent; border-color: transparent; margin-bottom: 20px; border-radius: 4px; color: #8a6d3b;; background-color: #fcf8e3; border-color: #faebcc;">
Note: For details on creating a GitHub account and connecting it to your BUas block repository, see email with the subject: 'LMS Access and Github account Instructions'.    
</div>

![GitHub repository](./images/GitHubRepo.gif)

*Figure 5. GitHub ADS&AI student repositories.*

#### *Install GitHub Desktop*

[You can download GitHub Desktop here.](https://desktop.github.com/) Once you have downloaded the file, unzip it and open the app, following the instructions for logging in to your GitHub account. Once you have installed GitHub Desktop and followed the setup instructions we can start using the software with a text document.

#### 3.4 Version controlling a plain text document

Version control systems like Git work best with plain text files. Plain text files are files with minimal encoding, whereas word and other word processors produce a lot of code that is not human readable. The same text saved in a '.txt' file opens equally well in Word, LibreOffice or Notepad. This 'portability' of plain text files is a major benefit: they will open and display the text properly on almost any computer.

Although there are many benefits to writing our documents in plain text files we quickly come across some limitations. We may want to emphasise parts of text with *italics* or with **bold** words. We may want to include headings or include quotations. This is where 'markdown' comes in.

Markdown is a way of including formatting into a plain text document. You may have come across HTML or LaTeX in the past. These markup languages also express information about the formatting and structure of plain text. Markdown, however, tries to minimize the syntax. This makes it easier to focus on the content of writing without the markup getting in the way---hence the name 'markdown.'

GitHub integrates its own version of Markdown syntax. If you add Markdown syntax to documents you version control with GitHub Desktop these will be rendered on the GitHub website. Arguably the best way to learn Markdown is to begin using it. 

#### *Text editors*

To write in plain text we want to use a text editor. There are a huge number of free and paid text editors available. Some of these are very straightforward and simple to use while others have a learning curve and potential uses beyond simple text editing. In the long run using a more advanced and extendable text editor may save you time, but for now we can start with a more user-friendly editor. [Visual Studio Code](https://code.visualstudio.com/) is a good option for getting started. Visual Studio Code is a text editor built by Microsoft and includes syntax highlighting for Markdown alongside integration with GitHub. It is free and open source, a manual, including installation instructions, is available [here](https://code.visualstudio.com/docs).

#### *Creating a document*

We can begin with a very simple document.

```
Hello world!
```

You can include the above text or something similar in a new plain text document. Once you have done this you can save the file with a file extension '.md'. This is the most popular file extension used for markdown files though others are sometimes used. Make sure that it is saved in plain text format in a new folder. Sometimes your text editor will default to Rich Text Format. You should be able to change this in the preferences or options of your chosen text editor. Make sure to name the file and folder with something meaningful. This may seem slightly confusing. The '.md' file extension lets GitHub (and other software) know that we are using markdown syntax. However, we still want to ensure that the encoding of the file is in 'plain text'. Once you are setup with a text editor you like then the encoding of documents will not usually be an issue.

To most effectively use Git to version control it is important to organize projects in folders. Git tracks the contents of a folder by creating a **repository** in the folder. The repository is made up of all the files in the folder that are 'watched' for changes by Git. It is best to create one repository for each major project you are working on, i.e., one repository for an article, one for a book, and one for some code you are developing. These folders are like the normal folders you would have on your computer for different projects, though the files in the folders have to be deliberately added to the repository in order to be version controlled.

#### *Adding a document to a new or existing repository on GitHub*

There are a number of different ways to **add** files for GitHub Desktop to track. We can drag the folder containing the file onto GitHub Desktop. When you do this you will be asked whether you want to create a repository for this folder. Alternatively we can click on the 'plus' icon to open a finder window to choose folders we want to add.

![GitHub add and clone](./images/GitHubAddClone.gif)

*Figure 6. GitHub add folder.*

You can also add files to an existing repository on GitHub.com. Before you can add a new file, you need to clone the repository to your local device. Cloning a repository pulls down a full copy of all the repository data that GitHub.com has at that point in time, including all versions of every file and folder for the project.

To clone a repository, open GitHub.com, and navigate to the main page of the repository. Above the list of files, click on the downward pointing arrow to 'Open with GitHub Desktop' ([Source](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)). 

![GitHub clone](./images/GitHubCloneOnline.gif)

*Figure 7. GitHub add folder.*

Once we have added our folder or existing repository from GitHub.com we will be able to see it in a list of repositories on the left column.

If we choose the repository we just added we will see the files contained in that repository. From this menu we can choose which files we want to version control. (There might be times when we are working on projects in which files are produced which we do not need or want to version control.) On the right we will see the current document.

If we show hidden folders in the folder, you will see that the folder contains an extra folder with the name '.git'. This folder is how GitHub desktop tracks changes we make within our version controlled folder whether these changes be adding new files or modifying existing ones.

We can go back to the document in our text editor and add something new. For example:

```
Hello world!
a second line
```

You can save the changes to your file and go back to GitHub Desktop. You will then see that these new lines of text appear. This lets us know that GitHub is able to see changes in your file but at the moment these changes have not been recorded in an official 'snapshot' of your repository.

To do this we need to **commit** our changes.

#### *Committing changes*

A **commit** tells Git that you made some changes which you want to record. Though a **commit** seems similar to saving a file, there are different aims behind 'committing' changes compared to saving changes. Though people sometimes save different versions of a document, often you are saving a document merely to record the version as it is when it is saved. Saving the document means you can close the file and return to it in the same state later on. **Commits**, however, take a snapshot of the file at that point and allow you to document information about the changes made to the document.

![GitHub commit](./images/GitHubCommit.gif)

*Figure 8. GitHub commit.*

To commit changes you must give a summary of the changes and include an optional message. It is important that you think carefully about when to make commits. The advantages of version control taking snapshots of your changes regularly relies on you making commits. It is often tempting to just commit changes when you have finished working on a document but this might not reflect when important changes occurred.

When you commit you will see 'commit to master'. This refers to the 'master branch'. Within a Git repository it is possible to have multiple 'branches.' These different branches are essentially different places in which to work. Often they are used to test new ideas or work on a particular feature. Initially it is not necessary to use the branches feature of GitHub, but you may want to learn to use it in the future, particularly if you want to use GitHub to collaborate on a repository with other people.

A useful way to think about commits is as the 'history' of your document. Each commit records a development or change made to the documents in your repository; the history of the document can be traced by looking at all of the commits. For this history to be useful later on, either for ourselves or for someone else, it is important that this history is recorded at relevant points. Trying to make commits 'atomic' is an important consideration. What this means is that each commit 'makes sense' on its own. The changes in the commit and the message are understandable without having to look at surrounding commits.

Thinking about how version control is used for code can make this idea more clear. When a new feature, or a bug fix, is added to some software it is important that these features can be isolated. If a commit includes changes to different aspects of the code it makes it hard to isolate when problems were introduced. It is also makes it difficult to remove a single change that is causing problems if other changes are included in the commit.

There are differences between using version control for code and text which will impact on how you make commits. However, the aim of making commits 'atomic' can still be used. For example, it would make sense to commit changes to the structure of a document separately to grammar and spelling fixes. If you later decided to change the structure you would likely still want to maintain your other fixes.

#### *Commit messages*

It is important that you use meaningful commit summaries and messages. Writing good commit messages requires some prior thought. Messages that make sense to you as an explanation of changes when you make a commit may no longer make sense to you in the future. If you are going to use version control in collaboration with other people it is especially important that other people can understand your commit messages. Version control as a system for managing changes to documents works best when active thought goes into using the software. It is therefore particularly important when collaborating with other that there is a shared understanding and approach to using version control.

One way of addressing this is to try to follow a 'commit style'. One influential [suggestion](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html) for a commit style has been made by Tim Pope. The style suggestions made by Tim Pope are partly ['built in'](https://github.com/blog/926-shiny-new-commit-styles) to the GitHub Desktop commit message interface but understanding the format will help ensure a consistent approach. The following commit message paraphrases Tim Pope's suggested format to focus on commits relating to text rather than code:

```
Capitalized, short (50 chars or less) summary

More detailed explanatory text, if necessary. In some contexts, the first line is treated as the subject of an email and the rest of the text as the body.

Write your commit message in the present tense: "Fix typos" and not "Fixed
typos."  This convention matches with other aspects Git commands.

Further paragraphs come after blank lines.

- Bullet points are okay, too

- Typically a hyphen or asterisk is used for the bullet, preceded by a
  single space, with blank lines in between, but conventions vary here
```

The GitHub Desktop interface takes care of some of these 'style' issues but it is good to be conscious about how you write commit messages. It will not always be necessary to write an extensive commit message but is important that the message is clear about the changes being made and that the commits and the commit message are useful 'atomically'.

An example of a short but clear commit message in the context of written work:

```
Reorder document outline

Move the methods section below the sources section in the document outline.
Why? Some of the methods discussion doesn't make sense without a description
of the sources being used.
```

A potentially useful parallel to writing good commit messages is the messages included when you edit a Wikipedia or Wiki page. When writing these messages it is important to explain the changes you made to the page and the reasoning behind these changes so that other people who see the changes can understand your reasoning. Approaching commit messages as if they will be read not only by yourself but also by others will help you write clear and meaningful commit messages.

#### *Publishing your repository*

At the moment we are only recording our changes locally. We may be happy to only store our changes locally (it is still important to back our files up) but we may want to upload our repository onto GitHub to make it public or to have it stored outside of our computer. The process of doing this through GitHub Desktop is straightforward. On GitHub desktop you 'publish' repositories. This will **push** your repository from your computer to the GitHub website and set up a **remote** repository in the process.

![GitHub push](./images/GitHubPush.gif)

*Figure 9. GitHub push.*

Once you have 'published' your repository it will be viewable on your profile at GitHub's website. To quickly view your repository online you can use the repository menu and choose 'View on GitHub'. This will bring you to your repository online in your browser.

![View repository on GitHub.com](./images/GitHubViewOnGitHub.gif)

*Figure 10. View repository on GitHub.*

You can now see your document in your online repository.

Once your document is online, you can continue to make local changes to your file. But you will have to syncronise your local changes to reflect these changes in the published GitHub repository. GitHub stores changes both locally (on your computer) and remotely (on their servers). It is important to keep these changes in sync. On GitHub Desktop this process is simplified by using the **push** and **pull** button on GitHub Desktop. This will ensure your local (computer) and remote (GitHub server) repositories are the same. If you want to work on your document before 'publishing it' you can choose to make commits without syncing. This will allow you to implement version control early on whilst keeping the changes local to your computer initially.

#### *Making changes remotely*

It is also possible to make a change to your repository on the web interface. Clicking on the name of the file will take you to a new page showing your document.

![View file on GitHub.com](./images/GitHubViewDocumentOnline.gif)

*Figure 11. View document on GitHub.*

From the web interface you have a variety of options available to you, including viewing the history of changes, viewing the file in GitHub Desktop, and deleting it. You can also see some other options next to 'code'. These options will not be so important to begin with but you may want to use them in the future. For now we will try editing a file in the web interface and syncing these changes to our local repository.

Click on the edit option. You will now be able to edit the file and add some new text.

![Edit file on GitHub.com](./images/GitHubEditFile.gif)

*Figure 12. Edit file on GitHub.*

Once you have made some changes to your file, you will again see the option to commit changes at the bottom of the text entry box.

![Edit file on GitHub.com](./images/GitHubCommitOnline.gif)

*Figure 13. Commit file on GitHub.*

Once you have committed these changes they will be stored on the remote repository. To get them back onto our computer we need to sync our these changes. We will see the 'pull' button on GitHub Desktop. 

![GitHub pull](./images/GitHubSync.gif)

*Figure 14. GitHub pull.*

We now have our remote changes synced back onto our computer.

You can see from this view that text with changes highlighted in green or red. Red indicates where things have been removed while green indicates additions. This can be useful for viewing the edits you have made before making a commit and helps you spot whether all the changes are ones you want to commit. On the left you will see a history of the changes you have made. At the moment this is very brief but as you work on a project the history might become much longer. Being able to see the changes you have made at different stages can be very useful.

__3.4a__ Install [GitHub Desktop](https://desktop.github.com/), and  [VSCode](https://code.visualstudio.com/) or another IDE/text editor on your local device. 

Let us start creating a markdown file that we will use to store our answer to exercise 2.1c, where you had to find, and describe one 'milestone' in the history of AI.

:pencil:__3.4b__ Create a markdown file (i.e., text file with extension '.md'), include the answer to exercise 2.1c, and save it to your local device (e.g., laptop) with the name [__YourName_GitHubExercise__]. Commit the changes, and push the markdown file to your personal BUas Block A repository.

For instructions on how to create a markdown file in VSCode, see the video below:

<iframe width="896" height="504" src="https://www.youtube-nocookie.com/embed/DLLrcr9u_XI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

*Video 2. How To Write and Preview Markdown In VScode.*

Material in this section has been adapted from [Getting Started With GitHub Desktop](https://programminghistorian.org/en/lessons/retired/getting-started-with-github-desktop) is licensed under CC BY 4.0. 

<div style="padding: 15px; border: 1px solid transparent; border-color: transparent; margin-bottom: 20px; border-radius: 4px; color: #8a6d3b;; background-color: #fcf8e3; border-color: #faebcc;">
Note: When you are finished with the independent study material, and still have some time left, try to apply your newly gained knowledge to the DataLab tasks.
</div>

***