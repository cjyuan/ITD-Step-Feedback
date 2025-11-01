# [Step 5](https://itd.codeyourfuture.io/steps/five/#instructions)  

### [Acceptance Criteria](https://itd.codeyourfuture.io/steps/five/#acceptance-criteria)
- You have successfully deployed your personal webpage from Step 4 using GitHub Pages.
- The URL of the deployed webpage includes your first name, last name, or both.
- The link to the deployed webpage has been submitted on the CYF Course Platform.

### Acceptable 
- They can satisfy the 2nd criteria if their GitHub username or repo name includes their first or last name. 

### Common Rejected Reasons

#### 1. The URL of the page does not include their first or last name
##### Feedback
> One of the acceptance criteria (https://itd.codeyourfuture.io/steps/five/#acceptance-criteria) has not yet been met:  
> - The URL of the deployed webpage includes your first name, last name, or both.
>
> Can you address this issue and resubmit your GitHub Pages link?

#### 2. The deployed the "wrong" page
Possible reasons: 
- They uploaded the `dist` folder (instead of the files inside)
- They uploaded the ZIP file instead of the files extracted from it.
- They did not name their HTML file `index.html`.

##### Feedback
> GitHub Pages requires your website files to be located in the repository’s **root** (**top-level**) folder.
>
> To deploy your site, move the contents of the dist folder into the root folder of your repository.
>
> If an `index.html` file is not present in the root folder, GitHub Pages will instead display the `README.md` file by default.
