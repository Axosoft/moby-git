# GitKraken Revert Git Commit Example Repo
## Featuring Moby Dick

### Congrats on progressing with your exploration of Git and GitKraken 👋

This branch provides an example of reverting with GitKraken and Git CLI.  

You can follow along with the [tutorial for "How to Revert a Commit in Git" on GitKraken.com][1].


#### Set up:

If you have not already done so, you will also need to [download GitKraken.][2]

[<img src="img/gitkraken-keif-teal-sq.png" alt='GitKraken download logo' width="100" />][2]


## Git Revert a commit with GitKraken

1. Open this local repository with GitKraken by clicking on the folder icon in the upper left, choosing 'Open a repo' and selecting the folder where you cloned this repository.

2. Modify any files you like and make a new commit in the repository.

3. In the graph view, right-click on the latest commit at the top of the graph.  

4. Select `Revert commit` from the list. 

**Congratulations!**  

You have successfully edited a file and made a commit with GitKraken 🎉

Take a look at the graph now and you will see a new commit named `Revert "previous commit summary"`. This new commit has undone the changes made in the reverted commit. 

While you can revert any commit in the graph, you might run into merge conflicts. Reverting just the last commit should be a safe method to undo your changes.  

GitKraken also offers an alternative to revert with our Undo button. If you change your mind on a commit you have just made, simply click 'Undo' in the top toolbar and GitKraken will remove the commit entirely. Read more about this feature in our [Undo support documentation](https://support.gitkraken.com/working-with-commits/undo-and-redo/)


*Now, let's try a revert with the CLI...*


## Git Commit a file with the Git CLI

1. Modify any files you like and make a new commit in the repository.

2. In the terminal type `git log` and hit enter to see your commit history and to expose the [commit SHA](https://git-scm.com/book/en/v2/Git-Tools-Revision-Selection). The first one shown will be the commit you just made. Copy this commit SHA to your clipboard.

3. In the terminal type `git revert your-commit-SHA` (replacing `your-commit-SHA` with the one you copied) and hit enter. 

4. If you find yourself in this unfamiliar editor, there is a good chance you are in `vim`. Type `i` to go into 'insert mode', which will allow you to navigate and type as you like. Then hit the `esc` key and type `:wq` and enter to tell the editor to write (save) your changes and quit the application.  You can read more about `vim` at [https://www.vim.org/](https://www.vim.org/).


**Congratulations!**  

You have successfully reverted a commit with the Git CLI. 👏


## Next Steps

You are now set up to work locally and push your changes to GitHub, or work on GitHub and pull those changes locally. 

Note: Git does not allow you to push a reverted commit by default if there are no commits after it. You will need to use the `force` option. [Learn more about pulling and pushing over on GitKraken.com](
https://support.gitkraken.com/working-with-repositories/pushing-and-pulling/)

--

[1]: https://www.gitkraken.com/learn/git/problems/revert-git-commit?utm_source=learn%20git%20practice%20repo&utm_medium=README%20revert%20git%20commit%20link&utm_campaign=revert%20git%20commit%20practice%20repo

[2]: https://www.gitkraken.com/download?utm_source=learn%20git%20practice%20repo&utm_medium=README%20gk%20download%20link&utm_campaign=revert%20git%20commit%20practice%20repo

