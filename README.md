# Exercise 1

This is the first exercise for the course [Deep Learning](https://lehre.idh.uni-koeln.de/lehrveranstaltungen/wintersemester-2024-2025/deep-learning/).

First, create an account on [GitHub](https://github.com). If you have an existing GitHub account, you may use it as well.

Send me an email to janis.pagel@uni-koeln.de with your GitHub account name, your real name and your matriculation number, so that I know that it is your account.

Go to http://compute.spinfo.uni-koeln.de an create an account there. Open the terminal by clicking on File > New > Terminal. Create an SSH key following [this guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent). Add this SSH key to your GitHub account following [this guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account).
Next, add your name and email to the git config following [this](https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git) and [this guide](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address). The email you choose should also be set in your GitHub account.

Clone [this repository](https://github.com/IDH-Cologne-Deep-Learning-2024/Exercise-1) by running

```
$ git clone git@github.com:IDH-Cologne-Deep-Learning-2024/Exercise-1.git
```

Go into the directory `Exercise-1` and create a new branch that is called after your GitHub username. Switch to that branch. Create a new file called `shakespeare-sonnet-1.txt` and copy into it the following text:

```
From fairest creatures we desire increase,
That thereby beauty’s rose might never die,
But as the riper should by time decrease,
His tender heir mught bear his memeory:
But thou, contracted to thine own bright eyes,
Feed’st thy light’st flame with self-substantial fuel,
Making a famine where abundance lies,
Thyself thy foe, to thy sweet self too cruel.
Thou that art now the world’s fresh ornament
And only herald to the gaudy spring,
Within thine own bud buriest thy content
And, tender churl, makest waste in niggarding.
Pity the world, or else this glutton be,
To eat the world’s due, by the grave and thee.
```

Save the file, add it to git's tracking and create a commit for the file. Now, add the author's name (Wiliam Shakespeare) at the top of the file. Save it, add the changes to git and create another commit.

Look at the log of your commits and save its output into a new file `log.txt`. Add and commit this file as well.

Lastly, push your changes to the branch with the name of your GitHub username.
In GitHub, go to https://github.com/IDH-Cologne-Deep-Learning-2024/Exercise-1 and switch to your branch. Make sure that everything worked correctly.
