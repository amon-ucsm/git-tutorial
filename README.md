# To do list
- [Create new repo](#create-new-repository)
- [Creating commit](#creating-commit)

## Create new repository ##
- Checking git version
    ```
    git --version
    ``` 
- Configure git
    ```
    git config --global user.name "git_user_name"
    ```
    ```
    git config --global user.email "git_user@mail"
- Initalize git
    ```
    git init
    ```
    You will see the output like this ``Initialized empty Git repository in PATH/TO/.git/``
- Checking status
    ```
    git status
    ```
- Deleting it
    ```
    rm -rf .git
    ```

## Creating commit ##
- Adding file and folder // Adding all file and folder
    ```
    git add .
    ```
- Adding specific file and folder //This is example of adding README.md file
    ```
    git add README.md
    ```
- Commiting
    ```
    git commit -m "Add any commit here"
    ```

