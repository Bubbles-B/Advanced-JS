…or create a new repository on the command line
echo "# Advanced-JS" >> README.md

# This command sets up a new Git repository in your current folder, creating a hidden .git directory. This .git folder is where Git stores the repository's history.
git init

# git add moves the specified file into the "index."
git add README.md (git add .)

# git commit takes the added changes and saves them in the repository's history.
git commit -m "first commit"

# git branch -M main renames the current branch to "main."
git branch -M main

# This command links your local Git repository to a remote repository with the alias "origin"
git remote add origin https://github.com/Bubbles-B/Advanced-JS.git

# git push -u origin main uploads your local "main" branch to the "origin" remote repository on GitHub. 
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/Bubbles-B/Advanced-JS.git
git branch -M main
git push -u origin main

access key: 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