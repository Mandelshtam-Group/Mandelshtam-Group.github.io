# Group Website
Welcome to the Github Repository for the Mandelshtam Group [Website](https://mandelshtam-group.github.io) at the University of California, Irvine!

# Contributing to the Project
Here we provide a quick summary for contributing to the project (intended for new group members).
The internet is a much better resource for working with Git/Github, please refer to official documentation if you need help with Git/GitHub version control. 

Note: a `$` character implies to type the following text into the terminal, i.e. do not include the $. 

## Fork the Original Repository
Go to the Mandelshtam-Group [Repository](https://github.com/Mandelshtam-Group/Mandelshtam-Group.github.io) and use the `fork` option to make your own version of the website repository. 

## Clone Your Website Repository 
Now that you have a personal version of the website on your GitHub page you can clone it to start developing locally.
To do this, go to your version of the website repository and copy the `clone` url.

Now on your terminal make a directory for holding the Github repository and use `$ git clone your-url`. 
This version of the repository will be referred to as the `origin`.
If you type `$ git remote -v` on your terminal you should see the origin remote. 
Also use `$ git status` to check on the state of your local repository. 

## Connecting the Upstream
It is possible that the original version of the Website (which we will call the `upstream`) will be changing as other group members work on the project.
We therefore need to connect the `origin` version (your forked version) to the `upstream` repository.

Note: You only need to set the upstream remote once. 

To set the upstream go to the Github upstream Repository (the [Mandelshtam-Group](https://github.com/Mandelshtam-Group/Mandelshtam-Group.github.io) version) and copy the git clone url. 

Now on the terminal in your origin directory use `$ git remote add upstream upstream-git-url)`
Once you have done this try `$ git remote -v` and you should see both your origin remote, and the upstream remote. 

## Synchronizing with the Upstream 
Once you have set the upstream you can use the `$ git pull upstream master` command.
This will fetch and merge the upstream master branch with your origin master branch.
In this way your origin can stay up to date with the upstream.
You should be running this command frequently to check back with the upstream (this will make pull requests easier to merge). 

## Developing Your Version of the Website
Now that you have a local version that is up-to-date with the upstream, you are free to develop.
Once you are happy you can use `$ git add .` to add all changes you have made to staging, then use `$ git commit ` to commit the changes in staging (make sure you add a relevant commit message).

You are now ready to push the changes you have made on the origin to your version of the website on GitHub.
The command `$ git push origin master` will push your commits to your GitHub.

(Note: you may want to look into [branching](https://guides.github.com/introduction/flow/) when you are developing). 

## Pull Request
Once you have updated the origin master on your GitHub page you will want to incorporate your changes into the upstream project. 
This can be done on GitHub.
Go to your Github page (origin) and select the `pull request` option. 

If everything is working choose the create pull request to submit your changes to the group website repository!

