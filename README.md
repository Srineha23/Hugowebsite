# Hugowebsite
##1.Set up your repository:
Ensure your HTML/CSS website code is hosted in a Git repository. Make sure you have Hugo installed locally and your website can be built successfully using Hugo commands.
##2.Create a GitHub Actions workflow:
Add a workflow file (e.g., .github/workflows/build1.yml) to your repository.

###
This workflow:

Triggers on any push event to any branch.
Checks out the code.
Sets up Hugo.
Builds the website using Hugo with minification enabled.
Archives the built website as an artifact.
###

