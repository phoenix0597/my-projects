Quick setup — if you’ve done this kind of thing before
Set up in Desktop: https://desktop.github.com/
or	HTTPS:
https://github.com/phoenix0597/my-projects.git
or SSH:
git@github.com:phoenix0597/my-projects.git

Get started by creating a new file (https://github.com/phoenix0597/my-projects/new/main) 
or uploading an existing file (https://github.com/phoenix0597/my-projects/upload). 
We recommend every repository include a README (https://github.com/phoenix0597/my-projects/new/main?readme=1), 
LICENSE (https://github.com/phoenix0597/my-projects/new/main?filename=LICENSE.md), 
and .gitignore (https://github.com/phoenix0597/my-projects/new/main?filename=.gitignore).

…or create a new repository on the command line

```
echo "# my-projects" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/phoenix0597/my-projects.git  # or git@github.com:phoenix0597/my-projects.git
git push -u origin main
```

…or push an existing repository from the command line
```
git remote add origin https://github.com/phoenix0597/my-projects.git  # or git@github.com:phoenix0597/my-projects.git
git branch -M main
git push -u origin main
```
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.