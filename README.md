# cfeproj
PS C:\users\admin\cfeproj> git remote add orgin https://github.com/winash1618/cfeproj.git
PS C:\users\admin\cfeproj>  git fetch remotename
fatal: 'remotename' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
PS C:\users\admin\cfeproj>  git fetch
PS C:\users\admin\cfeproj> git push -u orgin master
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 936 bytes | 46.00 KiB/s, done.
Total 7 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 4 local objects.
To https://github.com/winash1618/cfeproj.git
   7eb257e..822bc28  master -> master
Branch 'master' set up to track remote branch 'master' from 'orgin'.
heroku config:set DISABLE_COLLECTSTATIC=1 --app ilit-journey-05370
