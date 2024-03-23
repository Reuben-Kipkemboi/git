# Steps

1. Create a git repository. You can initialize Readme file with it and a lIcense also.
2. Locally create a folder/repository using the following commands:
- `mkdir PLP` - Creates a folder called PLP.
- Inside the folder create a file by using the command `touch index.txt`
- Now open the folder using your text editor for this case I will use  `code .` to open it in Vscode.
3. Initialize git locally.
 -  `git init`
3. Connect to github remote repository .
- `git remote add origin <repository-url>`
4. If you created your repo with readme file you have to pull changes to your local repository
 - `git pull origin master/main`
5. Stage your changes
 - `git add .`
6. Commit the files/Changes.
 - `git commit -m"commit message"`
7. Push the changes.
- `git push -u origin master/main` `-u` flag used to set upstream
