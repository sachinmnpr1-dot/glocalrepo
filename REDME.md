PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\gitfirstrepo> cd ..
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot> mkdir LocalRepo


    Directory: C:\Users\Mohamed\Downloads\sachinmnpr1-dot


Mode                 LastWriteTime         Length Name                                                                           
----                 -------------         ------ ----                                                                           
d-----          8/9/2026   6:23 PM                LocalRepo                                                                      


PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot> cd LocalRepo
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git init
Initialized empty Git repository in C:/Users/Mohamed/Downloads/sachinmnpr1-dot/LocalRepo/.git/
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        style.css

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git add .
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   style.css

PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git commit -m "Add initial files"
[master (root-commit) 4e01b96] Add initial files
 2 files changed, 4 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git status
On branch master
nothing to commit, working tree clean
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git remote add origin https://github.com/sachinmnpr1-dot/glocalrepo.git
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git remote -v
origin  https://github.com/sachinmnpr1-dot/glocalrepo.git (fetch)
origin  https://github.com/sachinmnpr1-dot/glocalrepo.git (push)
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git branch
* master
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git branch -M main
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git branch
* main
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 317 bytes | 317.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/sachinmnpr1-dot/glocalrepo.git
 * [new branch]      main -> main
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\LocalRepo> 