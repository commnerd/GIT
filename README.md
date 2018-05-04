# GIT
General tools for git

## Installation:
1. Clone the repo:
```bash
git clone https://github.com/commnerd/GIT.git
```
2. Add dev_env/bin or srv_env/bin to your $PATH variable depending on what context you're using the scripts in development or server context

### dev_env
- bin
-- git-use: Activate the associated script
```bash
git use (script|hook) <script-name>
```
-- git-unuse: Deactivate the associated script
```bash
git unuse (script|hook) <script-name>
```
-- git-back: Move back into the current history
```bash
git cleanup 
```
-- git-cleanup: Remove the given branch from both your local repo and origin
```bash
```

- hooks
-- pre-commit: Don't commit to master! (without approval)
```bash
git use 