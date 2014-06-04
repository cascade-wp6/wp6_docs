# Version control


We intend to implement the consequent utilisation of version control tools such as [git](https://git-scm.com/) or *subversion*. These little pieces of software keep a register of the files you are working on and track all changes. At the cost of very little extra effort in your everyday workflow, this brings the following benefits:

- 	**clean working directory**: well, you might already do your manual versioning by keeping a collection of files in your working directory that reads something like this:

      simulation.cpp
      simulation_v0.1.cpp
      simulation_v0.2.cpp
      simulation_v0.2.1.cpp
      simulation_in_review.cpp
      simulation_messed_up.cpp

	You also might have several copies of the code file in differently named directories. You might have made some little changes to the file in each of them. This clutters your project's working directory. Version control makes this redundand since the software keeps track of your work now. It allows you to make changes to your main code file and return to a previous version anytime you want. You even can keep several branches of that single code file. Still, there is only one file found in your working directory called `simulation.cpp`.
- 	**code safety and progressive development:** Certainly it happened to you that you helplessly messed up a previously running version of your piece of code. An accidentally overwritten file could even compromise the supposedly secured copies on your cloud storage or backup drive. With version control, if some development did not work out, you will always be able to go back to the last running version and start afresh. While doing so, you even could choose to keep those parts of your unsuccessful exploation that were actually not so bad. This saves a lot of frustration and makes the code development more progressive, conserving the good parts of your development while beeing able to undo the bad ideas.
- 	**project progress documentation:** Since version control does not only track the main code file, but also your result files, generated figures and manuscript files, if you let it do so, the timeline of changes is a perfect documentation of the projects progress. Additional information can be added by setting tags to certain versions of the project or by complementing the code with a documentation file, itself versioned as part of the project.
- 	**backing up:** The nature of version control tools like git allows to clone backup copies of the whole project directory to a remote server, a cloud storage or a usb drive. The perfect protection against technical problems on your main computer. Just clone your work.
- 	**collaboration and file syncing**: This feature also can be used to sync your files between your own computers or share them with colleaques for collaboration or review. It allows you to keep track of the changes made by each of the involved collaborators and reviewers.
- 	**publishing**: Whenever your project is fit for going public you can easily clone your whole work, including the development history, into a public hosting service, such as [GitHub](https://github.com). Here, everybody could review your code or manuscript before final submission or after the project is published. With a little work you can set up a semi-public repository on an own server with access management.



## git

First a few words in general about what *git* actually is and what it can do. I see two main purposes of it:

-	The very first purpose is **version control** of a project. This can be a piece of software or a written document, for example. As a developer or author you might want to keep track of your progress. Maybe you want to go back to earlier versions, because you somehow messed it up, or just because you liked it better. This ensures a continuous improvement of your project.

-	The second purpose is **collaboration**. Git allows you to share the whole project with others. It does track, who was doing changes on the project's files and is able to merge things together if the collaborators were working on different parts of the projects.

- If you think about it, this is also exactly the thing you need if you are working from different computers, e.g. from work and from home. So we can add **synchronisation** to that list.

*git* also helps with building up an organisational structure for complex software development. It is easy to work on different parts of the project at the same time and merge those so-called branches together afterwards.

### Install

If you have a [GitHub](https://www.github.com) account, [GitHub for Windows](http://windows.github.com/) or [GitHub for Mac](https://mac.github.com/) are clean and convenient tools to use. It installs a command line shell that includes all the utility that is required for *git* and the connectivity to GitHub. However, the actual GUI is not very flexible and uses a completely different vocabulary (syncing, updating) than the actual git. Alternatives are [git for windows](https://msysgit.github.io/). Many IDEs for code development come with a convenient git interface (e.g. RStudio, Eclipse).

In Ubuntu, *git* can be installed via

    apt-get update
    apt-get install git

Then you should [set your user properties](http://git-scm.com/book/en/Getting-Started-First-Time-Git-Setup).

	git config --global user.name "Your name"
	git config --global user.email your@email.com
	git config --global core.editor gedit

This just tells git under which name commits should be performed and which texteditor to use for requiring messages.

### use it

The principles of *git* are explained [on](https://try.github.io/) the [internet](http://think-like-a-git.net/) at [length](http://git-scm.com/book) and [short](https://rogerdudler.github.io/git-guide/), and it is worth looking into it, even if some clients make it a point-and-click adventure.

I only want to point out that *git* can be used on your local computer in any directory you like to put under version control. If no collaboration or syncing is necessary the commands `git add` and `git commit` are all you need. Maybe you will want to set a `.gitignore` file that excludes some directories or files from being tracked.

If you want to sync your versions to a remote server (e.g. to GitHub) for personal back-ups or to share it with others, you will need `git pull` and `git push`.

If a linear workflow is not sufficient and you want to apply more elaborate procedures such as *branching* and  you will  need to understand `git branch`, `git remote`, `git merge`, and more.

Useful are *tags* that can be set at any point in the project development that seems noteworthy (for instance the start of a simulation, sending the code to a collaborator, the submission of a manuscript) using `git tag`.

## GitHub

In the first place, GitHub is a webserver for Open Source projects. It stores, visualises and helps to manage projects that develop some kind of computer code. Of course everything on GitHub is under *git* version control.

To participate actively in the code development in WP6 [you will need a GitHub account](https://github.com/), which is completely free (no adds, no personal data trade).

Then, you should join the CASCADE WP6 team at [github.com/cascade-wp6](https://github.com/cascade-wp6) which gives you access to the private repositories. Now, you also can

- create your own (private or public) repositories and push your own projects to GitHub.
- invite other partners within CASCADE or attached to CASCADE to participate in your project.
- comment on other projects going on within CASCADE and get the code.

GitHub provides a couple of features for [project management](opensource.md)(Milestones and issue tracking) and [documentation](documentation.md) (Wikis and Version history).

[Learn more about it.](https://help.github.com/)
