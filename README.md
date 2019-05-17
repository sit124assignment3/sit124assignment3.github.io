# sit124assignment3.github.io

### Setup

Fork this repository on GitHub.

The fork is your version of the repo. All changes you make are submitted there first, and then a pull request is created to our main repo.

To clone your repo on your local machine, run this command in a terminal (replace username accordingly) - `git clone https://github.com/arpitkamboj/sit124assignment3.github.io`

This downloads the repo and all files are placed in a local directory.

Run this command to finish the setup:
`git remote add downstream https://github.com/sit124assignment3/sit124assignment3.github.io`

### Sync with the final website

If a change is made on the final website, use `git pull downstream master` to sync your local repo with it.

### Submitting your changes

After working on the website, you need to create a pull request in order to request for the changes to be incorporated.
Use `git add *` to add all the changes locally.

Use `git commit -m "Added some functionality"` to add a commit with appropriate information (just a small sentence to sum up what changes you made)

Use `git push origin master` to push the changes to your clone on GitHub.

On GitHub, go to your repository and click 'Create a Pull Request' option.
Fill in all the details about the changes you made and click submit.
