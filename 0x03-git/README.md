## 0x03. Git

Orlando Gomez Lopez

Holberton

Cohort 10

Cali Colombia

9 september 2019

# Requirements

General
A README.md file at the root of the holbertonschool-zero_day repo, containing a description of the repository
A README.md file, at the root of the folder of this project (i.e. 0x03-git), describing what this project is about
Do not use GitHubs web UI, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You wont be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
Your answer files should only contain the command, and nothing else
More Info

# Tasks

# 0. Repo-session mandatory

Score: 100.00% (Checks completed: 100.00%)
	Create a new directory called 0x03-git in your holbertonschool-zero_day repo. Make sure you include a README.md in your directory.

	Repo:

	GitHub repository: holbertonschool-zero_day

# 1. Coding fury road mandatory

Score: 100.00% (Checks completed: 100.00%)
	For the moment we have an empty project directory containing only a README.md. Its time to code!

	Create these directories at the root of your project: bash, c, js
	Create these empty files:
	c/c_is_fun.c
	js/main.js
	js/index.js
	Create a file bash/holberton with these two lines inside: #!/bin/bash and echo "Holberton"
	Create a file bash/school with these two lines inside: #!/bin/bash and echo "School"
	Add all these new files to git
	Commit your changes (message: Starting to code today, so cool) and push to the remote server
	Repo:

	GitHub repository: holbertonschool-zero_day
	Directory: 0x03-git
	File: bash/holberton, bash/school, c/c_is_fun.c, js/main.js, js/index.js

# 2. Collaboration is the base of a company mandatory

Score: 100.00% (Checks completed: 100.00%)
	A branch is like a copy of your project. Its used mainly for:

	adding a feature in development
	collaborating on the same project with other developers
	not breaking your entire repository
	not upsetting your co-workers
	The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers work.

	For this project, create a branch update_script and in this branch:

	Create an empty file named bash/98
	Update bash/holberton by replacing echo "Holberton" with echo "Holberton School"
	Update bash/school by replacing echo "School" with echo "The school is open!"
Add and commit these changes (message: My personal work)
	Push this new branch Tips
	Perfect! You did an amazing update in your project and its isolated correctly from the master branch.

	Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:

	Change branch to master
	Update the file bash/holberton by replacing echo "Holberton" with echo "Holberton School is so cool!"
	Delete the directory js
	Commit your changes (message: Hot fix) and push to the origin
	Ouf, hot fix is done!

	Repo:

	GitHub repository: holbertonschool-zero_day
	Directory: 0x03-git
	File: bash/holberton, bash/school, bash/98

# 3. Collaboration: be up to date mandatory

Score: 100.00% (Checks completed: 100.00%)
	Of course, you can also work on the same branch as your co-workers and its best if you keep up to date with their changes.

	For this task  and only for this task  please update your file README.md in the master branch from Github.com. Its the only time you are allowed to update and commit from Github interface.

	After you have done that, in your terminal:

Get all changes of the master branch locally (i.e. your README.md file will be updated)
	Create a new file up_to_date at the root of your repository and in it, write the git command line used
	Add up_to_date to git, commit (message: How to be up to date in git), and push to the origin
	Repo:

	GitHub repository: holbertonschool-zero_day
	Directory: 0x03-git
	File: README.md, up_to_date

# 4. HAAA what did you do??? #advanced 

Score: 50.00% (Checks completed: 50.00%)
	Collaboration is cool, but not really when you update the same file at the same time

	To illustrate that, please merge the branch update_script to master: Cool, all my changes will be now part of the main branch, ready to be deployed!

	HHHHHHHAAAAAAAA

	CONFLICT (content): Merge conflict in bash/holberton
			    As you can see, you have conflicts between two branches on the same file.

					  Your goal now is to resolve conflicts by using the version of the branch update_script, and push the result to the origin.

					  At the end, you should have all your work from the branch update_script (new file and two updated files) and all latest master commits (new files, delete folder, etc.), without conflicts.

					  Repo:

					  GitHub repository: holbertonschool-zero_day
					  Directory: 0x03-git

# 5. Never push too much #advanced

Score: 50.00% (Checks completed: 100.00%)
	Create a .gitignore file and define a rule to never push ~ files (generated by Emacs). Tips

	Repo:

	GitHub repository: holbertonschool-zero_day
	Directory: 0x03-git
	File: .gitignore

