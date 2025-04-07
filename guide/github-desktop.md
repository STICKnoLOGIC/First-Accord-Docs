## Github Desktop
Reading articles and watching tutorials is helpful, but hands-on experience is best. This project will guide you through making your first contribution. Stay relaxed, and you'll learn better. Follow the steps below to get started. It will be fun!

If you don't have GitHub Desktop on your device, [install it](https://desktop.github.com/).

## Fork this repository

<img width="300" src="/assets/fork.png" alt="fork this repository" />

Click the fork button in the upper right corner of [this page](https://github.com/STICKnoLOGIC/first-accord) to fork the repository. A clone of this repository will be created in your account as a result.

## Clone the repository

Now, clone the repository you just forked to your machine.

 > [!warning|label:Important]
 > __DO NOT CLONE THE ORIGINAL REPO__. Clone your forked repository.

To clone the repo, click on "Clone or Download" and then click on "Open in Desktop".

<img src="/assets/desktop/clone.png" alt="clone this repository" />

A pop up window will open. Click on "Open GitHubDesktop.exe".

<img src="/assets/desktop/open-app.png" alt="open desktop app" />

After you click on "Open GitHubDesktop.exe" the contents will be downloaded to your computer.

<img src="/assets/desktop/app-open.png" alt="open app" />

Now you have copied the contents of the First Accord repository in github to your computer.

## Create a Branch

Now, create a new branch by clicking on the "Current branch" icon at the top and then click on "New branch".

<img src="/assets/desktop/app-new-branch.png" alt="create branch" />

Name your branch. For example, `"sticknologic-name-branch"`.

<img src="/assets/desktop/app-name-branch.png" alt="name branch" />

Then click on `Create branch` button.

## Make necessary changes and commit those changes

 Go to the `contributors` Folder/Directory and copy the content of `__TEMPLATES__.json` (the template consists of essential/required parameters in JSON structure. To know more, [visit JSON Structure](json-structure))

Now in `contributors` Directory, Create a json file `this-is-you.json`(where `this-is-you` is your Github username, in my case its `sticknologic.json`), Open the created json file in a text editor/IDE you prefer and paste the content you copied from the `__TEMPLATE__.json`, edit the json file([click here to know more about Json Structure](json-structure)). Now, save the file.

You can see that there are changes to contributors Folder as you create your JSON file and they have been added to the Github Desktop.

<img src="/assets/desktop/status.png" alt="check status" />

Now commit those changes:

Write the message "Add `<your-name>` to Contributors list" in the _summary_ field.

Replace `<your-name>` with your name.

Click on the button that says `Commit to main`.

<img src="/assets/desktop/commit1.png" alt="commit your changes" />

At the bottom, you can see that the commit has been created.

<img src="/assets/desktop/commit2.png" alt="commit your changes" />

## Push changes to github

Click on File->Options and sign-in to Github.com. Type in your Github username and password.

<img src="/assets/desktop/sign-in.png" alt="log-in to Github" />

Click the `Push origin` button.

<img src="/assets/desktop/push.png" alt="push your changes" />

## Submit your changes for review

If you go to your repository on github, you'll see `Compare & pull request` button. click on that button.

<img src="/assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img src="/assets/submit-pull-request.png" alt="submit pull request" />

I'll be merging all of your modifications into the project's main branch shortly. Once the changes have been merged, you will receive an email notification.

## Where to go from here?

Congratulations! You have successfully completed the standard workflow: `fork -> clone -> edit -> pull request` that you will frequently encounter as a contributor.

You are welcome to join our community or group if you need assistance or have any questions.

[![Join Telegram Group](https://img.shields.io/badge/Telegram-26A5E4?style=flat&logo=telegram&logoColor=white)](https://t.me/+D51ix1qENBs0ZWRI)
[![Join Discord Server](https://dcbadge.limes.pink/api/server/https://discord.gg/zkspfFwqDg?style=flat)](https://discord.com)

Let's help you get started with contributing to other projects. I recommend beginning with [First Contribution](https://github.com/firstcontributions/first-contributions). This project was heavily inspired by it, just so you know!

## Tutorials Using Other Tools
| <img alt="cli" src="https://raw.githubusercontent.com/felixse/FluentTerminal/refs/heads/master/Icons/Icon_no_margin.png" width="100"> | <img alt="VS Code" src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Visual_Studio_Code_1.35_icon.png" width=100> | <i class="fa-solid fab fa-chrome fa-6x" style="color:lightblue"></i> |
| :------------------: | :------------------: | :------------------: |
| [Command Line Interface](guide/github-cli) | [Visual Studio Code](guide/github-vscode) | [Browser](guide/github-browser)


