
### Fork The First-Accord repository
<img  width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

[Fork](https://github.com/STICKnoLOGIC/First-Accord/fork) the First Accord repository by clicking on the fork button on the top of [this page](https://github.com/STICKnoLOGIC/First-Accord/).
This will create a copy of this repository in your account.
<br>
### Cloning the Repository

<img  width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button, then on SSH tab and then click the _copy to clipboard_ icon.

<img  width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

Open a terminal and run the following git command:

```bash
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.


For example:

```bash
git clone git@github.com:this-is-you/first-contributions.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

### Create a branch

Change to the repository directory on your computer (if you are not already there):

```bash
cd first-contributions
```

Now create a branch using the `git switch` command:

```bash
git switch -c your-new-branch-name
```

For example:

```bash
git switch -c add-alonzo-church
```

<details>
<summary> <strong>If you get any errors using git switch, click here:</strong> </summary>

If the error message "Git: `switch` is not a git command. See `git –help`" appears, it's likely because you're using an older version of git.

In this case, try to use `git checkout` instead:

```bash
git checkout -b your-new-branch-name
```

</details>


<!-- TODO create guide using CLI -->