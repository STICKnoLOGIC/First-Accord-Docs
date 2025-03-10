## Visual Studio Code Guide

If you don't have Visual Studio Code on your device, [install it](https://code.visualstudio.com/download).

 > [!NOTE|label:Notice:]
 > This tutorial was created with Visual Studio Code (Version 1.97.2) on a Windows 10 system. In a subsequent part of this tutorial, we will utilize some keyboard shortcuts. These might vary on different operating systems (macOS/Linux) and keyboard languages (UK, DE, etc.). You can access your list of shortcuts by typing "shortcut" in the Command Palette.

## Fork this repository

<img width="300" src="/assets/fork.png" alt="fork repository" />

Click the fork button in the upper right corner of [this page](https://github.com/STICKnoLOGIC/first-accord) to fork the repository. A clone of this repository will be created in your account as a result.

## Clone your repository

<img width="300" src="/assets/cli/clone.png" alt="clone repository" />

Now, clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click the code button, then on the HTTPS tab, and then click the _copy to clipboard_ icon.

 > [!warning|label:Important]
 > __DO NOT CLONE THE ORIGINAL REPO__. Clone your forked repository.

Next, launch Visual Studio Code. The VS Code welcome page will appear. From that point, press `F1` to display the bar illustrated below. Observe that there is already a `>` (greater than) symbol in the text box. You can access the input prompt by pressing `CTRL-P` and then entering the `>` character.

<img src="/assets/vscode/clone.png" alt="Clone via vscode" />

You might observe that a few unclear commands are already mentioned below. These are the commands I have used recently. Therefore, simply disregard them.

<img src="/assets/vscode/clone1.png" alt="Clone repo" />

Now enter `git clone`, just `git` or `clone` (it functions like a search).

Choose the option `Git: Clone` and hit `Enter`.

<img src="/assets/vscode/clone2.png" alt="Paste URL" />

Enter the URL of your repository and press `Enter`. This will launch a File Explorer allowing you to select the location for the Git repository's storage.

for Example:
    https://github.com/this-is-you/first-accord.git

Where `this-is-you` is your Github username.

> [!warning|label:Important:]
> Ensure it is the forked repo and not the original; otherwise, it won't function

<img src="/assets/vscode/clone3.png" alt="Status popup" />

You should see a status popup on the bottom right of Visual Studio Code. After it has finished, you can open up the cloned repository (now a folder on your machine) using the buttons in the dialog.

## Make necessary changes

Go to the `contributors` Folder/Directory and copy the content of `__TEMPLATES__.json` (the template consists of essential/required parameters in JSON structure. To know more, [visit JSON Structure](json-structure))

Now in `contributors` Directory, Create a json file `this-is-you.json`(where `this-is-you` is your Github username, in my case its `sticknologic.json`), Open the created json file in a text editor/IDE you prefer and paste the content you copied from the `__TEMPLATE__.json`, edit the json file([click here to know more about Json Structure](json-structure)). Now, save the file.

<img src="/assets/vscode/changes.png" alt="Add your contribution" />

## Commit & Push changes to GitHub

On the left side of VS Code, there is a menu featuring 5 visible icons. Choose the icon for version control/source control. (Quick Key: Ctrl + Shift + G)

<img src="/assets/vscode/commit.png" alt="Commit" />

The file explorer shows all files that were modified since the last commit. By placing the cursor over the files and pressing the `+` (plus), the files are prepared for staging.

<img src="/assets/vscode/commit1.png" alt="Stashed Files">

Enter text in the field above the explorer and hit the checkmark. The modifications are now saved to your local version. The modifications need to be sent back to GitHub now.

<img src="/assets/vscode/push.png" alt="Stashed Files">

Tap the three-dot icon to access the menu, and then choose the `Publish Branch` option. This should initiate a prompt for you to enter your GitHub credentials.

<img src="/assets/vscode/gh-auth.png" alt="gh auth">

## Submit your changes for review

At this stage, you have finished your modification, but it remains only in your repository. This phase will guide you in submitting a request to the administrator of the primary repository to integrate your modification.

In your GitHub repository, you'll find the `Compare & pull request` button adjacent to the notification for the new branch. Press that button.

<img src="/assets/compare-and-pull.png" alt="create a pr" />

Now submit the pull request.

<img src="/assets/submit-pull-request.png" alt="submit pr" />

I'll be merging all of your modifications into the project's main branch shortly. Once the changes have been merged, you will receive an email notification. 

## Where to go from here?

Congratulations! You have successfully completed the standard workflow: `fork -> clone -> edit -> pull request` that you will frequently encounter as a contributor.

You are welcome to join our community or group if you need assistance or have any questions.

[![Join Telegram Group](https://img.shields.io/badge/Telegram-26A5E4?style=flat&logo=telegram&logoColor=white)](https://t.me/+D51ix1qENBs0ZWRI)
[![Join Discord Server](https://dcbadge.limes.pink/api/server/https://discord.gg/zkspfFwqDg?style=flat)](https://discord.com)

Let's help you get started with contributing to other projects. I recommend beginning with [First Contribution](https://github.com/firstcontributions/first-contributions). This project was heavily inspired by it, just so you know!

## Tutorials Using Other Tools
| <img alt="cli" src="https://raw.githubusercontent.com/felixse/FluentTerminal/refs/heads/master/Icons/Icon_no_margin.png" width="100"> | <img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"> | <i class="fa-solid fab fa-chrome fa-6x" style="color:lightblue"></i> |
| :------------------: | :------------------: | :------------------: |  
| [Command Line Interface](guide/github-cli) | [GitHub Desktop](guide/github-desktop) |[Browser](guide/github-browser)

