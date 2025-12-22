# HELP

## How to pull?

Situation: you `git clone <repo>` then you made changes locally. Now you want to pull the latest changes from remote without losing your local changes.

if `git pull` gives merge conflicts, do:

```sh
git stash     # save your local changes temporarily
git pull      # pull the latest changes from remote
git stash pop # re-apply your local changes
```

## AI Assistance:

- You may enable the in-editor **Co-pilot** for AI-assisted auto-complete. Remember however, that you are the **Pilot**. This means, you are responsible for the code.
- You may ask it to explain concepts or errors.
- You may not ask it to solve the task.
