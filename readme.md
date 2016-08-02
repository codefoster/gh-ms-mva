# Course Title: GitHub for Windows Users
## Module 1: Basic Concepts and the GitHub Workflow (50 mins)

#### Background & introductions

- Introductions of presenters
- Background on version control and rise in popularity of git and GitHub
- GitHub has more than 14 million users, 35 million repositories
- Open source community on GitHub unites developers

#### Microsoft & GitHub

- Collaboration reaches beyond development environment and operating system
- GitHub integrations with Microsoft: GitHub Desktop, other Microsoft friendly UIs
- Microsoft recently introduced Git into TFS - a good reason to learn Git
- Microsoft hosts all open source projects on GitHub
- https://github.com/Microsoft / https://microsoft.github.io/

#### the difference between central and distributed models

- Every developer has the entire project at all times, including history
- Internet connection not needed
- <Images of remote!>
- Remote repository somewhere, we have it on GitHub

#### The distinction between git and GitHub

- GitHub built on top of Git
- GitHub is for collaboration
- GitHub employees work to maintain Git (open source)
- Git handles the version controlling, GitHub provides the UI and social aspects
- Understandably blurry line - you can perform functions of each in so many different ways

#### GitHub Workflow

- Show workflow guide images
- Talk through process of sharing repository, branching is cheap and fast
- Overview of what issues, PRs are and when to use them
- Commits are easy to search and diff and lightweight, just series of pointers
- Time to turn around on a change - reference Stefan's CI/CD slides (slide 3, 4, 9): https://github.box.com/s/qg0nwyagsv72dmnfb5bqqo8ywprp8avf

#### GitHub and Open Source

- Talk about a few really neat open source projects (Detroit Water Project)
- GitHub isn't just about your own workflow, it's about finding a cool project and contributing
- Microsoft hosts all of its open source projects on GitHub

## Module 2: GitHub in the Browser

#### creating repos

- What is a repository
- How to create a repo
- .gitignore conversation
- README.md conversation
- Licensing conversation

#### using organizations

- Using user vs organization to create a repository
- Org: can be used for open source projects, more permissions for other contributors
- You can have teams on orgs

#### adding contributors

- Lets others push (make changes) to the remote repository
- Demo process, add Jeremy
- Simple, flat permission structure: You're either a collaborator or you aren't
- When you'd want to add contributors vs. when you'd encourage a fork & pull model

#### Issues for collaboration

- Demo making an issue, discuss purposes
  - Replace email
  - at mentioning - mention Jeremy
  - Markdown
  - conversations
  - bug fix requests
  - Planning

#### basic text editing

- Demo creating a branch, reference the workflow heavily
- Create a file, show text editing on UI
- Commit to branch on web

#### pull requests

- Create PR, at mention Jeremy
- Have Jeremy help with collaboration process
- Show workflow again

## Module 3: GitHub Desktop
All the details on installing and using Desktop, launching it from the browser, etc.

## Module 4: GitHub Integrations with Visual Studio
The relative ease of simply doing source control from your IDE. We would show Visual Studio as well as Visual Studio Code.
- Visual Studio 2015
  - Developer Assistant
  - Visual Studio Tools for Git
  - GitHub Extension for Visual Studio
    - Installation
    - Creating a repo
    - A common scenario: a fork, a mod, and a PR
- Visual Studio Code


## Module 5: GitHub on the Command Line

#### Installing Git from command line

- Are they OK showing Git Bash shell?
- We recommend using Git Bash because the commands will match other development environments - this works best on Windows 10 due to Bash integration
- Consistency in solving problems using resources like stackoverflow, etc.
- Download Git from git-scm then launch git bash
- http://www.pcworld.com/article/3050473/windows/heres-how-windows-10s-ubuntu-based-bash-shell-will-actually-work.html

#### git configs

- Demo seeing configs
- Show image of levels of configurations
- Demo setting some configs

#### git clone - working locally

- Distinguish between `git init` and `git clone`
- Demo both
- Clone example - use repo from earlier
- For init - do something new

#### Workflow

- Show workflow again, discuss which commands go to where
- Show git cheatsheet
- git clone
- git branch
- git add
- git commit
- git status
- git push

#### Danger Zone: Changing History

- Git can be scary - but it's actually safe once you know some simple commands
- `git revert`
- Watch out for anything that changes a commit ID
  - cherry-pick
  - rebase
  - reset
  - commit amend
- `git reflog`  

"The command line is the only place you can run all Git commands -- most of the GUIs only implement some subset of Git functionality for simplicity. If you know how to run the CLI version, you can probably figure out how to run the GUI, while the opposite is not necessarily true." - Scott Chacon, Pro Git


## Module 6: Beyond the Basics
This would be a grab bag of more in-depth or advanced  concepts. Here we talk about pull requests, submodules, continuous deployment from GH to Azure, perhaps rebasing, cherry picking, stashing, etc. (that may be too much)
