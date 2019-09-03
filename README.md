# Git Lab

*Not to be confused with [GitLab](https://gitlab.uah.edu/)*

---

## What is Git?

[Git](https://git-scm.com/) is a [Distributed Version Control System](https://en.wikipedia.org/wiki/Distributed_version_control) 
(DVCS) created by Linus Torvalds during his work on the `linux` kernel. It allows developers to track their changes, work 
collaboratively, and even tag special versions of the codebase for release. Git is by and far the most widely used version 
in the software development world (though in companies spanning multiple decades, you may still encounter 
[Subversion](https://en.wikipedia.org/wiki/Apache_Subversion), a 
[Concurrent Versions System](https://en.wikipedia.org/wiki/Concurrent_Versions_System)).

Git's central unit is a `repository`, or collection of similar files in a folder structure. A repository is updated via `commits`, 
which are simply lists of additions, subtractions, and changes to files in the repository's last commit. Git repositories can have 
`branches`, which allow multiple versions of the code to exist at one time. Branches can also be merged into other branches, or 
deleted. A request to merge one branch onto another is called a `Pull Request`. Sometimes, PRs have conflicts, and conflicts can be 
resolved by manually editing the files, using an IDE, or a web client like `GitHub`, `GitLab`, `Gitea`, or `BitBucket`, all of which 
are git servers used in the industry.

Git can be installed from the [official website](https://git-scm.com/downloads). It can also be installed through a package manager 
like `apt` (debian), `brew` (MacOS), or `chocolatey` (Windows). There are also GUI Clients like [`GitHub Desktop`](https://desktop.github.com/) 
and [`GitKraken`](https://www.gitkraken.com/). Many editors, like `PyCharm`, `Visual Studio Code`, `vim`, `XCode`, and `Visual Studio` 
also have git functionality built in or installable via well-maintained community plugins.

## Performing this lab

To do this lab, install git on your system and clone this repository. Next, create a repository locally or in a hosted service. Finally, 
copy the contents of the first folder into your repository (so that `README.md` is in the root of the directory) and follow the instructions 
in the `README.md` file.  