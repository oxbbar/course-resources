# Online Courses and General Learning

In this readme you will find:
- [Online courses I've completed/am completing](#courses)
  - Links to them
  - My data

- [Broad Documentation and Tutorials](#broad-resources-and-guides)
  - Websites
  - Documentation
  
- [Specific resources I've found really helpful while learning](#specific-resources-and-guides)
  - Websites
  - Social posts
  - Video guides
  
- [How I set up my workspaces](#software-and-setup)
  - Software, environments and packages
  - Basic commands and brief explanations

## Courses

- [Google Data Analytics Professional Certificate](https://www.coursera.org/professional-certificates/google-data-analytics) //
[My Data](https://github.com/oxbar/course-online-general/tree/main/google-data-analytics-professional-certificate)
  - SQL, R, Tableau
  
- [Google IT Automation with Python Professional Certificate](https://www.coursera.org/professional-certificates/google-it-automation) // 
[My Data](https://github.com/oxbar/course-online-general/tree/main/google-it-automation-with-python-professional-certificate)
  
- [IBM Data Analyst Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-analyst) // 
[My Data](https://github.com/oxbar/course-online-general/tree/main/ibm-data-analyst-professional-certificate)
   
- [Data Science Fundamentals with Python and SQL Specialization](https://www.coursera.org/specializations/data-science-fundamentals-python-sql) // 
[My Data](https://github.com/oxbar/course-online-general/tree/main/data-science-fundamentals-with-python-and-sql-specialization)

## Broad Resources and Guides

### Git / GitHub Desktop

- [GitHub Docs](https://docs.github.com/en)
- [Stack Overflow](https://stackoverflow.com/)
- [Atlassian - Getting Git Right](https://www.atlassian.com/git)
- [Javatpoint - GitHub Tutorial](https://www.javatpoint.com/github)
- [git/github guide, a minimal tutorial - Karl Broman](https://kbroman.org/github_tutorial/)

### Conda / Virtual Environments

- [Conda Documentation](https://docs.conda.io/projects/conda/en/latest/index.html)

### JupyterLabs

- [Jupyter Project Documentation](https://docs.jupyter.org/en/latest/)

### R

- [R Documentation](https://www.rdocumentation.org/)
- [ggplot2: Elegant Graphics for Data Analysis](https://ggplot2-book.org/index.html)
- [Tidyverse.org](https://www.tidyverse.org/)
- [Statistics Globe - Learn R Programming](https://statisticsglobe.com/r-programming-language)

## Specific Resources and Guides

### Git / GitHub Desktop

- [The Git Parable](https://tom.preston-werner.com/2009/05/19/the-git-parable.html)
- [YouTube - "What is Git? Explained in 2 Minutes!"](https://www.youtube.com/watch?v=2ReR1YJrNOM)
- [YouTube - "Git, GitHub, & GitHub Desktop for beginners"](https://www.youtube.com/watch?v=8Dd7KRpKeaE)
- [YouTube - "How to install Git on Windows 10 | Updated 2022"](https://www.youtube.com/watch?v=cJTXh7g-uCM)
- [YouTube - "Git Installation On Windows"](https://www.youtube.com/watch?v=2j7fD92g-gE)
- [How to Use GitHub Desktop: A GitHub Desktop Tutorial](https://www.simplilearn.com/how-to-use-github-desktop-tutorial-article)
- [GitHub Skills](https://skills.github.com/)
- [YouTube - "GitHub Profile Readme"](https://www.youtube.com/watch?v=KhGWbt1dAKQ)
- [YouTube - "How to Edit Github Readme"](https://www.youtube.com/watch?v=-0GjKG4gRmY)
- [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
- [YouTube - "Git Tutorial 8 - .gitignore file"](https://www.youtube.com/watch?v=ErJyWO8TGoM)
- [Connect with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh)
- [YouTube - "How-To Setup SSH Keys for GitHub Using GitBash (+Bonus Tips)"](https://www.youtube.com/watch?v=6e3LCcpjqpc)
- [Git commit](https://www.atlassian.com/git/tutorials/saving-changes/git-commit)

### Conda / Virtual Environments

- [YouTube - "Install Miniconda (Python) with Jupyter Notebook and Setting Up Virtual Environments on Windows 10"](https://www.youtube.com/watch?v=XCvgyvBFjyM)
- [Reddit - "Can anyone explain the differences of Conda vs Pip?"](https://www.reddit.com/r/Python/comments/w564g0/can_anyone_explain_the_differences_of_conda_vs_pip/)
- [Conda User Guide - Tasks](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/index.html)

### JupyterLabs

- [How To Setup Jupyter Lab in 2022 | Data Science for Developers | 14 minutes tutorial](https://www.youtube.com/watch?v=BtYXPY-A9_M)
- [Jupyter Notebook Shortcuts](https://towardsdatascience.com/jypyter-notebook-shortcuts-bf0101a98330)

### Python

- 

### R

- 

### SQL

- 

### Tableau

- 

### Power BI

- 

## Software and Setup

The software I'm using and how I set up to kick it all off.

- [Miniconda](https://docs.conda.io/en/main/miniconda.html)
    - Conda is an open source environment and package manager. Miniconda is a small, bootstrap version of Anaconda that includes only conda, Python, the packages they depend on, and a small number of other useful packages, including pip, zlib and a few others.
        - `conda update conda` to update conda
        - `conda create -n googlecourse python` to create a new environment called 'googlecourse' that includes the latest python and its related packages
        - `conda info --envs` to see the environments list (the 'base' environment is here, as well as my 'googlecourse' environment to mess about in)
        - `conda activate googlecourse` to switch to the googlecourse environment
        - `conda install jupyter` to install jupyter labs in this environment
        - `conda install -c conda-forge r-essentials` - to install the [R programming language essentials](https://anaconda.org/conda-forge/r-essentials) and allow jupyter to use R files

- [Git](https://git-scm.com/)
    - A version control system used to track changes in code and sync local versions with centralised repositories.
        - `git mkdir git` to create a folder in my local user folder.
        - 'cd dir' - to move to this folder.
        - `git mkdir oxbar` to create a folder where repos for my account will go.
        - `cd oxbar` to move to this folder.
        - `git clone https://github.com/oxbar/course-resources` to make a clone of this repo locally. I then updated this readme with some information through github.com.
        - `cd course-reosurces` to move to this repo.
        - `git pull` to pull the latest version, which contains a readme file.
        - If I use jupyter notebooks in this directory, a folder will be created with checkpoints that I don't want synced with the remote repo. So I need to ensure these are ignored.
        - `touch .gitignore` to create the .gitignore file, then manually add .ipynb_checkpoints to .gitignore to avoid Jupyter checkpoint files being pushed to the remote repository.
        - `git status` to see what changes will/will not be committed. 
        - `git add .gitignore` to add .gitignore to the list of files to be committed. I will need to do this for each new repo that will use jupyter notebooks.
        - At this stage, Git is ready to commit and push the changes to the remote repo. I had planned on using GitHub Desktop for everything, but wanted to at least succeed at creating, adding, testing and using a SSH key to push commits, rather than logging in.
        - `git config --list` to see that no user.name or user.email are currently in the configuration.
        - `ls -al ~/.ssh` to see if any files exist in the SSH directory.
        - `ssh-keygen -t ed25519 -C "you@example.com"` to generate a SSH key for a specific email address, then choose a file name ("testfilename") and passphrase
        - `eval $(ssh-agent -s)` to start the SSH agent.
        - `ssh-add ~/.ssh/testfilename` to add the SSH key file above to the SSH agent list.
        - `clip < ~/.ssh/testfilename.pub` to copy the SSH key to the clipboard, then add it as a new SSH key in https://github.com/settings/keys.
        - `ssh -T git@github.com` to authenticate with GitHub (check key fingerprint matches with https://docs.github.com/en/github/authenticating-to-github/githubs-ssh-key-fingerprints)
        - `git remote set-url origin git@github.com/<Username>:<Project>.git` I used this because when I cloned the repo earlier it was through https and caused errors with SSH. I should have used `git clone git@github.com:<Username>:<Project>.git`
        - `git commit -m "gitignore file."` to commit this updated gitignorefile, but Git asked me to confirm my author identity
        - `git config --global user.email "you@example.com"` to set my account's default email address
        - `git config --global user.name "Your Name"` to set my account's default username
        - `git commit -m "gitignore file."` to commit this updated gitignore file with account identification now present.
        - `git push"` to push the changes to the remote repository.
    
- [GitHub Desktop](https://desktop.github.com/)
    - An application to interact with GitHub via a GUI. 
    - I wanted to use both Git Bash and GitHub Desktop to understand the processes.
        - Repository >> Repository settings... >> Ignored files (replicates the above process)
