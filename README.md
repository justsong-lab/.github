# GitHub Profile Updater for Organization

## Deploy Steps
1. Fork this repository.
2. Edit `update.py`, `Ctrl-F` search for variable `github_username`, change its value to your organization's name.
3. Then click the `Actions`, enable the workflow.

That's all, your readme profile will be automatically updated on every sunday.

You can goto your repository's actions page, click the `update` workflow and then click `Run workflow` to manually trigger the Github Action.

You may need to change the timezone in `.github/workflows/update.yml` about line 33. 


## Others
For the version for user, check out [here](https://github.com/songquanpeng/songquanpeng).