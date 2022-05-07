# Algebra

![image](https://user-images.githubusercontent.com/67740644/167239629-b5d3731f-51de-4c37-9b40-89e6369ec4b2.png)

# Welcome to Open Source Community
The open source community is diverse and highly motivated. We're sure you'll be able to find someone who can help you (or that you can help) no matter what your interests are.

Whether it's development or advocacy, open source software and other collaborative projects benefit through, and because of, community. Unlike traditional projects that require physical resources, sharing economies are generally only hindered by the number of people contributing to an effort and their ability to acquire and share knowledge.

Our development efforts generate resources for collaborative organizations, to help create and maintain communication within and among open source projects; motivate and efficiently organize groups of remote individuals, and; cultivate an open ethos where the principles and practices of open source can foster collaboration co-creation and community.

# Contributing

If you want to contribute to a project and make it better, your help is very welcome. Contributing is also a great way to learn more about social coding on Github, new technologies and and their ecosystems and how to make constructive, helpful bug reports, feature requests and the noblest of all contributions: a good, clean pull request.

# Forking a repository

This tutorial uses the Spoon-Knife project, a test repository that's hosted on GitHub.com that lets you test the fork and pull request workflow.

    Navigate to the Spoon-Knife project at https://github.com/octocat/Spoon-Knife.
    Click Fork. Fork button
![image](https://user-images.githubusercontent.com/67740644/167239944-0889099f-c406-4098-91d1-234c2c77d255.png)
    GitHub will take you to your copy (your fork) of the Spoon-Knife repository.

# Cloning a fork

You've successfully forked the Spoon-Knife repository, but so far, it only exists on GitHub. To be able to work on the project, you will need to clone it to your computer.

You can clone your fork with the command line, GitHub CLI, or GitHub Desktop.

    On GitHub, navigate to your fork of the Spoon-Knife repository.

    Above the list of files, click Code. "Code" button
![image](https://user-images.githubusercontent.com/67740644/167239963-9e69c865-816b-44c7-b5e6-7e13232ba1b3.png)

To clone the repository using HTTPS, under "Clone with HTTPS", click
. To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click . To clone a repository using GitHub CLI, click Use GitHub CLI, then click
![image](https://user-images.githubusercontent.com/67740644/167240026-093cdd74-09d5-4ed1-94c1-b1edb2f16b50.png)
![image](https://user-images.githubusercontent.com/67740644/167240032-c0f70f3b-d01b-4099-bb79-833b6de96054.png)
    . The clipboard icon for copying the URL to clone a repository

    The clipboard icon for copying the URL to clone a repository with GitHub CLI

    Open Git Bash.

    Change the current working directory to the location where you want the cloned directory.

    Type git clone, and then paste the URL you copied earlier. It will look like this, with your GitHub username instead of YOUR-USERNAME:

    $ git clone https://github.com/YOUR-USERNAME/Spoon-Knife

    Press Enter. Your local clone will be created.

    $ git clone https://github.com/YOUR-USERNAME/Spoon-Knife
    > Cloning into `Spoon-Knife`...
    > remote: Counting objects: 10, done.
    > remote: Compressing objects: 100% (8/8), done.
    > remove: Total 10 (delta 1), reused 10 (delta 1)
    > Unpacking objects: 100% (10/10), done.

# Making and pushing changes

Go ahead and make a few changes to the project using your favorite text editor, like Atom. You could, for example, change the text in index.html to add your GitHub username.

When you're ready to submit your changes, stage and commit your changes. git add . tells Git that you want to include all of your changes in the next commit. git commit takes a snapshot of those changes.

git add .
git commit -m "a short description of the change"

When you stage and commit files, you essentially tell Git, "Okay, take a snapshot of my changes!" You can continue to make more changes, and take more commit snapshots.

Right now, your changes only exist locally. When you're ready to push your changes up to GitHub, push your changes to the remote.

git push

# Making a pull request

At last, you're ready to propose changes into the main project! This is the final step in producing a fork of someone else's project, and arguably the most important. If you've made a change that you feel would benefit the community as a whole, you should definitely consider contributing back.

To do so, head on over to the repository on GitHub where your project lives. For this example, it would be at https://www.github.com/<your_username>/Spoon-Knife. You'll see a banner indicating that your branch is one commit ahead of octocat:main. Click Contribute and then Open a pull request.

GitHub will bring you to a page that shows the differences between your fork and the octocat/Spoon-Knife repository. Click Create pull request.

GitHub will bring you to a page where you can enter a title and a description of your changes. It's important to provide as much useful information and a rationale for why you're making this pull request in the first place. The project owner needs to be able to determine whether your change is as useful to everyone as you think it is. Finally, click Create pull request.

# Contributors
|  Name   |  Role in Project  |  Profile   | 
| :----:  |  :-------------:  |  :-----:   |
| K.Sasikalyan | Author       |  [Check](https://github.com/KanakamSasikalyan)      |
| B.Radhika    | Collaborator & Contributor|  [Check]() |


© Copyright Agency and contributors 2022. 
