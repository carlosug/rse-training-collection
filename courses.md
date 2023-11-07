
# Software Carpentry Workshop with Python

## Goal:
> Help researchers get their work done in less time and with less pain by teaching the basic research computing skills.

## Requirements:
No prior knowledge is required

## Level:
Essentials (foundational skills)

## Family root:
.

## Duration:
3 half-days

## Overview content and lessons:

1. Intro to Python programming I and II *with Anaconda*:
    - python fundamentals
    - analysing and visualising data
    - storing data and lists object
    - repeating actions with Loops
    - analysing data from multiple Files
    - creating functions
    - errors and exceptions
    - defensive programming
    - debugging
    - **Command-Line Programs**
        - command-line arguments, handling multiple files, flags and standard Inputs

2. Intro the Unix Shell:
    - navigating files and directories
    - working with files and directories
    - pipes and filters
    - loops
    - shell scripts
3. Version Control with Git:
    - creating repository
    - tracking changes
    - exploring history
    - ignoring Things
    - remotes in Github
    - collaborating
    - conflicts
    - open science

---
# Coderefinery workshop

## Goal:
> teach basic scientific computing tools and become familiar with tools and best practices for scientific software develpment

## Requirements:
Some programming experience, but generic-proposed approach

## Family root:
.

## Level:
Essentials (foundational skills)

## Duration:
6 half-days

## Overview content and lessons:

1. Intro to version control with Git I, II, III, and IV
    - creating repository
    - adding files and commiting changes
    - git history and log
    - writing useful commit messages
    - ignoring files and paths
    - creating and working branches
    - merging and deleting branches
    - conflict resolutions 
    - publishing an existing repository
    - cloning a repository
2. Collaborative distributed version I and II
    - Centralized workflow
    - creating pull request
    - code review and merging changes
    - version control
    - fork and clone
    - pen pull request
3. Reproducible research:
    - preparing code to be usable by you and others in the future 
    - organizing projects with readme.md
    - directory structure
    - tracking source code, data, and results
    - reproducible publication e.g. binder, rrtools, jupyter notebooks (not practical)
    - recording computational steps e.g. snakemake *(Make GNu is not included)*
    - recording dependencies e.g. python venv and requirements.txt or environment.yml
    - recording environment e.g. container Singularity *(Docker, podman is not included in practice)*
4. Social coding and open software:
    - Social coding: sharing software, code reusability
    - software licensing
    - software citation e.g. citation.cff
    - sharing data: general institutional repositories *(what about models)*
5. How to document your research software:
    - in-code documentation
    - readme files
    - reStructuredText and Markdown
    - HTML static site generators
    - Wikis
    - deploying Sphinx documentation to Github pages
    - Hosting websites/homepages on Github
6. Jupyter notebooks
    - a tool to write and share executable notebooks and data visualization
7. Automated testing
    - preventing yourself and others from breaking your functioning code 
    - testing type
    - test design e.g. pytest
    - enabling automated testing **github actions**
8. Modular code development
    -  Making reusing parts of your code easier 

---


# TUDelft - Version control & collaborative development for research software

## Goal:
> Help researchers get familiar with using Git for effectively managing source code and decentralised repository as well as succesfully manage research software, establishing efficient workflows and splitting resposabilities within a project

## Requirements:
Little knowledge on command-line interface with Unix Shell. It is required to know how to navigate, create, edit, visualise and append command output to a file via Unix Shell. Software carpentry 2 and 3 content is desired.

## Family root:
Coderefinery lessons

## Level:
Essentials (foundational skills)

## Duration:
4 half days

## Overview content and lessons:

1. Fundamental operations with git:
    - git repositories for version control
    - tracking changes in working documents
    - organizing tracked changes in a history
2. Branching and remote operations:
    - branching
    - operations with remotes
3. Collaborative software development:
    - connecting to code repositories
    - exploring Github GUI
    - management strategies
    - documenting issues
    - pull reuqests
4. Collaborative software development:
    - code reviews
    - guidelines
    - open source license
    - citation
    - releasing software
    - semantic versioning


---

# eScience Center - Good practices in Research software development

## Goal:
> Researchers learn good software practices and skills to  facilitate open and reproducible research, focus on methods to build, modular, reusable, maintainable, sustainable, reproducible, testable, and robust software

## Requirements:
Little knowledge on command-line interface with Unix Shell. It is required to know how to navigate, create, edit, visualise and append command output to a file via Unix Shell. Software carpentry 2 and 3 content is desired.

## Family root:
Coderefinery lessons

## Level:
Essentials (foundational skills)

## Duration:
4 half-days

## Overview content and lessons:
1. Introduction to best practices in Research Software Development:
2. Introduction to git:
3. Collaboration with git and Github:
    - how can we collaborate with others within one repository
    - how can we collaborate with people who we might not know yet
    - what is fork and clone
    - what is a pull request or merge request
    - what is code revivew
4. Modular code development:
    - what is modularity and its components
    - why write modular code to make maintenance easie, maximise reusability, and facilitate scalability
    - when to create modular code
5. Documentation:
    - focus on coderefinery lesson: [in-code comments and README's](https://coderefinery.github.io/documentation/guide/#a-lesson-with-a-focus-on-in-code-documentation-and-readme-files)
    - why to document software
    - what makes good documentation
    - how to write in-code documentation
    - how to write good readmes files
    - how to create documentation with Sphinx and readtheDocs
    - how to deploy on your personal homepage to Github pages
6. Testing and continous integration:
    - focus on pytest- unit test [coderefiniery lesson](https://coderefinery.github.io/testing/pytest/)
    - how to automate integration of code changes from multiple contributors into a single software project
    - how to setup continous integration in Github
    - for what ca I use continous integration
    - recap full-cycle collaborative workflow coderefinery [lesson](https://coderefinery.github.io/testing/full-cycle-ci/)
    - how to do five test in code refinery [test design lesson](https://coderefinery.github.io/testing/test-design/)

---

# Swiss SIB - First Steps with UNIX in Life Science

## Goal:
> Researchers (focus on bio informatics) learn most useful commands of Git, an intro to collaborative workflows and how to use Github

## Requirements:
no background in 

## Family root:
.

## Level:
Essentials (Foundational skills)

## Duration:
(-) full days and half

## Overview content and lessons:
- What is UNIX and why should biologists use it?
- UNIX filesystem: navigation and usage
- Environment, processes & Jobs
- Working with directories
- Working with files and file content


---


# Swiss SIB - Version control with Git

## Goal:
> Researchers learn most useful commands of Git, an intro to collaborative workflows and how to use Github

## Requirements:
recommended basic knowledge of unix command line and following introductory using Bash shell at their [UNIX course](https://www.sib.swiss/training/course/20240116_FSWU)

## Family root:
SIB lessons

## Level:
Essentials (Foundational skills)

## Duration:
2 full days and half

## Overview content and lessons:

1. First steps with Git:
    - introduction to version control systems and Git
    - Git basics: your first commit
    - Git concepts: commits, the HEAD pointer and the Git index
    - Git branches: introduction to branched workflows and collaborative
    - workflow examples
    - branch management: merge, rebase and cherry-pick
    - retrieving data from the Git database: git checkout
    - working with remotes: collaborating with Git
    - GitHub: a brief overview

2. Git advanced topics:
    - rewriting history: interactive rebase, git reset and commit amending.
    - the detached HEAD state explained
    - the Git stash: Git’s “cut and paste” functionality
    - Git tags: label important commits
    - GitHub: creating a new project, adding new users and collaborating wit them
    
3. optional modules:
    - GitHub Actions and GitLab CI/CD: writing automated pipelines
    - Git submodules: embed a Git repository as a subdirectory of another Git repo
    - Git LFS: versioning large files with Git


---

# Carpentry - Intermediate Research Software Development with Python

## Goal:
> Researchers learn the core set of intermediate-level software development skills and best practices for working as part of a team in a research environment using Python.

## Requirements:
Basic knowledge and skills on research software development by attending [novice Software Carpentry Python Course](https://software-carpentry.org/lessons)

## Foundations:
Based on [Incubator Intermediate Research Software Development Skills In Python Lesson Material](https://github.com/carpentries-incubator/python-intermediate-development/tree/gh-pages)

## Level:
Essentials (foundational skills)

## Duration:
4 full-days

## Overview content and lessons:
1. Setting up environment for collaborative code development
- intro yo virtual environment
- collaboration usinhg git
- coding convetions with python code style

2. Ensuring correctness of software at scale
- automatically testing software
- scaling up unit testing
- continous integration for automated testing
- diagnosing issues and improving robustness

3. Software development as a process
- software requirements
- software architecture and design
- programming paradigms
- functional programming intuition
- object-oriented programming intuition

4. Collaborative software development for reuse
- developing software in a team as code review
- preparing software for reuse and release
- packing code for release and distribution

5. Managing and improving softwre over its lifetime
- managing a collaborative software project
- software improvement through feedback

---

# eScience Center - Intermediate Research Software Development with Python

## Goal:
> Researchers learn the core set of intermediate-level software development skills and best practices for working as part of a team in a research environment using Python.

## Requirements:
Basic knowledge and skills on research software development by attending [novice Software Carpentry Python Course](https://software-carpentry.org/lessons)

## Foundations:
Based on [Incubator Intermediate Research Software Development Skills In Python Lesson Material](https://github.com/carpentries-incubator/python-intermediate-development/tree/gh-pages)

## Level:
Essentials (foundational skills)

## Duration:
4 full-days

## Overview content and lessons:
1. Setting up environment for collaborative code development
- intro yo virtual environment
- collaboration usinhg git
- coding convetions with python code style

2. Ensuring correctness of software at scale
- automatically testing software
- scaling up unit testing
- continous integration for automated testing
- diagnosing issues and improving robustness

3. Software development as a process
- software requirements
- software architecture and design
- programming paradigms
- functional programming intuition
- object-oriented programming intuition

4. Collaborative software development for reuse
- developing software in a team as code review
- preparing software for reuse and release
- packing code for release and distribution

5. Managing and improving softwre over its lifetime
- managing a collaborative software project
- software improvement through feedback

---





