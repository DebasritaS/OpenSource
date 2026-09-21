# OPENSOURCE CONTRIBUTION


1. To make a rep Git repo:

```bash
git init
```
2. Git clone:
 
 ```bash
 git clone <repository-url>
 ```
 3. Add a GitHub repository as a remote:

```bash
git remote add origin <repository-url>
```
Verify remote:

```bash
git remote -v
```
To check branch:

```bash
git branch
```
To rename branch:

```bash
git branch -M main # converted to name "main" 
```
To create new branch:

```bash
git checkout -b <branch-name>
```
To change current working branch:

```bash
git checkout <branch-name>
```
To delete branch(cannot delete current working branch, change current working branch before deleting):

```bash
git branch -d <branch-name>
```

4. Check the repository status:

```bash
git status
```

5. Stage, commit, and push changes:

```bash
git add <filename>   # or . to add all files
```
```bash
git commit -m "Message"
```
To push:

```bash
git push origin main
```
```bash
git push -u origin main # to upstream
```

6. Pull remote changes and push again if needed:

```bash
git pull --rebase origin main
```
```bash
git push --force origin main
```
7. Remove .git from project1 inside another git repo:

```bash
cd project1
```
```bash
rm -rf .git
```
