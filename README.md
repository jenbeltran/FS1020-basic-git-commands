# fs1020-open-lab-1: Introduction to git commands

## Scenario: Imagine that you are a developer on a team and need to add a new landing page to a website. 

1. Please clone this repo

```git clone```

2. Open the folder in VS Code

3. Make a new branch before you add/make changes to the code. Think about it as making your own copy so you don't edit the main file AND so others can't tamper with your copy. **DO NOT MAKE CHANGES IN MASTER BRANCH!**

```git checkout -b landing-page-your-name```

Want to see all the branches you have? `git branch`

4. Now that you have your own branch, you want to make sure that your branch is up-to-date with the master branch. In other words, you want to make sure you have the most updated copy of the file.

```git pull origin master```

5. Now that you have the updated copy. It's time to add your new page!

In the views folder, please create a new HTML file and name it **'landing-page-your-name.html'**

You can add anything you want in the HTML file. Feel free to copy my example.

6. You've successfully created a new landing page and it's ready to commit to the main file (aka Master branch)! 

```
git add -A
git commit -m “type your message here...ex. added new landing page”
git push
```

7. Did your boss just assign you the 'Contact Us' page too? Repeat steps 3-6 whenever you need to add a new feature. # FS1020-basic-git-commands
