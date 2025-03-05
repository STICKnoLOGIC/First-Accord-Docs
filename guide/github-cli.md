
# CLI Guide
Welcome! In this section, we will help you `step-by-step` on how to contribute to [First Accord]('https://github.com/STICKnoLOGIC/First-Accord') using the CLI or Command Line

If you dont have git in your device, [Install the git](https://github.com/git-guides/install-git).

### Fork The First-Accord repository
<img  width="300" src="./assets/fork.png" alt="fork this repository" />

[Fork](https://github.com/STICKnoLOGIC/First-Accord/fork) the First Accord repository by clicking the fork button at the top of [this page](https://github.com/STICKnoLOGIC/First-Accord/). This will create a copy of this repository in your account.
<br>
### Cloning the Repository

<img  width="300" src="./assets/cli/clone.png" alt="clone this repository" />

Now, clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click the code button, then on the HTTPS tab, and then click the _copy to clipboard_ icon.

<img  width="300" src="./assets/cli/copy-to-clipboard.png" alt="copy URL to clipboard" />

Open a terminal and run the following git command:

```bash
git clone "url you just copied"
```

Where `"url you just copied"` (without quotation marks) is the URL to this repository (your fork of this project). See the previous steps to obtain the URL.

For example:

```bash
git clone https://www.github.com/this-is-you/first-accord.git
```

Where `this-is-you` is your GitHub username. Here, you're copying the contents of the first-contributions repository on GitHub to your computer.

## Make necessary changes and commit those changes
 Go to the `contributors` Folder/Directory and copy the content of `__TEMPLATES__.json` (the template consists of essential/required parameters in JSON structure. To know more, [visit JSON Structure](json-structure))

```bash
cd first-accord/contributors
```

Now in `contributors` Directory, Create a json file `this-is-you.json`(where `this-is-you` is your Github username), Open the created json file in a text editor and paste the content you copied from the `__TEMPLATE__.json`, edit the json file([click here to know more about Json Structure](json-structure)). Now, save the file.


If you go to the project directory and execute the command `git status`, you'll see there are changes.

<img width="450" src="./assets/cli/git-status.png" alt="git status" />

Add those changes to the branch you just created using the `git add` command:

```bash
git add this-is-you.json
```
Where `this-is-you` is your GitHub username.

Now commit those changes using the `git commit` command:

```bash
git commit -m "Add your-name to Contributors list"
```

replacing `your-name` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```bash
git push -u origin
```

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img src="./assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img src="./assets/submit-pull-request.png" alt="submit pull request" />

I'll be merging all of your modifications into the project's main branch shortly. Once the changes have been merged, you will receive an email notification. 

## Where to go from here?

Congratulations! You have successfully completed the standard workflow: `fork -> clone -> edit -> pull request` that you will frequently encounter as a contributor.

You are welcome to join our community or group if you need assistance or have any questions.

[![Join Telegram Group](https://img.shields.io/badge/Telegram-26A5E4?style=flat&logo=telegram&logoColor=white)](https://t.me/+D51ix1qENBs0ZWRI)
[![Join Discord Server](https://dcbadge.limes.pink/api/server/https://discord.gg/zkspfFwqDg?style=flat)](https://discord.com)

Let's help you get started with contributing to other projects. I recommend beginning with [First Contribution](https://github.com/firstcontributions/first-contributions). This project was heavily inspired by it, just so you know!

## Tutorials Using Other Tools
| <img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"> | <img alt="VS Code" src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Visual_Studio_Code_1.35_icon.png" width=100></a> | <a href="gui-tool-tutorials/sourcetree-macos-tutorial.md"><img alt="Sourcetree App" src="https://wac-cdn.atlassian.com/dam/jcr:81b15cde-be2e-4f4a-8af7-9436f4a1b431/Sourcetree-icon-blue.svg" width=100></a> |
| :------------------: | :------------------: | :------------------: | 
| [GitHub Desktop](guide/github-desktop) | [Visual Studio Code](docs/gui-tool-tutorials/github-vscode) | [Github WebPage](guide/github-webpage)