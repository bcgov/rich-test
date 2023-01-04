## Tips for R based workflow.

### Use Github for version control (this avoids having directories full of copies of the same file.)

-  Join BCGov GitHub Organization: https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Gov-Org-HowTo/Joining-the-BCGov-on-GitHub.md 
-  Create a new repository at https://github.com/bcgov by hitting the green button `New`. 
-  Choose a meaningful name for your project, and check the box to add a readme.md file to your project and then click the green `create repository` button.
- Click on the green button `code` and then copy the url of your repository.

### Use Rstudio for your IDE.

- Open Rstudio, click File>New Project>Version Control>Git and then paste the repository's url and choose a directory name and location then click create project.
- at the prompt type `remotes::install_github("bcgov/bcgovr")` You might need to install.packages("remotes") first.
- at the prompt type `library(bcgovr)` and then type `create_bcgov_project()`

