# First-Contribution
Making Your First Contribution to an Open Source Project

Hello There, if you are new to Github, and want to dive into the world of open source contribution, you are at right place. Just follow this tutorial, and you will be done with your first contribution to open source.

## Getting Things Ready
Before we start, make sure:
- You have a github account, and logged in.
- You have installed git locally on your machine.
- You have opened this repository in two tabs.\
  One for Reading and second for following tutorial, as your first contribution will be on this repository :)  


# Forking
Now first step is forking, because we don't want to make a change in the original repository at the first stage. 
On the top right of your page, you can see a button with name Fork. \
Click that and follow the said steps, now the repository has been forked to your own repositories. We will make changes in it and then add them into the main repository.

# Cloning
If you just want to make some minor changes, like some changes in readme etc, you can work directly on the forked repository online. But, if you want to make some changes in code, you should clone this repository to local machine and then make the changes.\
For that, copy the url of your forked repository , it will be like ```https://github.com/<your-username>/First-Contribution```
Now make a folder in your local machine where you want to clone the repository. \
In that folder, write open git bash by right clicking.\
Now clone the app by entering following command:
```
git clone <url you copied>
```

It will be like:
```
git clone https://github.com/<your-username>/First-Contribution
```
Great, now you have cloned the app to your machine.

# Adding New Branch
For making changes, we will make a separate branch, so that this doesn't mess up with the main branch. We do this because if something goes wrong, we can discard this branch.

First change directory to the cloned repository using ```cd First-Contribution```\
Now, in git bash, write this command:
```
git switch -c <your-branch-name>
```

For example:
```
git switch -c myFirstContribution
```

# Making Changes
Now you can make the required changes. For this repository, you should add your picture and link to your github profile to Contributors.md with comments\
That's basic html, so you should figure it out your self. One thing for getting the image link is that you can get the rounded image from this link : https://images.weserv.nl/?url=avatars.githubusercontent.com/u/94343225?v=4&h=50&w=50&fit=cover&mask=circle&maxage=7d , by changing 94243225 with your id.
Or you can upload place picture in pictures folder and then add that in contributors.md, that's upto you.



# Commiting Changes
Now it's time to commit changes. \
First, let's check the status of repository for any changed files.
```
git status
```

Now, stage the changed files, using this command:
```
git add .
```

The dot is for all changed files, if you want to change a particular file, you can use it's name as ```git add <filename>```\

Now, commit the changes.
```
git commit -m "Commit Message"
```

like:
```
git commit -m "Added my picture with link to id : github.com/umarfarooq478"
```

After that, just push the repository to origin, using:
```
git push -u origin <your-branch-name>
```
branch name is what you used earlier, like

```
git push -u myFirstContribution
```



# Generating Pull Request
Now, navigate to your repository on github.com. There will be an option of compare and genrate Pull Request, just click that. If it is not showing, refresh the page.\ \

After that add the details of what you have done, and go ahead. \ Finally, I will review it and merge in the main branch, and you will be a contributor to this open source list :))))
