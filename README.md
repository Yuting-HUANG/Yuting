Last login: Thu May  7 17:07:22 on ttys001
➜  ~ pwd
/Users/yutinghuang
➜  ~ ls
Applications           Music                  math.sh
Code                   Pictures               my-first-repo
Commands               Postman                my-second-repo
Desktop                Public                 my-third-repo
Documents              README.md              short
Downloads              bash                   test
Git                    cloudsql_local_adaptor test.py
Library                dbt.code-workspace     workbench
Movies                 list.txt
➜  ~ cd Git
➜  Git ls
dba.dbt
➜  Git cd..
zsh: command not found: cd..
➜  Git cd ..
➜  ~ cd Git
➜  Git mkdir my-first-repo
➜  Git cd my-first-repo
➜  my-first-repo git init
Initialized empty Git repository in /Users/yutinghuang/Git/my-first-repo/.git/
➜  my-first-repo git:(master) echo "# Yuting" >> README.md
➜  my-first-repo git:(master) ✗ git add README.md
git commit -m "first commit"
git remote add origin git@github.com:Yuting-HUANG/Yuting.git
git push -u origin master
[master (root-commit) 4a7c6aa] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
Warning: Permanently added the RSA host key for IP address '140.82.118.3' to the list of known hosts.
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 232 bytes | 232.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Yuting-HUANG/Yuting.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
➜  my-first-repo git:(master) git remote
origin
➜  my-first-repo git:(master) git push -u origin master
Branch 'master' set up to track remote branch 'master' from 'origin'.
Everything up-to-date
➜  my-first-repo git:(master) git remote
origin
➜  my-first-repo git:(master) git remote add origin https://github.com/Yuting-HUANG/my-first-repo.git
fatal: remote origin already exists.
➜  my-first-repo git:(master) git push -u origin master
Branch 'master' set up to track remote branch 'master' from 'origin'.
Everything up-to-date
➜  my-first-repo git:(master) rm readme.txt
rm: readme.txt: No such file or directory
➜  my-first-repo git:(master) touch README.md
➜  my-first-repo git:(master) nano README.md
➜  my-first-repo git:(master) ✗ git add -A
➜  my-first-repo git:(master) ✗ git commit -m "added README.md"
[master 26d34b0] added README.md
 1 file changed, 28 insertions(+), 1 deletion(-)
 rewrite README.md (100%)
➜  my-first-repo git:(master) git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
➜  my-first-repo git:(master) git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
  GNU nano 2.0.6              File: README.md                         Modified

# Yuting

### Geography

I live in the city of Baltimore, in the state of Maryland, in the United States
of America.

### Reading

Three of my favorite books are:

- *Mindstorms* by Seymour Papert
- *Welcome to the Monkey House* by Kurt Vonnegut
- *Persepolis* by Marjane Satrapi

### Food

Last night I dreamt about eating in these restaurants:

1. Linger in Denver.
2. Azura in Jerusalem.
3. Gemma in New York City.

### Contact

The best way to get in touch with me is [on Twitter](https://twitter.com/seankross).
