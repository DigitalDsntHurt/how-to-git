# Learning to use Git

# Create A New Project
* Create an app or collection of files to give to GitHub
* Create a GitHub Repo called test-app
* Upload to master branch

# Update An Existing Project
	$ cd path/to/your/dir

# Clone the project	
	$ git clone git@github.com:DigitalDsntHurt/test-app.git
	$ cd test-app

# Make & save changes to files ~
	$ git add .
	$ git commit -m "i changed some files"
	$ git remote add origin git@github.com:DigitalDsntHurt/test-app

# Create a new branch and switch to it
	$ git checkout -b new-branch

# Push changes to new branch
	$ git push origin new-branch