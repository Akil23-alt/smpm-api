dsadm@ESN501D1201986 MINGW64 ~
$ git config --global user.name "Seu Nome"

dsadm@ESN501D1201986 MINGW64 ~
$ git config --global user.name "Akil23-alt"

dsadm@ESN501D1201986 MINGW64 ~
$ git config --global user.email "kauaakil23@gmail.com"

dsadm@ESN501D1201986 MINGW64 ~
$ mkdir smpm-api

dsadm@ESN501D1201986 MINGW64 ~
$ cd smpm-api

dsadm@ESN501D1201986 MINGW64 ~/smpm-api
$ git init
Initialized empty Git repository in C:/Users/dsadm/smpm-api/.git/

dsadm@ESN501D1201986 MINGW64 ~/smpm-api (master)
$ mkdir smpm-api

dsadm@ESN501D1201986 MINGW64 ~/smpm-api (master)
$ cd smpm-api

dsadm@ESN501D1201986 MINGW64 ~/smpm-api/smpm-api (master)
$ git init
Initialized empty Git repository in C:/Users/dsadm/smpm-api/smpm-api/.git/

dsadm@ESN501D1201986 MINGW64 ~/smpm-api/smpm-api (master)
$ echo "// Arquivo inicial da API smpm-api" > app.js

dsadm@ESN501D1201986 MINGW64 ~/smpm-api/smpm-api (master)
$ git add app.js
warning: in the working copy of 'app.js', LF will be replaced by CRLF the next time Git touches it

dsadm@ESN501D1201986 MINGW64 ~/smpm-api/smpm-api (master)
$ git commit -m "chore: criar arquivo inicial app.js"
[master (root-commit) d3a18f3] chore: criar arquivo inicial app.js
 1 file changed, 1 insertion(+)
 create mode 100644 app.js

dsadm@ESN501D1201986 MINGW64 ~/smpm-api/smpm-api (master)
$ git remote add origin https://github.com/Akil23-alt/smpm-api.git

dsadm@ESN501D1201986 MINGW64 ~/smpm-api/smpm-api (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Akil23-alt/smpm-api.git'

dsadm@ESN501D1201986 MINGW64 ~/smpm-api/smpm-api (master)
$ git branch -m main

dsadm@ESN501D1201986 MINGW64 ~/smpm-api/smpm-api (main)
$ git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 261 bytes | 65.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Akil23-alt/smpm-api.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

dsadm@ESN501D1201986 MINGW64 ~/smpm-api/smpm-api (main)
$
