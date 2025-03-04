Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
…
user@LAPTOP-NSB71ORR MINGW64 ~
$ cd "D:\FILE\Sem 4\tugas PW"
bash: cd: D:\FILE\Sem 4\tugas PW: No such file or directory

user@LAPTOP-NSB71ORR MINGW64 ~
$ cd "D:\FILE\Sem 6\Tugas PW"

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW
$ git clone https://github.com/kheylontoh/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW
$ cd belajarGit

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git checkout -b Tugas-Git
Switched to a new branch 'Tugas-Git'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Git)
$ git add Tugas-Git.txt
fatal: pathspec 'Tugas-Git.txt' did not match any files

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Git)
$ git add Tugas-Git.txt
fatal: pathspec 'Tugas-Git.txt' did not match any files

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Git)
$ git touch Tugas-Git.txt
git: 'touch' is not a git command. See 'git --help'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Git)
$ touch Tugas-Git.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Git)
$ git add Tugas-Git.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Git)
$ git config --global user.name "kheylontoh"

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Git)
$ git config --global user.email "kherenlontoh026@student.unsrat.ac.id"

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Git)
$ git commit -m "Menambahkan Tugas-Git.txt"
[Tugas-Git b4707c9] Menambahkan Tugas-Git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Git.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Git)
$ git checkut main
git: 'checkut' is not a git command. See 'git --help'.

The most similar command is
        checkout

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git merge Tugas-Git
Updating 9a5240b..b4707c9
Fast-forward
 Tugas-Git.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Git.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 307 bytes | 307.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/belajarGIT.git
   9a5240b..b4707c9  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git checkout -b Tugas-Html
Switched to a new branch 'Tugas-Html'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Html)
$ git add Tugas-Html.txt
fatal: pathspec 'Tugas-Html.txt' did not match any files

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Html)
$ touch Tugas-Html.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Html)
$ git add Tugas-Html.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Html)
$ git commit -m "Menambahkan Tugas-Html.txt"
[Tugas-Html 9ae071c] Menambahkan Tugas-Html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Html.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git merge Tugas-Html
Updating b4707c9..9ae071c
Fast-forward
 Tugas-Html.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Html.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 307 bytes | 307.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/belajarGIT.git
   b4707c9..9ae071c  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git checkout -b Tugas-Css
Switched to a new branch 'Tugas-Css'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Css)
$ touch Tugas-Css.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Css)
$ git add Tugas-Css.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Css)
$ git commit -m "Menambahkan Tugas-Css.txt"
[Tugas-Css 443c208] Menambahkan Tugas-Css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Css.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git merge Tugas-Css
Updating 9ae071c..443c208
Fast-forward
 Tugas-Css.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Css.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 259 bytes | 259.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/belajarGIT.git
   9ae071c..443c208  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git checkout -b Tugas-Js
Switched to a new branch 'Tugas-Js'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Js)
$ touch Tugas-Js.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Js)
$ git add Tugas-Js.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Js)
$ git commit -m "Menambahkan Tugas-Js.txt"
[Tugas-Js 5c94111] Menambahkan Tugas-Js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Js.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git merge Tugas-Js
Updating 443c208..5c94111
Fast-forward
 Tugas-Js.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Js.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 255 bytes | 255.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/belajarGIT.git
   443c208..5c94111  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-midProject)
$ touch Tugas-midProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-midProject)
$ git add Tugas-midProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-midProject.txt"
[Tugas-midProject a785784] Menambahkan Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git merge Tugas-midProject
Updating 5c94111..a785784
Fast-forward
 Tugas-midProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 271 bytes | 271.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/belajarGIT.git
   5c94111..a785784  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git checkout -b Tugas-Php
Switched to a new branch 'Tugas-Php'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Php)
$ touch Tugas-Php.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Php)
$ git add Tugas-Php.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Php)
$ git commit -m "Menambahkan Tugas-Php.txt"
[Tugas-Php 139787b] Menambahkan Tugas-Php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Php.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-Php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git merge Tugas-Php
Updating a785784..139787b
Fast-forward
 Tugas-Php.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Php.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 254 bytes | 254.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/belajarGIT.git
   a785784..139787b  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-finalProject)
$ touch Tugas-finalProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-finalProject)
$ git add Tugas-finalProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-finalProject.txt"
[Tugas-finalProject f0066fb] Menambahkan Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git merge Tugas-finalProject
Updating 139787b..f0066fb
Fast-forward
 Tugas-finalProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 274 bytes | 274.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/belajarGIT.git
   139787b..f0066fb  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/belajarGIT.git
 * [new branch]      Tugas-Css -> Tugas-Css
 * [new branch]      Tugas-Git -> Tugas-Git
 * [new branch]      Tugas-Html -> Tugas-Html
 * [new branch]      Tugas-Js -> Tugas-Js
 * [new branch]      Tugas-Php -> Tugas-Php
 * [new branch]      Tugas-finalProject -> Tugas-finalProject
 * [new branch]      Tugas-midProject -> Tugas-midProject

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/belajarGit (main)
$

