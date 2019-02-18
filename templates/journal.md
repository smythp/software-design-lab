# $Sabina's Technical Journal

## Week Two (1/30 to 2/6)

The first week, I did most of the DHRI Command Line tutorial up to and not including Pipes. I spent an inexplicably long time trying to clone software-lab tutorial from Patrick's repository, then forked it to my repository and tried to clone it from there, to no avail. I still don't know why I didn't manage to clone software-lab. I followed the steps carefully again and again. Happily, I was able to clone software-lab in class on the second week with Antonio's help but by typing what I think were the exact same commands. 

Hour 1: DHRI Command Line tutorial

Hour 2: Tried to clone software-lab repository in terminal, unsuccessfully. Read and followed lots of instructions from various sources

Hour 3: DHRI Command Line tutorial. 

Hour 4: Tried to clone software-lab repository in terminal again. Downloaded newest version of Visual Studio Code. Forked software-lab to my Github account, thinking that maybe I would be able to clone it to terminal from there. Tried to clone my forked copy of software-lab to terminal. Unsuccessful

Hour 5: DHRI Command Line tutorial. Lost files I had created in terminal by deleting them in Desktop from the front end. Got rather confused and decided to stay away from the front end.

Hour 6: Tried to clone software-lab repository in terminal again. Got really frustrated. Decided to ask someone for help on Tuesday.

Hour 7: Set out to finish the DHRI Command Line tutorial but my brain was sluggish and dull and I kept going over the same exercises and getting them wrong, so I stopped.

Note: I'm trying to commit this journal to GitHub. I'm a little confused. 

## Week Three (2/7 to 2/13)

Doing the GCDI Git tutorial, I was nonplussed by observing that when I typed git config –list, instead of seeing my git user name and user email, I saw a huge list of really interesting looking stuff, such as core.legacyheaders=false and color.interactive=auto. Instead of the $ there was a : and I couldn’t type cd ~ to get back to the beginning. I hit return and more strange words and symbols appeared. I hit return again, and more, and more and so on, until I saw, at the bottom of that great list, my user name, user email and (END). Yay. How cool is that. I have tons of stuff. However, I can’t get back to where I can type commands. I decide to close terminal and hope that when I open it again I can start fresh. Yeah. That worked. As I work through the tutorial I do things that we did in class last Tuesday. This is great because it reinforces what I learned (and partially forgot). I have to stop myself from speedreading the tutorial; I have the impulse to say oh yeah I know that, we did that, and miss key steps. I have to plod along and do everything. It’s therapeutic. I have to keep it easy and simple. There’s no hurry. The important thing is that I sit here for three hours doing stuff. I discovered common exit commands to return to $ prompt. 

Hour 1: DHRI Git tutorial

Hour 2: DHRI Git tutorial and tried to add journal.md to GitHub

Hour 3: continued to try to push journal.md to GitHub and succeeded. Updated goals.md. 

Hour 4: Command line crash course from Learn Python the Hard Way. I had started Learn Python the Hard Way, and in lesson 0 Zed Shaw told me to do his command line crash course before going any further. Although I had done more than half of the DHRI command line tutorial (up to Pipes), I thought it best to do Zed Shaw's command line crash course from beginning to end too. 

Hour 5: Command line crash course from Learn Python the Hard Way

Hour 6: Command line crash course from Learn Python the Hard Way

Hour 7: Learn Python the Hard Way, lessons 1-3 

Hour 8: Learn Python the Hard Way, lessons 4-5

Hour 9: Learn Python the Hard Way, lesson 6

## Week 4 (2/14 to 2/20)

One of the things I have to do this week is tidy up my directories. I have two projects directories; one is in Desktop and the other is somewhere else. Both have files in them, but not the same files. I'm going to move and then remove files, but I'll do this tonight or tomorrow. 

Hour 1: modified goals and journal, and pushed both to the repository. Explained to one of my classmates how to modify files in code and then push modified files to a repository. Googled how to move files from one directory to another. Tried to do it. It didn't work.

Hour 2: did exercise six in Learn Python 3 the Hard Way. I had done Exercise 6 in Learn Python 2 the Hard Way but making strings and variables in Python 3 following instructions from the Python 2 book hadn't worked. With the Python 3 book it was easy peasy. Then I decided to give moving files between directories another try. I consulted Zed Shaw's command line crash course. I'm confused because moving files isn't really moving them, it's renaming them. I have to ask Patrick about this. Because moving was confusing, I copied instead. I copied a bunch of files from Users/sabinapringle to Users/sabinapringle/projects/ and then removed the files in Users/sabinapringle. I know there has to be a better way. I want to move stuff, not copy stuff or rename stuff. And I want to move a bunch of files at once. I know I can use wildcards but when I tried it didn't work. I can copy files but I don't think I know how to copy directories. I could figure all this stuff out but I think this time I might ask a digital fellow for help, because I prefer to move on with the exercises in Learn Python the Hard Way.

Hour 3: wow I did something really weird and got kind of stuck in the middle of committing my journal. I couldn't figure out how to get back to the $ sign (exit commands I know didn't work) so I closed Terminal. When I went back in I tried to commit again and I got a scary error message telling me that there was a process running and I had to remove a swap - I think it was swap - file.
The thing I had to do was vim -r /Users/sabinapringle/Desktop/projects/software-design-lab/.git/COMMIT_EDITMSG 