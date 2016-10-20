# Learning to use Git

* Creating A New Project
* Create an app or collection of files to give to GitHub
* Create a GitHub Repo called test-app

# Updating An Existing Project
	$ cd path/to/directory/where/you/app/or/files/are
	$ git init
	$ git add .
	$ git commit -m "first commit"
	$ git remote add origin git@github.com:DigitalDsntHurt/test-app.git
	$ git push -u origin master

# Updating An Existing Project
	$ cd path/to/your/dir

# Clone the project	(master branch)
	$ git clone git@github.com:DigitalDsntHurt/test-app.git
	$ cd test-app

# Clone the project	(particular branch)
	$ git clone -b branch-name --single-branch git@github.com:DigitalDsntHurt/test-app.git
	$ cd test-app

# Make & save changes to files ~
	$ git add .
	$ git commit -m "i changed some files"
	$ git remote add origin git@github.com:DigitalDsntHurt/test-app

# Create a new branch and switch to it
	$ git checkout -b new-branch

# Push changes to new branch
	$ git push origin new-branch