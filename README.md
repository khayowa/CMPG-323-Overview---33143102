# CMPG-323-Overview---33143102
IT Development Semester Project Overview

## Project and Repository structure
The CMPG-323-Overview repository will accommodate for Project 1
<br>
<br>
Each project will be integrated with a unique repository as follows:
<br>
<ul>
<li><a href= "https://github.com/khayowa/CMPG-323-Project-2---33143102">Project 2 - API Development</a></li>
<li><a href= "https://github.com/khayowa/CMPG-323-Project-3---33143102">Project 3 - Web App Project Testing Patterns</a></li>
<li><a href= "https://github.com/khayowa/CMPG-323-Project-4---33143102">Project 4 - RPA and Testing Project</a></li>
<li>Project 5 - Reporting Project</li>
</ul>

## Integration of project and repository context diagram

## Branching Strategy
The Feature Branching Strategy is the approach that will be taken throughout the development and maintenance cycle. This will consist of a main branch which will be protected and a develop branch which will be default. For any feature addition, a feature branch will be created and merged with the develop branch. After all the necessary features are merged to the develop branch, a pull request to the main branch will be submitted to add all the features from the develop branch at once. A hotfix branch will modify the main branch directly and the develop branch to keep correlation between main and develop.

## Use of a .gitignore file
A .gitignore file is used to ignore a chosen file or folder. In API development which is project 2, a .gitignore file is highly required to allow builds to come from one source. This is essential as during development, modifications or debbuging applies on the same feauture. Web app project testing patterns, project 3 and RPA and testing project, project 4 will also require a .gitignore file as this will help avoid potentially costly commits of files that should be versioned during testing.

## Storage of credentials and sensitive information
The storage of sensitive information will be kept in a configuration file. No form of credentials or sensitive information will be handled in the source code as this goes against security protocols. In ASP NET Core a Secret Manager tool can be implemented to store sensitive information. Managing user secrets is beneficial to the extent of working with git as secrets are omitted from commits.
