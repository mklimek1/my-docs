## 5. Fork

When you contribute to a GitHub project, the most typical workflow is to fork the project, but open the project README and make yourself familiar with the specific instructions in the very project as these might slightly differ. 

1. To fork a repo, click on `Fork` located at the top right corner of your screen.

2. Clone the forked repo in your local computer using the following command:
  `git clone < LINK TO THE REPO >`

You'll see the repo link when you click on the code dropdown. 

Once you've cloned it, open the directory containing your new fork and start adding your contribution.
When done push your changes on GitHub by using the following instructions:

| `git status` | displays which modifications have been staged|
| `git add .`| adds changes to the cloned repo |
| `git commit -m "changes"` | performs a commit to the cloned repo |
| `git branch -M changes` | creates a new branch |
|`git push -u origin changes` | pushes the changes |

Take a look at [git cheat sheet](<https://education.github.com/git-cheat-sheet-education.pdf>) for more information.

GitHub will prompt you to create a pull request once you have pushed your changes to the cloned repository. Create the pull request and then wait for the maintainers to merge your changes into the main repository. In case you forked the project some time ago, ensure that you incorporate the upstream modifications into your local repository. 

If you come across a large file, you can install git-lfs if it is not already installed by running the command "brew install git-lfs".

| **Information**: Git LFS is an extension for large file storage, developed by Atlassian, GitHub, and several other open-source contributors. By downloading appropriate versions of large files slowly, it reduces the impact of large files in your repository.|

You may refer to the documentation provided on [how to install git-lfs](<https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage> "How to install git-lfs").

Alternatively, if you have troubles using Git, you can use [GitHub Desktop Client](<https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop>) which is an application that enables you to interact with GitHub using a GUI instead of the command line or a web browser.

See also: [6. Choose](choose.md)
