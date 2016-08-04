# Course Title: GitHub for Windows Users
## Module 1: Basic Concepts and the GitHub Workflow (50 mins)

#### Microsoft & GitHub

- Introductions of presenters (PP)
- Background on version control and rise in popularity of git and GitHub (PP)
- GitHub has more than 14 million users, 35 million repositories (Browser) 
- Open source community on GitHub unites developers (B)
- GitHub is for more than just code (show wedding planning) (B)
- Collaboration reaches beyond development environment and operating system (PP)
- GitHub integrations with Microsoft: GitHub Desktop, other Microsoft friendly UIs (PP)

#### The difference between central and distributed models

- Every developer has the entire project at all times, including history (PP)
- Internet connection not needed (P)
- Snapshots vs. Deltas (P)
- Remote repository somewhere, we have it on GitHub (P)

#### The distinction between git and GitHub

- GitHub built on top of Git (pp)
- GitHub is for collaboration
- GitHub employees work to maintain Git (open source)
- Git handles the version controlling, GitHub provides the UI and social aspects
- Understandably blurry line - you can perform functions of each in so many different ways
- What is specifically GitHub, and NOT Git?
  - Issues
  - Pull Requests
  - Orgs & teams
  - Code review UI
  - Many Integrations like Heroku or Travis CI
  
#### GitHub Workflow

- Show workflow guide images (browser) 
- Talk through process of sharing repository, branching is cheap and fast
- Overview of what issues, PRs are and when to use them
- Commits are easy to search and diff and lightweight, just series of pointers
- Time to turn around on a change - Not a year, not a month, but continuous 

#### GitHub and Open Source

- Talk about a few really neat open source projects (Detroit Water Project)
- GitHub isn't just about your own workflow, it's about finding a cool project and contributing
- Microsoft hosts all of its open source projects on GitHub 
- https://github.com/Microsoft / https://microsoft.github.io/

## Module 2: GitHub in the Browser

#### creating repos

- What is a repository (browser demo) 
- How to create a repo
- .gitignore conversation
- README.md conversation
- Licensing conversation (http://choosealicense.com/no-license/) 

#### using organizations

- Using user vs organization to create a repository (pp) 
- Org: can be used for open source projects, more permissions for other contributors
- You can have teams on orgs

#### adding contributors

- Lets others push (make changes) to the remote repository (browser) 
- Demo process, add Jeremy
- Simple, flat permission structure: You're either a collaborator or you aren't
- When you'd want to add contributors vs. when you'd encourage a fork & pull model

#### Issues for collaboration

- Demo making an issue, discuss purposes (browser) 
  - Replace email
  - at mentioning - mention Jeremy
  - Markdown
  - conversations
  - bug fix requests
  - Planning

#### basic text editing (Browser) 

- Demo creating a branch, reference the workflow heavily
- Create a file, show text editing on UI
- Commit to branch on web

#### pull requests (browser) 

- Create PR, at mention Jeremy
- Fork & pull vs. GitHub flow
- Have Jeremy help with collaboration process - https://github.com/Microsoft/vscode/pulse
- Show workflow again

## Module 3: GitHub Desktop

#### Introducing GitHub Desktop

#### Repositories

#### Branching and Changes

#### Other Desktop Tools
- Tortoise Git
- SourceTree
- Git Extensions
- SmartGit
- git-cola
- GitEye
- Git Kraken

## Module 4: GitHub Integrations with Visual Studio
#### Bing Developer Assistant
#### GitHub Extension for Visual Studio
#### Visual Studio Code
- Changes
- Diffs
  - side-by-side and inline
  - stage selected lines
- Push, pull, and sync
- Branches
- Git Output
- Extensions

#### Visual Studio Extensions
- Annotator
- Git History
- Share Code
- Open in GitHub
- Partial Diff
- gitignore

## Module 5: GitHub on the Command Line

#### Installing Git from command line (browser) 

- We recommend using Git Bash because the commands will match other development environments - this works best on Windows 10 due to Bash integration
- Consistency in solving problems using resources like stackoverflow, etc.
- Download Git from git-scm then launch git bash
- http://www.pcworld.com/article/3050473/windows/heres-how-windows-10s-ubuntu-based-bash-shell-will-actually-work.html

#### git clone - working locally (demo) 

- Distinguish between `git init` and `git clone`
- Demo both
- Clone example - use repo from earlier
- For init - do something new

#### Workflow (demo) 

- Show workflow again, discuss which commands go to where
- Show git cheatsheet
- git clone
- git branch
- git add
- git commit
- git status
- git push
- git diff, git diftool -d

"The command line is the only place you can run all Git commands -- most of the GUIs only implement some subset of Git functionality for simplicity. If you know how to run the CLI version, you can probably figure out how to run the GUI, while the opposite is not necessarily true." - Scott Chacon, Pro Git


## Module 6: Beyond the Basics
This would be a grab bag of more in-depth or advanced  concepts. Here we talk about pull requests, submodules, continuous deployment from GH to Azure, perhaps rebasing, cherry picking, stashing, etc. (that may be too much)

#### GH Pages

#### Multiple remotes

#### Remote tracking branches

#### Combination commands

#### git configs

- Demo seeing configs
- Show image of levels of configurations
- Demo setting some configs

#### Danger Zone: Changing History

- Git can be scary - but it's actually safe once you know some simple commands
- `git revert`
- Watch out for anything that changes a commit ID
  - cherry-pick
  - rebase
  - reset
  - commit amend
- `git reflog`  
