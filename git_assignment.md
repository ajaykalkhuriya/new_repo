Initialize a directory as git repository.

Go into the directory containing the project.
Type git init.
Type git add to add all of the relevant files.
You’ll probably want to create a .gitignore file right away, to indicate all of the files you don’t want to track. Use git add .gitignore, too.
Type git commit.

Go to github.

Log in to your account.
Click the new repository button in the top-right. You’ll have an option there to initialize the repository with a README file, but I don’t.
Click the “Create repository” button.

$ git remote add origin git@github.com:username/new_repo
$ git push -u origin master