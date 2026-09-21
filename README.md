# OPENSOURCE CONTRIBUTION


1. To make a rep Git repo:

```bash
git init
```

2. Check the repository status:

```bash
git status
```

3. Stage, commit, and push changes:

```bash
git add <filename>   # or . to add all files
```
```bash
git commit -m "Message"
```
```bash
git push origin main
```

4. Pull remote changes and push again if needed:

```bash
git pull --rebase origin main
```
```bash
git push --force origin main
```
5. Remove .git from project1 inside another git repo

```bash
cd project1
```
```bash
rm -rf .git
```
