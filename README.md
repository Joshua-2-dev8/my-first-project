# my-first-project
i initailized a Git repo, added files to the staging, commit the files with a message "initial commit", practised cloning, linked my local repository to the remote repo 
Ojarotade@DESKTOP-KHOUSFN MINGW64 ~/projects (main)
$ touch goals.txt

Ojarotade@DESKTOP-KHOUSFN MINGW64 ~/projects (main)
$ git add goals.txt
fatal: pathspec 'goals.txt' did not match any files

Ojarotade@DESKTOP-KHOUSFN MINGW64 ~/projects (main)
$ git add goals,txt
fatal: pathspec 'goals,txt' did not match any files

Ojarotade@DESKTOP-KHOUSFN MINGW64 ~/projects (main)
$ git add goals.txt
fatal: pathspec 'goals.txt' did not match any files

Ojarotade@DESKTOP-KHOUSFN MINGW64 ~/projects (main)
$ ls
my-first-project/

Ojarotade@DESKTOP-KHOUSFN MINGW64 ~/projects (main)
$ cd my-first-project

Ojarotade@DESKTOP-KHOUSFN MINGW64 ~/projects/my-first-project (main)
$ git add golas.txt
fatal: pathspec 'golas.txt' did not match any files

Ojarotade@DESKTOP-KHOUSFN MINGW64 ~/projects/my-first-project (main)
$ git add goals.txt

Ojarotade@DESKTOP-KHOUSFN MINGW64 ~/projects/my-first-project (main)
$ git commit -m "Added goals.txt that contains my programming goals"
[main 87d6874] Added goals.txt that contains my programming goals
 1 file changed, 4 insertions(+)
 create mode 100644 goals.txt

Ojarotade@DESKTOP-KHOUSFN MINGW64 ~/projects/my-first-project (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 401 bytes | 200.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Joshua-2-dev8/my-first-project.git
   b29eaf4..87d6874  main -> main

Ojarotade@DESKTOP-KHOUSFN MINGW64 ~/projects/my-first-project (main)
$ git add README.md

