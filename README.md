cd C:\Users\USER\Desktop\learning_code\readme2
bash: cd: C:UsersUSERDesktoplearning_codereadme2: No such file or directory

USER@DESKTOP-0FR883O MINGW64 ~
$ cd "C:\Users\USER\Desktop\learning_code\readme2"

USER@DESKTOP-0FR883O MINGW64 ~/Desktop/learning_code/readme2 (main)
$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.txt

no changes added to commit (use "git add" and/or "git commit -a")

USER@DESKTOP-0FR883O MINGW64 ~/Desktop/learning_code/readme2 (main)
$ git add .

USER@DESKTOP-0FR883O MINGW64 ~/Desktop/learning_code/readme2 (main)
$ git commit -m "upload fix"
[main 18bd017] updated fix
 1 file changed, 1 insertion(+)

USER@DESKTOP-0FR883O MINGW64 ~/Desktop/learning_code/readme2 (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 252 bytes | 252.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/awoyesuku/readme1.git
   a83e74c..18bd017  main -> main


 
