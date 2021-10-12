
$ echo "# Practicing Git " > README.md

$ git init
Initialized empty Git repository in /private/tmp/ggg/.git/

$ git add README.md

$ git commit -m "first commit"
[master (root-commit) adc1a5a] first commit
1 file changed, 1 insertion(+)
create mode 100644 README.md

$ git remote add dragonball git@github.com:kaochenlong/ggg.git

$ git push -u dragonball master
Counting objects: 3, done.
Writing objects: 100% (3/3), 228 bytes | 228.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To github.com:kaochenlong/ggg.git
* [new branch]      maaster - > master
Branch master set up to track remote branch master from dragonball.
