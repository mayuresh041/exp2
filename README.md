C:\Users\91987>cd rev1

C:\Users\91987\rev1>git checkout -b fb1
Switched to a new branch 'fb1'

C:\Users\91987\rev1>git branch
* fb1
  master

C:\Users\91987\rev1>git checkout master
Switched to branch 'master'

C:\Users\91987\rev1>git checkout fb1
Switched to branch 'fb1'

C:\Users\91987\rev1>git checkout master
Switched to branch 'master'

C:\Users\91987\rev1>git merge fb1
Already up to date.

C:\Users\91987\rev1>rev1.txt

C:\Users\91987\rev1>git branch
  fb1
* master

C:\Users\91987\rev1>git checkout fb1
Switched to branch 'fb1'

C:\Users\91987\rev1>rev1.txt

C:\Users\91987\rev1>git add .

C:\Users\91987\rev1>git commit -m "first"
[fb1 119999e] first
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\Users\91987\rev1>rev1.txt

C:\Users\91987\rev1>git checkout master
Switched to branch 'master'

C:\Users\91987\rev1>rev1.txt

C:\Users\91987\rev1>git merge fb1
Updating daf99af..119999e
Fast-forward
 rev1.txt | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\Users\91987\rev1>rev1.txt

C:\Users\91987\rev1># exp2
