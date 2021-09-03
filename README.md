# project-2

## Overview

## How I got here?

```
# Create the 'project-2' directory
mkdir project-2

# Move into the 'project-2' directory
cd project-2

# Call the express-generator tool
npx express-generator --view=hbs

# Initialise a local git repository in the 'project-2' directory
git init

# Stage all the changes in the 'project-2' directory, which will let us commit them next
git add .

# Commit our generated files
git commit -m "Initial commit"

# (git init printed some warning about master changing, so let's rename it to development)
git branch -m development

# Create your project-2 repo on GitHub, so we can push our changes to the remote repo
gh repo create

# Push our branch to GitHub
git push origin development
```

:sparkles: **Note:** If `gh` is not installed, you can do `brew install github/gh/gh` to install it. It's a great useful tool for using GitHub from the command line! :sparkles:
