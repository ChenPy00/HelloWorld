# HelloWorld

As a record of the first code upload to GitHub.

## Preparation

1. If using shh to upload, please ensure that there is an ssh key under the GitHub user

2. Please ensure that you can connect to GitHub normally and use the instruct

`ssh -T git@github.com`

## Upload instructions

1. Using git to initialize repository

   `git init`

2. Add files

   `git add ./.`

3. Submit the file to the repository.

   `git commit -m "first commit"`

4. Replace branch name

   - Master is the default name in Git, while main is the default name in GitHub. Therefore, if you want to replace the branch name, please follow the below:

     `git branch -m master main`

   - if not, please follow the below:

     `git branch -M master`

5. Remote to the project

   `git remote add origin https://github.com/ChenPy00/HelloWorld.git`

6. Push the code from the local warehouse to Github

	`git push -u origin master # or main`


