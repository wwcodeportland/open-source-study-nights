# Github Fork Workflow

You can choose to manage your own version of a Github repository ("repo") as a branch, or by forking the main project. Many open source projects prefer you to make a fork, so you can keep your own work separate from the official project.

The setup process is described [in this article](https://help.github.com/articles/fork-a-repo/). It can be summarized as follows:

1. Using the Github web interface, log into your account and fork the base repository.
2. Navigate to your own fork, copy the clone URL, and use `$ git clone` to get the forked repository on your own machine.
3. Your local repository will have a remote repository called `origin` located at your fork. Add a remote called `upstream` located at the base project's URL.

Then you can use the instructions in [this article](https://help.github.com/articles/syncing-a-fork/) to keep your local repository synced with the upstream (base project).
