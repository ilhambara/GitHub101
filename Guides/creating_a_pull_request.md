 #  Creating a Pull Request (PR) on GitHub


1. #### Find a project you want to contribute to.
    Browse GitHub and find a project that piques your interest.
    
2. #### Fork it.
    A fork is a copy of a repository that allows you to freely experiment with changes without affecting the original project. Click the fork button on the top right of any project to do so.
    ![Fork Button](/images/fork_button.jpg)
    
3. #### Clone it to your local system.
    Locate the green "code" button on your newly cloned project.  
    ![Code Button](/images/code-button.png)   
    Click the clipboard button to copy the repository web URL.    
    ![Clone Button](/images/https-url-clone.png)  
    In your terminal type `$ git clone https://github.com/<YOUR-USERNAME>/<ORIGINAL-REPOSITORY-NAME>`.  
    This creates a local repository from your remote one.
    
4. #### Make a new branch.
    Open your newly cloned repository by typing `$ cd ORIGINAL-REPOSITORY-NAME`.  
    Then type `$ git checkout -b <BRANCH-NAME>` to create a new branch.
    
5. #### Make your changes.
    Open up the project by typing `$ code .`, and make the appropriate changes.
    You can alternatively open the repository in any other IDE too.
    
6. #### Push it back to your repo.
    Add your changes by typing `$ git add .`.  
    Then add a commit message by typing `$ git commit -m "YOUR-COMMIT-MESSAGE"`.  
    Lastly, type `$ git push origin <BRANCH-NAME>` to push all of your changes back to your remote repository.
    ##### Note : Do Not Make Changes in the Master branch
    
7. #### Click Create pull request to open a new pull request.
    Navigate back to your forked repository on GitHub.
    You can now see a "Create Pull Request" button on the main page.
    Click the "Pull requests" tab and select "New pull request".  
    Be sure to select the appropriate branch you want to merge from and to.  
    ![Create Pull Request](/images/choose-base-and-compare-branches.png)
    Finally, click "Create pull request" to create your pull request.
   
 
