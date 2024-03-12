Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT

Lenovo@DESKTOP-UB2H0VT MINGW64 ~ (master)
$ cd "C:\Tugas PW 1"

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1
$ git clone https://github.com/MarshandaMumu/belajarGit.git
fatal: destination path 'belajarGit' already exists and is not an empty directory.

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1
$ cd belajarGIT

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-git)
$ git checkout -b Tugas-git
fatal: a branch named 'Tugas-git' already exists

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
[Tugas-git 62e4616] Menambahkan Tugas-Git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Git.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-git)
$ git config --global user.email "mumumrshnda@gmail.com"

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
On branch Tugas-git
nothing to commit, working tree clean

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git merge Tugas-git
Updating c9e76ce..62e4616
Fast-forward
 Tugas-Git.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Git.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git push origin main
fatal: User cancelled dialog.
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/MarshandaMumu/belajarGit.git/'

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 293 bytes | 293.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/MarshandaMumu/belajarGit.git
   c9e76ce..62e4616  main -> main

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-Html.txt"
[Tugas-html c94607c] Menambahkan Tugas-Html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Html.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-html)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        Tugas-Html.txt
Please commit your changes or stash them before you switch branches.
Aborting

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-html)
$ git stash
Saved working directory and index state WIP on Tugas-html: c94607c Menambahkan Tugas-Html.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git merge Tugas-html
Updating 62e4616..c94607c
Fast-forward
 Tugas-Html.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Html.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 294 bytes | 294.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/MarshandaMumu/belajarGit.git
   62e4616..c94607c  main -> main

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-Css.txt"
[Tugas-css 0f59e1b] Menambahkan Tugas-Css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git merge Tugas-css
Updating c94607c..0f59e1b
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 336 bytes | 336.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/MarshandaMumu/belajarGit.git
   c94607c..0f59e1b  main -> main

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-Js.txt"
[Tugas-js eda2bef] Menambahkan Tugas-Js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Js.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-js)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        Tugas-Js.txt
Please commit your changes or stash them before you switch branches.
Aborting

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-js)
$ git stash
Saved working directory and index state WIP on Tugas-js: eda2bef Menambahkan Tugas-Js.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git merge Tugas-js
Updating 0f59e1b..eda2bef
Fast-forward
 Tugas-Js.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Js.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git merge Tugas-js
Already up to date.

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 240 bytes | 240.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MarshandaMumu/belajarGit.git
   0f59e1b..eda2bef  main -> main

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-midProject)
$ touch Tugas-MidProject.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-MidProject.txt"
[Tugas-midProject 28d266d] Menambahkan Tugas-MidProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git merge Tugas-midProject
Updating eda2bef..28d266d
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 295 bytes | 295.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MarshandaMumu/belajarGit.git
   eda2bef..28d266d  main -> main

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-Php.txt"
[Tugas-php 0b5bab7] Menambahkan Tugas-Php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git merge Tugas-php
Updating 28d266d..0b5bab7
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 293 bytes | 293.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MarshandaMumu/belajarGit.git
   28d266d..0b5bab7  main -> main

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
[Tugas-finalProject ee801d0] Menambahkan Tugas-FinalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 0b5bab7..ee801d0
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MarshandaMumu/belajarGit.git
   0b5bab7..ee801d0  main -> main

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/MarshandaMumu/belajarGit.git
 * [new branch]      Tugas-css -> Tugas-css
 * [new branch]      Tugas-finalProject -> Tugas-finalProject
 * [new branch]      Tugas-git -> Tugas-git
 * [new branch]      Tugas-html -> Tugas-html
 * [new branch]      Tugas-js -> Tugas-js
 * [new branch]      Tugas-midProject -> Tugas-midProject
 * [new branch]      Tugas-php -> Tugas-php

Lenovo@DESKTOP-UB2H0VT MINGW64 /c/Tugas PW 1/belajarGIT (main)
$

