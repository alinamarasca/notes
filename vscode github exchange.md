## Working with VSCode and GitHub

---

### Cloning through VSCode

1. work through **termial**
2. `git clone https://link to directory`
   will copy into directory you are currently in

**Want to check if you are in git repo now?**

Get in th folder you copied:

1. `cd foldername` enter
2. `la` list all
   you will see all files on repo including **.git** folder

---

### Making changes in VSCode and applying them to GitHub files

_e.g._ We have README.md.Change it, save it. To apply changes to GitHub:

1. work through **termial**
2. `git status` to see which files were modified
3. `git add .` will add all files listed above
4. `git commit -m "Your comment to changes which adds to title box on GH" -m "Your comment which adds to description box on GH"`
5. Now files are ready to be **pushed** to GitHub.
   `git push origin master`

   ***

   ### Starting repository in VSCode and pushing it to GH.

6. Create folder in VSCode.
7. Get into it:
   `cd ../foldername`
8. Let's add a README.md file and type `git init` in **terminal**

`git add Readme.md` enter

`git commit -m"blah blah"` enter

4. Create empty repository on GitHub.
5. `git remote add origin https:/link to our repo`
6. `git push origin master`
