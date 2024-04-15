<div align = "center">
<h1><img src = "https://github.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/blob/master/Emojis/Travel%20and%20places/Rocket.png" width="40" height="40">Getting Started With Creating a Pull Request</h1>
</div>


Welcome to the beginner's guide to creating a pull request (PR) on GitHub! Pull requests are a fundamental aspect of collaborating on GitHub, allowing you to propose changes to a repository. Follow these steps to create your first pull request:

## Step 1: Fork the Repository

Click on the **Fork** button in the upper right corner of this page. This will create a copy of this repository in your GitHub account.

## Step 2: Clone the Forked Repository

1. Open your forked repository on GitHub.
2. Click on the **Code** button and copy the repository URL.
3. Open your terminal or command prompt.
4. Use the `git clone` command followed by the repository URL to clone the repository to your local machine.

```bash
git clone <repository-url>
```

## Step 3: Create a New Branch
Create a new branch for your changes using the `git checkout` command.
```bash
git checkout -b <branch-name>
```

## Step 4: Make Changes
1. Make the necessary changes to the files in your local repository using a text editor or IDE.
2. Save your changes.

## Step 5: Commit Your Changes
1. Stage the changes you want to commit using the `git add` command.
```bash
git add .
```
2. Commit the staged changes with a descriptive commit message using the `git commit` command.
```bash
git commit -m "Your descriptive commit message here"
```

## Step 6: Push Changes to GitHub
Push your changes to your forked repository on GitHub using the `git push` command.
```bash
git push origin <branch-name>
```

## Step 7: Create a Pull Request
1. Visit your forked repository on GitHub.
2. Click on the **Compare & pull request** button next to the branch you just pushed.
3. Review the changes you made.
4. Click on the **Create pull request** button.
5. Provide a descriptive title and additional information about your pull request.
6. Click on the **Create pull request** button to submit your pull request.

<div align = "center">
  <h3><img src = "https://github.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/blob/master/Emojis/Activities/Party%20Popper.png" width="40" height="40">Congratulations! You've created your first pull request... Now, wait for the repository maintainer to review and merge your changes.</h3>
</div>
