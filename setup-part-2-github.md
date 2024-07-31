
# CTP SETUP PART 2:  Setting Up Github 

### THIS IS THE SECOND STEP OF GETTING SETUP FOR CTP.   DON'T DO THIS UNLESS YOU'VE ALREADY COMPLETED [THIS SETUP GUIDE](https://github.com/CUNYTechPrep/2024-python-summer-prep/blob/main/setup.md) FIRST.  


Here we are going to setup github so we can easily log in and push changes to github.  

We will be following Github's [Official Guidelines for setup](https://docs.github.com/en/get-started/getting-started-with-git/set-up-git#setting-up-git):
* Install [Github Command Line Interface](https://github.com/cli/cli#installation)
* [Follow these Official Installation Steps Here](https://docs.github.com/en/get-started/getting-started-with-git/set-up-git#setting-up-git)
	* Follow the steps carefully. Make sure to:
		1. Install the Github CLI (Command Line Interface)
		2. Install or Update Git
		3. Set git Username and Email address
		4. Run the `gh auth login` command. 
		5. Follow the instructions in the terminal, below are the options you want to pick for each question:
``` 
? What account do you want to log into? 
	GitHub.com

? What is your preferred protocol for Git operations on this host? 
	HTTPS

? Authenticate Git with your GitHub credentials? 
	Yes
? How would you like to authenticate GitHub CLI? 
	Login with a web browser. ENTER
```

### Making Sure It Works - Create and Edit your own Repo
1. Go to your github homepage. 
2. Create a repo.
3. Clone said repo to your computer locally.  
4. CD into that repo folder. 
5. Edit file in repo
6. Add, commit, and push changes. 
```
git status
git add [TYPE IN FILENAME]
git status

git commit -m "I added my first edit in the readme"
git status

git push
```
7. Now check your repo on the internet to see if the files are updated. 

