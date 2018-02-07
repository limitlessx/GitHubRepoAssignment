This file is created for GitHubRepoAssignment. 

CodingDojo@DESKTOP-M9CAE1M MINGW64 ~
$ cd Desktop

CodingDojo@DESKTOP-M9CAE1M MINGW64 ~/Desktop
$ mkdir GitHubRepoAssignment

CodingDojo@DESKTOP-M9CAE1M MINGW64 ~/Desktop
$ ls
 desktop.ini  'git commands.txt'   GitHubRepoAssignment/   gittest/

CodingDojo@DESKTOP-M9CAE1M MINGW64 ~/Desktop
$ cd GitHubRepoAssignment

CodingDojo@DESKTOP-M9CAE1M MINGW64 ~/Desktop/GitHubRepoAssignment
$ pwd

CodingDojo@DESKTOP-M9CAE1M MINGW64 ~/Desktop/GitHubRepoAssignment
$ git init
Initialized empty Git repository in C:/Users/CodingDojo/Desktop/GitHubRepoAssignment/.git/

CodingDojo@DESKTOP-M9CAE1M MINGW64 ~/Desktop/GitHubRepoAssignment (master)
$ touch readme.md

CodingDojo@DESKTOP-M9CAE1M MINGW64 ~/Desktop/GitHubRepoAssignment (master)
$ ls
readme.md

CodingDojo@DESKTOP-M9CAE1M MINGW64 ~/Desktop/GitHubRepoAssignment (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readme.md

nothing added to commit but untracked files present (use "git add" to track)

CodingDojo@DESKTOP-M9CAE1M MINGW64 ~/Desktop/GitHubRepoAssignment (master)
$ git add readme.md

CodingDojo@DESKTOP-M9CAE1M MINGW64 ~/Desktop/GitHubRepoAssignment (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   readme.md


CodingDojo@DESKTOP-M9CAE1M MINGW64 ~/Desktop/GitHubRepoAssignment (master)
$ git commit -m 'updated the content'
[master (root-commit) 2664015] updated the content
 1 file changed, 1 insertion(+)
 create mode 100644 readme.md

CodingDojo@DESKTOP-M9CAE1M MINGW64 ~/Desktop/GitHubRepoAssignment (master)
$ git status
On branch master
nothing to commit, working tree clean
