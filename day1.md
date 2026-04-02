# Day 1 - GitHub & Git Basics

## Date
2 April 2026

---

## Goal of the Day
- Set up Git and GitHub
- Learn basic commands

---

## What I did
- Created GitHub account
- Created first repository (my-first-repo)
- Edited README.md on GitHub
- Installed Git on Windows
- Configured Git (username & email)
- Cloned repository to local computer
- Created notes.txt file locally
- Used git add, commit, and push
- Successfully pushed code to GitHub
- Learned how authentication works
- Used git pull to fetch files from GitHub

---

## Commands I used
```bash
git clone <repo-link>  
git add .
git commit -m "message"
git push
git pull

```
---
## Code Excecuted today

```

$ git --version
git version 2.53.0.windows.2

$ git config --global user.name "Rachana Maurya"


$ git config --global user.email "xxx.com"

$ git clone https://github.com/mauryarachana7-byte/my-first-repo.git
Cloning into 'my-first-repo'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

$ cd my-first-repo

$ git add .

$ git commit -m "Added notes file"
[main 7d3c8b4] Added notes file
 1 file changed, 1 insertion(+)
 create mode 100644 notes.txt

$ git push
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 317 bytes | 317.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/mauryarachana7-byte/my-first-repo.git
   03af73a..7d3c8b4  main -> main

$ cd ..

$ git clone https://github.com/mauryarachana7-byte/learning-log.git
Cloning into 'learning-log'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

$ cd learning-log

$ git pull
Already up to date.

$ git add .


$ git commit -m "day 1 log uploaded"
[main 75e2b2e] day 1 log uploaded
 1 file changed, 118 insertions(+), 14 deletions(-)


$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 1.38 KiB | 1.38 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/mauryarachana7-byte/learning-log.git
   c941632..75e2b2e  main -> main



```

---
## Markdown Basics.

- Markdown is used to format text in GitHub files

- `#` is used for headings (titles)
  - `#`   Chapter title  
  - `##`  Section  
  - `###` Sub-section
 
- `-` Creates bullet point
- Bold text `**important**`
- Code style `git push`


---
## What I Learned
- Git tracks changes in files
- GitHub is used to store code online
- `git commit` saves changes locally
- `git push` uploads changes to GitHub
- `git pull` downloads latest changes
- Authentication is required while pushing code

---
## Problems I Faced
- Confusion during GitHub authentication while pushing

---
## How I Solved Them
- Completed login using browser when prompted