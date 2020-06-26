### Github

We use github to produce code collaboratively, each subgroup has its own shared code to make research easier.

This is a basic summary of how to use github for collaborative projects in the group. It assumes you have a github [account](https://github.com/kul-group/Group-Handbook/blob/master/Account%20Setup.md#non-essential), are part of [kul-group](https://github.com/kul-group) and are using the Professional version of the PyCharm IDE.

#### Set-up

1. Go to the Github repository you want to work on, click the 'clone' button and copy the URL it shows.
2. Open PyCharm click 'VCS' in the menu bar and select 'Get from Version Control...', paste the URL, and click 'clone'
3. The project will load and you will see a blank menu, in the lower right corner, click the button which says '<no interpreter>' and select your anaconda python interpreter (make sure you have this interpreter set up. See [here](https://docs.anaconda.com/anaconda/user-guide/tasks/integration/python-path/) for instructions.)
4. Then, in the menu bar, go to VCS > Git > 'Pull...', make sure the popup window is filled out and select 'pull', you should now see files when you expand a folder in the 'Project' menu on the left. You could click one of these files and edit it directly, but it is better to create a branch.
5. Create a branch: In the lower right, next to the interpreter button you clicked previously, click the branch button (the label is probably 'master'), and select 'New Branch', name it and click 'create'.
  
You are now ready to make additions to the project! By editing a branch instead of your original copy, you ensure that you always have a working copy of the code; if something goes wrong with your edits, you can go back to the original. Next we will discuss the workflow for adding to a new project.

#### Workflow

1. Clone the repo (see the set-up directions 1-4 above)
2. Checkout a local branch (set-up step 5)
3. Add pages and/or edit exisiting pages
4. Push local branch to remote repository: in the menu bar click VCS > Git > 'Push...', and click 'push' in the popup (you can change the name of the branch you are sending to github by clicking the underlined part in the upper-left of the popup window). You need to have actually made changes and committed them locally for this to work.
5. Go to GitHub and fill out pull request (find your branch, click 'pull request') for the merge into the master branch
6. Checkout/clone the repo regularly to stay up to date with the current status of the project

#### Tips


