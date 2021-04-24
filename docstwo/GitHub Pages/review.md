---
layout: default
title: Collaborating - review online
parent: GitHub Pages
nav_order: 4
---
 
# Collaborating: review online  
The GitHub flow allows us to propose and review changes in pull requests. To do so, you need to add collaborators who are granted push access to a shared repository. They create topic branches when changes need to be made. Pull requests initiate code review and general discussion about the changes before they are merged into the main branch.

## How to share file with the reviewer?


1. Go to [this website](https://github.com//) and log in.
2. Open your repository.
3. Click **Settings** on the right.
4. Go to **Branches** on the left navigation panel.
5. Click **Add rule** in **branch protection rules**.
6. Provide a name of the branch and check **Require pull request reviews before merging** checkbox.  
   ![rule](/assets/images/rule.png)
7. Click **Create**.
8. Go to **Manage access** on the left navigation panel.
9.  Provide your password and click **Confirm password**.
10. Click **Invite a collaborator**.
11. Search for collaborator in the search bar.
12. Click **Add (user name) to this repository**.


## How to review the shared file?

1. Open the email you received inviting you to collaborate.  
    ![invite](/assets/images/invite.png)
2. Accept the invitation and click on the highlighted link to open the repository in GitHub Pages.
3. In this repository, click **Code** to clone the repository and **Open with GitHub Desktop**.  
   ![clone](/assets/images/clone.png)
4. Open GitHub Desktop.
5. Click **Branch** on the navigation bar, and add **New Branch**.  
   ![branch](/assets/images/branch.png)
6. Provide the name of the branch and click **Create branch**.  
    ![createbranch](/assets/images/createbranch.png)
7. In GitHub Desktop, select **Open in Visual Studio Code**.  
   ![openin](/assets/images/openin.png)
8. Apply the changes in the file in Visual Studio Code.
9.  Save the applied changes.
10. Go to GitHub Desktop.
11. Open **Changes** tab and verify if the file contains the applied changes.
12. Write a summary in the **Summary** field about the change you made to the file. 
13. Click **Commit to [branch name]**.
14. Click **Push origin**.
15. Click **Create pull request**.
16. You are now moved to github.com page. 
17. In **Open a pull request** window, Use the base branch dropdown menu to select the branch you want to merge your changes into, then use the compare branch drop-down menu to choose the branch you made your changes in.
   ![compare](/assets/images/compare.png)
18. Provide a description for your pull request.
19. Click on the gear icon on the right in **Reviewers** section and assign a person who will review the applied changes.  
   ![reviewers](/assets/images/reviewers.png)
20. Click **Create pull request**.


## How to review the changes made by reviewer?

1. Open the pull request either by clicking the link on your email or:
   - Go to the repository.
   - Open **Pull requests** tab.  
   ![pull](/assets/images/pull.png)
   - Open the file.
2. Go to **Files changed** tab and review the applied changes.  
   ![fileschanged](/assets/images/fileschanged.png)
3. Click **Review changes** on the right. You have three options:  
   ![review](/assets/images/review.png)
    - Select **Comment** to leave general feedback without approving the changes or requesting additional changes.
    - Select **Approve** to submit your feedback and approve merging the changes.
    - Select **Request changes** to submit feedback that must be addressed before the pull request can be merged.
4. If the changes are approved, select **Merge pull request**.  
   ![mergepull](/assets/images/mergepull.png)
5. Select **Confirm merge**.  
   ![confirmmerge](/assets/images/confirmmerge.png)
6. After merging request is done and the changed content is added to your file in the repository, you can delete branch created during the process.