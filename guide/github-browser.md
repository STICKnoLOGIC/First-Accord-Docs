# Browser Guide

Contributing to a GitHub project for the first time might seem a little intimidating, but don't worry—it's simpler than you think! Whether you're fixing a typo or adding a cool new feature, every contribution matters and helps make projects better. In this quick and friendly guide, I'll walk you through the steps to make your first contribution using a browser. Let's jump in and get you started on your GitHub journey!

## Fork The First-Accord repository
<img  width="300" src="/assets/fork.png" alt="fork this repository" />

[Fork](https://github.com/STICKnoLOGIC/First-Accord/fork) the First Accord repository by clicking the fork button at the top of [this page](https://github.com/STICKnoLOGIC/First-Accord/). This will create a copy of this repository in your account.

## Create a Branch
Copy the following link and surf it in your Browser:

`
https://GitHub.com/github-username/First-Accord/branches
`

Where `github-username` is your GitHub Username.

For Example: (my Github Username is `STICKnoLOGIC`)

`
https://GitHub.com/STICKnoLOGIC/First-Accord/branches
`

<img src="/assets/web/branch.png" alt="create branch">

Then click the `New branch` button at the top-right

<img src="/assets/web/branch2.png" alt="name branch">

and type in the name of your new branch, for example `sticknologic-name-branch`, make sure you select `main` as the source.

Click the `Create new Branch` and a branch will be created.


## Make necessary changes and commit those changes

 Go to the `contributors` Folder/Directory and copy the content of `__TEMPLATES__.json` (the template consists of essential/required parameters in JSON structure. To know more, [visit JSON Structure](json-structure)).

<img src="/assets/web/create.png" alt="create file">

Navigate back to the repository's main page. Click on the `Add file` button, then select `Create new file`.

<img src="/assets/web/add-file-name.png" alt="add file name">

Enter `contributors/your-username.json` in the field, replacing `your-username` with your actual GitHub username (for my case, `sticknologic`).

> [!NOTE]
> Don't worry, once you type or enter `/` in that field, it will automatically create a new subfolder or use an existing one.

<img src="/assets/web/edit.png" alt="edit file">

In the text area, paste the content copied from `__TEMPLATE__.json` and edit it as needed. [Visit the JSON structure](json-structure) to learn more about the accepted values and keys in your JSON file.

<img src="/assets/web/commit.png" alt="commit file">

After editing the JSON, commit your changes by clicking the `Commit changes...` button located at the top right.

<img src="/assets/web/save.png" alt="save file">

Enter `Add your username as a contributor` as your commit message, replacing "your username" with your GitHub username. Then confirm to save or change the file.

## Submit your changes for review

If you go to your repository on github, you'll see `Compare & pull request` button. click on that button.

<img src="/assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img src="/assets/submit-pull-request.png" alt="submit pull request" />

I'll be merging all of your modifications into the project's main branch shortly. Once the changes have been merged, you will receive an email notification.

## Where to go from here?

Congratulations! You have successfully completed the standard workflow: `fork -> edit -> pull request` using your Browser that you will frequently encountser as a contributor.

You are welcome to join our community or group if you need assistance or have any questions.

[![Join Telegram Group](https://img.shields.io/badge/Telegram-26A5E4?style=flat&logo=telegram&logoColor=white)](https://t.me/+D51ix1qENBs0ZWRI)
[![Join Discord Server](https://dcbadge.limes.pink/api/server/https://discord.gg/zkspfFwqDg?style=flat)](https://discord.com)

Let's help you get started with contributing to other projects. I recommend beginning with [First Contribution](https://github.com/firstcontributions/first-contributions). This project was heavily inspired by it, just so you know!

## Tutorials Using Other Tools
| <img alt="cli" src="https://raw.githubusercontent.com/felixse/FluentTerminal/refs/heads/master/Icons/Icon_no_margin.png" width="100"> | <img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"> | <img alt="VS Code" src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Visual_Studio_Code_1.35_icon.png" width=100> |
| :------------------: | :------------------: | :------------------: |
| [Command Line Interface](guide/github-cli) | [GitHub Desktop](guide/github-desktop) | [Visual Studio Code](docs/gui-tool-tutorials/github-vscode)