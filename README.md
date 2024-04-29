# Hugowebsite
###
1.Set up your repository:
Ensure your HTML/CSS website code is hosted in a Git repository. Make sure you have Hugo installed locally and your website can be built successfully using Hugo commands.
###
2.Create a GitHub Actions workflow:
Add a workflow file (e.g., .github/workflows/build1.yml) to your repository.

###
This workflow:
###
i.Triggers on any push event to any branch.
###
ii.Checks out the code.
###
iii.Sets up Hugo.
###
iv.Builds the website using Hugo with minification enabled.
###
v.Archives the built website as an artifact.
###

