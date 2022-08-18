# CMPG-323-Overview-31612032
Project 1
## Overview:
This repository will be for planning the semester and what needs to be done. Also, a structure will be added on how and when each project is completed as well as a brief explanation on what branching strategy I will be using.
## Project Structure:
I will be using a separate repository for each project. This will help with keeping it clean and organized. 
The projects are as follows: <br />
- Project 1: Agile & Scrum <br />
- Project 2: API Development <br />
- Project 3: Web App Project Testing Patterns <br />
- Project 4: RPA & Testing Project <br />
- Project 5: Reporting Project <br /> <br />
A diagram explaining project and repository context and how they are integrated:
![Readme file photo](https://user-images.githubusercontent.com/90267019/185401475-71e3f993-9e12-4d96-9f5d-711132326a4f.png)


## Branching Strategy:
This is a example of the branching strategy that I will be using throughout my projects:  <br />
![Branching Strategy drawio](https://user-images.githubusercontent.com/90267019/184968243-851c0680-d202-423d-978f-1952389ddd2b.png) <br />
As shown, the main branch will contain the production-ready code. The other branches will be used to work on new features or for bug fixes. These branches will then be merged back into the main branch when completed.
## Why the use of .gitignore files:
These function are used to tell when a file has to be ignored when committing a project to a repository.  <br />
- Files that contain passwords or sensitive information will be ignored. <br />
- Files that are generated by the IDE that we'll be working on should also be ignored.
## Storage of credentials and sensitive information explanation:
The main feature for sensitive information is git-secret. <br />
It encrypts a file and stores it directly in the repository. The history of any changes for every commit will be provided. 
