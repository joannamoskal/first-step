
# What is Git?
Here's a kind of the recap what I've learnt during our lesson.

The lesson was about [[Git]].

## Definition
Git is a kind of tool, software which is a distributed version control system [[VCS]] that tracks changes in any set of computer files.

## Installation
Firstly, I had to install this software on my computer. To do that I opened google browser and I found the Git website https://git-scm.com/downloads from where I could download it. It is available for free. I chose the latest version and the downloading started automatically.

## Creating a new repository
Then I got to know that this system uses commands, and that Git VCS allows me to create repositories. Each [[repository]] is a kind of library where all my file changes will be stored. 

First, I made a folder (= directory) on my "D" disc partition. I called it "GIT". Next I found out that there is a website https://git-scm.com/docs where I can find references on how to do what I want to do when it comes to Git VCS. I found a command which allows me to create a new, empty repository.

I noticed that this command will allow me also to reinitialize an existing repository.
  
This command is: 

*git init*

[[git init]]

So I wrote it down and I copied the link address of my folder which is D:\Git (it is a path to my repositories) and I clicked the enter key on my keyboard to run this command. It allowed me to create a new repository in a GIT folder. Then I opened it and clicked "view" and I marked hidden elements and I found out that in this directory there is a hidden element which is called  .git. As it is the same name as my repository, I created another repository which I called: ABC. 

All of those things I was doing on my computer were also practicing via the game on the table which was prepared by my brother. We used some cards, papers and a felt tip pen for this game. It was just a representation of what we did on the computer and it was very useful. It helped me better imagine and understand what we were talking about.

After creating the ABC repository I tried to make something in my repository, in other words I simply made a file. I chose the text document which has an extension: .txt.

Because of the fact that I have my repository in a different place than when I installed Git I always  have to change the directory via using a command: 

*cd /D* 

- it allows me to change the directory. In my case it is the D disc partition and then I wrote down a command: 

*D:\ABC*

and it led me to the proper place. So the whole command is:

*cd /d D:\ABC*

Now I could create a file which was a text document. So I created a file in the notepad and I named it bla.txt and saved it in my repository directory. 

Then I used a command: 

*git add bla.txt* 

which allowed me to track my chosen file via Git VCS. 

## Commands: 

*git add* 
[[git add ]]
updates the current content found in the working tree and gives me an opportunity to prepare the content for the next commit.  

I also used another command which was

*git status*
[[git status]]

It always shows how my files are changed or what is their current status. After I wrote some text in my file and I wrote command: git status, the Git VCS knows that I changed something in my previous version of this file.I added some text in my txt. file so I could see that there were some changes to be committed. But before doing it I had to write so -called the git commit message for my changes. To do that I had to write another command which is:

*git commit -m*
[[git commit -m]]

and the title of the message in the quotation marks, for example:

*git commit -m “wers pierwszy”*

The first commit is sometimes called “root”

Now I could send my changes to [[Github]] which is an Internet hosting service for software development and version control using Git.

Because I already had an account on this website it was easier for me. Otherwise I would have to create one first.

Then I had to create a repository on Github, so I did it. I named it “first step”. 

Then I created new branch named “main” by using a command:

*git branch -M main*
[[git branch]]
then

*git remote add origin https://github.com/joannamoskal/first-step.git

[[git remote]]
I did another change in my file. Then I committed it and pushed to my remote repository on Github via using bellowed command:

*git push* 

and the URL address of my branch in my repository. I found this address when I clicked on “Code” and there is the URL address to my repository. The whole command I wrote was:

git push [https://github.com/joannamoskal/first-step.git](https://github.com/joannamoskal/first-step.git)

  

Now I see that on my Github account, there is a new repository called first step  with one branch named main and in this branch I have 2 commits, because I made two changes in my file and I pushed them to this place.

From now on every change I make in my text file named bla.txt I have to push to Github.

There is also another hotkey which is worth to know:

*:q*

It allows you to change windows in GIT.

There is also other command which I heard about during my first lesson:

*git log*

this command shows the name of the commit which is automatically added - it is usually a long combination of letters and numbers, the author and the date of the change.

*git branch -m old-name new-name

it allows me to change the name of the current branch

**
**

