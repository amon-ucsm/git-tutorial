# To do list
- [Create new repo](#create-new-repository)
- [Creating commit](#creating-commit)
- [View history of changes](#view-history-of-changes)

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

## View history of changes ##
- View log
    - View full log
        ```
        git log
        ```
    - View with one line
        ```
        git log --oneline
        ```
- View specific
    - Change auther name and date & time
        ```
        git log --oneline --auther="git_user_name" --since="2025-08-03 14:19:27"
        ```