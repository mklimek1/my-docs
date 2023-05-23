## 5. Fork

Next, you'll want to open the README and make sure you understand the instructions. Then, fork the repo by clicking on Fork located at the top right corner of your screen.
(obrazek)
Clone the forked repo in your local computer using the following command:
git clone < LINK TO THE REPO >
You'll see the repo link when you click on the code dropdown. Once you've cloned it, open the directory containing your new fork and start adding your contribution.
When done push your changes on GitHub by using the following instructions:

| git status | displays which modifications have been staged|
| git add .| adds changes to the cloned repo |
| git commit -m "changes" | performs a commit to the cloned repo |
| git branch -M changes | creates a new branch |
|git push -u origin changes | pushes the changes |

GitHub will prompt you to create a pull request once you have pushed your changes to the cloned repository. Create the pull request and then wait for the maintainers to merge your changes into the main repository. In case you forked the project some time ago, ensure that you incorporate the upstream modifications into your local repository. If you come across a large file, you can install git-lfs if it is not already installed by running the command "brew install git-lfs".

| **Information**: Git LFS is an extension for large file storage, developed by Atlassian, GitHub, and several other open-source contributors. By downloading appropriate versions of large files slowly, it reduces the impact of large files in your repository.|

You may refer to the documentation provided on [how to install git-lfs](<https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage> "How to install git-lfs").

See also:[6. Choose](choose.md)
