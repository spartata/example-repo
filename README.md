# Example Repository
This is a sample repo, Hello world!

Code change to existing markdown file!

GIT COMMANDS USED:

-- gets repo current status\
git status
\
-- review file diferences\
git diff README.md
\
-- wrap up file and prepare to commit - put in stage state i.e. stage box is all files that will be committed\
git add README.md
\
-- commit all staged files in your local repo\
git commit -m "README Markdown file commit"
\
-- push in main repo\
git push origin main

[comment]: <> (This is a comment, it will not be included)
# to unstage
git restore --staged index.html
# to discard changes in working directory
git restore README.md