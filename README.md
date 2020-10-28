# Notes for GitHub presentation

[Tech Tools for Collaboration](https://docs.google.com/presentation/d/1CoWJMspDieE7RUDhEei60j7TyEVY9ACh-Kmlu9MIFGQ/edit?usp=sharing) - this was a previous presentation I did in which Git and GitHub are mention

Examples in libraries:

[CGP on GitHub](https://github.com/usgpo/cataloging-records)

[GitHub for non programmers](https://github.com/tvanantwerp/github-for-non-programmers)

[EZ Proxy IP Blacklist](https://github.com/prbutler/EZProxy_IP_Blacklist)

For those doing 

[Library Carpentries: Introduction to Git](https://librarycarpentry.org/lc-git/)



## Why use Git and GitHub

Before getting into the specific steps on how to use Git and GitHub - it's important (and often overlooked) to look at the reasons why Git/GitHub will make your work easier and better.
* Version control
	* Which file is the final version?
	* Backing up files
		* Easily revert to previous versions of a file
			* Good for situations where a change might break the project (code, html, css)
* Attach metadata to file changes
	* What has changed in this file
	* Why was this edit made?
	* Who made this edit?
* Enable collaboration
	* Conflict free changes/edits
		* Collision resistant collaboration
	* On GitHub can create and track issues
	* Can fork projects (copy projects and maintain as separate)
	* Can review changes before adding to main project
		* Pull request
* Free hosting
	* GitHub can host files
	* GitHub can be used for websites
		* Github.io
		* Personal websites
			* myqua.github.io (change this!)
		* Write in Markdown and website is converted automatically into HTML
		* Here's some examples of GitHub hosted Websites
			* Conferences
				* Code4Lib - https://github.com/code4lib/2020.code4lib.org
	* Open source software project - (of course!)
		* Islandora
	* Examples from Library Carpentries
		* Local library looking to start a crowdsourcing project
		* Multiple people editing metadata for a collection 

## Basics of using Git

* Three options
	* Download software
		* Use command line
		* Use software GUI
	* Use only on GitHub
* Create a repository
	* git init
* Check status of a project
	* git status
* Add a file 
	* git add myfile.txt
	* File now in staging area
* Commit a file
	* git commit -m
	* Saves the file's state
	* Adds a short descriptive message
		* Sample messages
* Compare add and commit as staging a photo
	* It's a two stage process
	* Add puts subjects in the frame
	* Commit takes the snapshot
* See differences between versions
	* git diff
		* Shows changes between an edited file and the file's most recent commit

## Basics of using GitHub

* Make a remote repository
	* git remote add origin https://github.com/myname/hello-world.git
	* git push -u origin main
		* origin is the site/repository
		* main is the branch  
	* git pull
		* downloads files from a remote repository to your local
* GitHub pages
	* Build a website using GitHub pages
	* Use a static site generator to convert repository into website
		* Jekyll
	* GitHub.io
		* Build a personal/professional site
