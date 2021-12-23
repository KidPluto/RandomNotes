## My most used Git commands

----
Getting the code from master to your branch
```
$> git status
$> git pull
$> git pull origin master
$> git merge origin master
// If any files have conflicts
// Git --> Resolve Differences (In IntelliJ Idea)
// Need to commit the results to complete the merge process
```
----
Getting changes from another branch
* Branch_1 is from main
* Branch_2 is from Branch_1 
  * Seems to work when both branches are from main
* While on Branch_2
```
$> git pull origin Branch_1
// This failed with [fatal: Not possible to fast-forward, aborting.]
$> git pull origin Branch_1 --rebase
// Worked
```
----
Not seeing new branch
```
// On master
$> git pull origin master
// Works, but still not seeing new branch
$> git fetch
```
----
Updating your branch, after others have worked on it
```
$> git pull origin/GUA-22147
$> git merge origin/GUA-22147
```

----
Clone just a single branch
```
git clone --single-branch -b react-mini https://github.com/safak/youtube.git .
git clone --single-branch --branch blog https://github.com/http4k/http4k.git .
git clone --branch blog https://github.com/http4k/http4k.git .
```

