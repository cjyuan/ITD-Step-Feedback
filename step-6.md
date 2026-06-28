# [Step 6](https://curriculum.codeyourfuture.io/itd/steps/six/#instructions)  

### [Acceptance Criteria](https://curriculum.codeyourfuture.io/itd/steps/six/#acceptance-criteria)
- You have successfully deployed your personal webpage from Step 4 using GitHub Pages.
- The URL of the deployed webpage includes your first name, last name, or both.
- The link to the deployed webpage has been submitted on the CYF Course Platform.

### Acceptable 
- They can satisfy the 2nd criteria if their GitHub username or repo name includes their first or last name. 

### Common Rejected Reasons

#### 1. The URL of the page does not include their first or last name
##### Feedback
> One of the acceptance criteria (https://itd.codeyourfuture.io/steps/six/#acceptance-criteria) has not yet been met:  
> - The URL of the deployed webpage includes your first name, last name, or both.
>
> Can you address this issue and resubmit your GitHub Pages link?

#### 2. They deployed the "wrong" page
Possible reasons: 
- They uploaded the `dist` folder (instead of the files inside)
- They uploaded the ZIP file instead of the files extracted from it.
- They did not name their HTML file `index.html`.

##### Feedback
> GitHub Pages requires your website files to be located in the repository’s **root** (**top-level**) folder.
>
> If an `index.html` file is not present in the root folder, GitHub Pages will instead display the `README.md` file by default.
>
> To deploy your site, move the contents of the dist folder into the root folder of your repository.
>
>
> Your website files are the files inside the "dist" sub-folder. You need to "move" them to the root folder of your repository.
> 
> You can "move" the files on GitHub by renaming them on GitHub, or you can upload those files to the top-level folder of your repository.



#### 3. They submitted a link to their GitHub repository instead of the link to their deployed page on GitHub Pages

> The link you submitted is not a link to your webpage on GitHub Pages.
>
> Please follow the instructions in "4. Create a repository for your website" and "5. Deploy your webpage on GitHub Pages" 
> to deploy your CodePen page to GitHub Pages. 

#### 4. The GitHub Repository does not contain an `index.html`
Your repository has been set up correctly for deployment on GitHub Pages.

At the moment, though, the page being displayed is the content of your `README.md` file rather than the webpage you created in CodePen.

Pleae review the instructions in section **"4. Create a repository for your website"** and follow them closely 
to download your webpage files from CodePen and upload them to your repository.

When the steps are completed properly, the top-level folder of your repository should contain the following files:
(1) `index.html`
(2) `style.css`









