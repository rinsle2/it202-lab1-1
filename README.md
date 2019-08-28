# lab 1-1:   Codio and GitHub basics

Create a basic HTML page, create a GitHub repository, connect this project to your repo, and push updates.



## Create and test a page in Codio

1. Navigate to https://www.w3schools.com (a site you'll come to know well)

2. Find the __Learn HTML__ section.

3. In the left nav, find the page titled __HTML5 Intro__.   That page includes a basic HTML5 document;  copy and paste into your index.html file.

4. Update the content of the <title> element to be your name.
    
5. Preview your index page by selecting "Current File (static)" from the menu.  (We're not previewing a project running some executable code;  for most of our work, we simply want to open our files in a web browser.)  
Why aren't you seeing your name?  View the page source (right-click in the browser) to verify that you're loading your updated page.  Why isn't your name displayed?  Check the browser tab.

6. Update your index.html file, setting the content of the H1 element to be your name, save and refresh the preview window.

7. Copy the URL (address) of your page, navigate to https://validator.w3.org/#validate_by_uri, paste your page URLin to box and test it.   Take a look at the results.  If there are errors, update your file and test until fixed.


## Create a GitHub account and repository


8. If you don't have one, create a free account on https://github.com 

9. Create a new repository, named __it202-lab1-1__; do __NOT__ "Initialize this repository with a README"


## Add a Git to your Codio project

10. On Codio, open a terminal window (Tools > Terminal)

11. At the prompt, type in "git init" .  This will create a new Git on your project.

## Connect your Codio Git to your GitHub repository

12. On your GitHub repo page, click the green "Clone or Download" button, and copy the address in the dialog box.

13. In your Codio terminal window, type ```git remote add master ``` followed by your repo address.  


