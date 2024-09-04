# Test Assistant Repo

This is a test repository for verifying the skills of an assistant.

## Table of Contents
- [Description](#description)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description
This repository is created to evaluate the assistant's ability to use Git, VSCode, and Markdown.

## Installation Instructions
1. Clone the repository:
    ```bash
    git clone https://github.com/fimbifoi/test-assistant-repo.git
    ```
2. Navigate to the repository directory:
    ```bash
    cd test-assistant-repo
    ```
3. Install dependencies:
    ```bash
    npm install
    ```

## Usage
To start the React application, use the following command:
```bash
npm start
```

## Contributing
1. Navigate to:

[test-assistant-repo](https://github.com/fimbifoi/test-assistant-repo)

2. In the top-right corner of the page, click Fork.
![Image on Forking a repository](https://docs.github.com/assets/cb-34352/mw-1440/images/help/repository/fork-button.webp)

3. Under "Owner," select the dropdown menu and click an owner for the forked repository.

**_Note_**

_If your username is grayed out, it's because the fork already exists. Instead, you should bring your existing fork up to date. For more information, see "Syncing a fork."_

4. By default, forks are named the same as their upstream repositories. Optionally, to further distinguish your fork, in the "test-assistant-repo" field, type a name.

5. Click Create fork.

6. Working on repository
**Cloning a fork**
You've successfully forked the "test-assistant-repo" repository, but so far, it only exists on GitHub. To be able to work on the project, you will need to clone it to your computer.

You can clone your fork with the command line, or GitHub Desktop.

To learn more about GitHub CLI, see  [GitHub CLI](https://docs.github.com/en/github-cli/github-cli/about-github-cli)

To create a clone of your fork, use the --clone flag.

```bash
gh repo fork test-assistant-repo --clone=true
```
**Creating a branch to work on**

Before making changes to the project, you should create a new branch and check it out. By keeping changes in their own branch, you follow GitHub Flow and ensure that it will be easier to contribute to the same project again in the future. For more information, see "GitHub flow."

```bash
git branch BRANCH-YourUsername
```
```bash
git checkout BRANCH-YourUsername
```
**Making and pushing changes**

Go ahead and make a few changes to the project using your favorite text editor

When you're ready to submit your changes, stage and commit your changes. git add . tells Git that you want to include all of your changes in the next commit. git commit takes a snapshot of those changes.

```bash
git add .
```
```bash
git commit -m "a short description of the change"
```

When you stage and commit files, you essentially tell Git, "Okay, take a snapshot of my changes!" You can continue to make more changes, and take more commit snapshots.

Right now, your changes only exist locally. When you're ready to push your changes up to GitHub, push your changes to the remote.

```bash
git push
```

**Making a pull request**

At last, you're ready to propose changes into the main project! This is the final step in producing a fork of someone else's project, and arguably the most important. If you've made a change that you feel would benefit the community as a whole, you should definitely consider contributing back.

To do so, head on over to the repository on GitHub where your project lives. For this example, it would be at `https://github.com/<your_username>/test-assistant-repo`. You'll see a banner indicating that your branch is one commit ahead of octocat:main. Click Contribute and then Open a pull request.

GitHub will bring you to a page that shows the differences between your fork and the octocat/Spoon-Knife repository. Click Create pull request.

GitHub will bring you to a page where you can enter a title and a description of your changes. It's important to provide as much useful information and a rationale for why you're making this pull request in the first place. The project owner needs to be able to determine whether your change is as useful to everyone as you think it is. Finally, click Create pull request.


## License

[License](https://github.com/fimbifoi/test-assistant-repo/blob/main/LICENSE)