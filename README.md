# Fetch GitHub API

Functions to return all possible details which can be fetched from the GitHub API.

## Functions

The following functions are needed:

* `get_user_details()` - Returns the details of a user.
   - Input: username
   - Ouput (Return as object) : Name, Email, Bio, Location, Company, Avatar url, total followers, total following, total stars, array of organizations, account_created_at as date
   
* `get_repository_details()` - Returns the details of a repository.
   - Input: username, repository_name
   - Ouput (Return as object): All repository details in the api
   
* `get_commit_details()` - Returns the details of a commit.
   - Input: username, repository_name
   - Ouput (Return as object): All commit details in the api
   
* `get_issue_details()` - Returns the details of an issue.
   - Input: username, repository_name
   - Ouput (Return as object): All issue details in the api
   
* `get_pull_request_details()` - Returns the details of a pull request.
   - Input: username, repository_name
   - Ouput (Return as object): All pull request details in the api

## How to contribute

### 1. Fork the repository

The first step is to fork the repository to your own GitHub account. This will create a copy of the repository that you can make changes to.

To fork the repository, click on the **Fork** button in the top right corner of the repository page.

### 2. Clone the repository

Once you have forked the repository, you need to clone it to your local machine. This will create a copy of the repository on your computer that you can work on.

To clone the repository, open a terminal and run the following command:

```
git clone https://github.com/[your-username]/fetch-github-api.git
```

### 3. Create a new branch

Before you start making changes, you should create a new branch to work on. This will allow you to keep your changes separate from the main branch of the repository.

To create a new branch, run the following command:

```
git checkout -b <branch-name>
```

### 4. Make your changes

Now you can start making changes to the code. Please follow the coding style of the project, including indentation. If the project has tests, run them before you commit your changes.

### 5. Commit your changes

Once you have made your changes, you need to commit them to the repository. This will save your changes so that you can track them and revert them if necessary.

To commit your changes, run the following command:

```
git commit -m "Your commit message"
```

### 6. Push your changes to your fork

Once you have committed your changes, you need to push them to your fork on GitHub. This will make your changes available to you and other users who have forked the repository.

To push your changes, run the following command:

```
git push origin <branch-name>
```

### 7. Open a pull request

Once you have pushed your changes to your fork, you can open a pull request to merge your changes into the main branch of the repository.

To open a pull request, go to the **Pull requests** tab in the repository and click on the **New pull request** button.

In the pull request, you will need to provide a title and description for your changes. You can also add any additional information that you think is relevant.

Once you have submitted the pull request, we will review your changes and decide whether to merge them into the main branch.
