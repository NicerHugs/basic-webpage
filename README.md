### Terminal
- to open terminal, use the spotlight search (command and spacebar) and type in "terminal"
- we used terminal to install "git"
	- to check if git is installed, type "git" into the terminal and press enter.
	- if it is not, you may be prompted to install some x-code-select tools. just follow the prompts!
		- eventually you will be prompted to enter your password - this is the password for your computer. you won't see it as you type, but it IS working! press enter when you're done
	- if it is, you should see output that describes the commands you can use with git.
- we used terminal to set up a "git repository" for our project
	- first we had to "move" into the project folder
	 	- find the folder in Finder
		- in terminal, type "cd " (don't forget the space)
		- now drag your folder from Finder into the Terminal window
			- the terminal should now say "cd /path/to/the/project/folder"
		- press enter
			- you should now be "in" the project in terminal.
			- read the terminal prompt to be sure you are in the right place. you should see the name of your folder in the prompt.
	- next, we initiate a git repository. You only have to do this step one time.
		- after you've made your project folder and moved into your project folder:
		- type "git init" and press enter.
			- to see if this worked, try typing "ls -a" and pressing enter
				- you should see the names of all the files in your project AND it should also say ".git"
				- if you don't see ".git" this means your "git init" didn't work correctly.
- we used terminal to "push" our code to the internet
	- after you've made your git repository AND made your GitHub repository:
	- the FIRST TIME you want to push your website to GitHub:
		- copy the code under "…or push an existing repository from the command line"
		- paste it into terminal and press enter
	- if you want to change your website after you have already pushed it to GitHub:
		- make sure you are "in" your folder in terminal (see above)
		- type the following commands:
			- "git add ." (this adds all your changes to the project)
			- "git commit -m 'some message about what you did'" (this is like your save name)
			- "git push origin master" (this actually pushes your code to the internet)

### TextEdit
- we used TextEdit to write our HTML file
	- We had to change some settings to make TextEdit work for writing HTML:
	- from TextEdit, open preferences
		- in the New Document tab
			- under Format, select "Plain text"
			- under Options, unselect "smart quotes", "smart dashes" and "smart links"
		- in the Open and Save tab
			- under When Opening a File, select "Display HTML files as HTML "
			- under HTML Saving Options, select "No CSS" for Styling

### Google Chrome Inspector
- we used the inspector and edit a live website
- To open the inspector, open a website in Google Chrome
- In the View menu --> Developer --> Developer Tools
- OR type Option Command J
- Make sure the Elements tab is selected

### GitHub
- we used GitHub to store our code on the internet
	- to make a project on GitHub, find the green "New" button to make a new repository
	- give your project a name and click "Create Repository"
- we used GitHub to host our website
	- After you have pushed your code to GitHub from the terminal (see above):
	- in Github, from your repository page, go to the Settings tab.
	- scroll down until you see "GitHub Pages" and change "Source" to "Master Branch" and save.
	- now when you scroll down to GitHub Pages you should see the URL of your website!
