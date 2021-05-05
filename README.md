# GitKraken Clone Example Repo
## Featuring Moby Dick

### Congrats on progressing with your exploration of Git and GitKraken 👋

This branch is meant to provide an example of reverting with GitKraken and Git CLI.  

You can follow along with the [tutorial for "How to Revert a Commit in Git" on GitKraken.com][1].


#### Set up:

If you have not already done so, you will also need to [download GitKraken.][2]

[<img src="img/gitkraken-keif-teal-sq.png" alt='GitKraken download logo' width="100" />][2]


## Git Revert a file with GitKraken

1. Open this local repository with GitKraken by clicking on the folder icon in the upper left, choosing 'Open a repo' and selecting the folder where you cloned this repository.

2. Make a new commit in this branch, editing whatever you like.  

3. In the graph view, right mouse click on the latest commit at the top of the graph.  

4. Select `Revert commit` from the list. 

**Congratulations!**  

You have successfully edited a file and made a commit with GitKraken 🎉

Take a look at the graph now and you will see a new commit named "Revert "previous commit summary". This new commit has undone the changes made in the reverted commit. While you can revert any commit in the graph, you might run into merge conflicts. Reverting just the  last commit should be a safe method to undo your changes.  

GitKraken also offers an alternative to revert with our Undo button. If you change your mind on a commit you have just made, simply click 'Undo' and GitKraken will remove the commit entirely. Read more about this feature on our [Undo support documentation page](https://support.gitkraken.com/working-with-commits/undo-and-redo/)


*Now, let's try a revert with the CLI...*


## Git Commit a file with the Git CLI

1. Make a commit in the repository, modifying any files you like.

2. In the terminal type `git log` and hit enter to see your commit  history and to  expose the [commit sha](https://git-scm.com/book/en/v2/Git-Tools-Revision-Selection). The first one shown will be the for commit you just made. Copy this commit sha to your clipboard.

3. In the terminal type `git revert your-commit-sha` (replacing `your-commit-sha` with the one you copied) and hit enter 

4. This will If you find youself in this unfamiliar editor, there is a good chance you are in `vim`. Type `i` to go into 'insert mode', which will allow you to navigate and type as you like. Then hit the `esc` key and type `:wq` and enter to tell the editor to write(save) your changes and quit the application.  You can read more about `vim` at [https://www.vim.org/](https://www.vim.org/)

5. 

**Congratulations!**  

You have successfully reverted a commit with the Git CLI.


## Next Steps

You are reading this on the `git-revert` branch of this repository.  

To continue on   

To switch branches if you are reading this on GitHub, click the `banches` option towards the top left of the code view and select the branch you want to navigate to.  

To checkout the branch locally and pull from the online branch in the CLI type `git checkout -b `

To checkout the branch locally using GitKraken, simply click on the `` branch in the Remote menu on the right hand side.  


--

[1]: https://www.gitkraken.com/learn/git/problems/revert-git-commit?utm_source=learn%20gi[…]20tutorial%20link&utm_campaign=git%20clone%20practice%20repo

[2]: https://www.gitkraken.com/download?utm_source=learn%20git%20practice%20repo&utm_medium=README%20gk%20download%20link&utm_campaign=git%20clone%20practice%20repo