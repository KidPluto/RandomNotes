
## Setting up IntelliJ with GitHub
* On GitHub create repo
    * Keep web page open, and logged in
* On local, clone it
* Start up IntelliJ, load project
* Make a change, commit, and push
* When prompted select Use Token
* On the popup window select Generate
    * This will send you back to the web page, select generate and copy token
* Paste token into popup window
* Push should work at that point

## Add an existing project to GitHub
* Good description [here](https://docs.github.com/en/github/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line)
    * Following the non GitHub CLI section in the article above
    * Create a repo on GitHub ...
  ```
  $> git init -b main
  $> git add . 
  $> git commit -m "First commit"
  $> git remote add origin  <REMOTE_URL> 
  $> git remote -v
  $> git push -u origin main
  Enter username
  Enter token
  ```
    * The authorization is failing on the push
    * https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/accessing-github-using-two-factor-authentication
    * https://github.com/settings/tokens

## Another way
This I think is a little simpler

* In GitHub 
  * Forked a repo
* On local
  * Clone it
  * One way of doing that.  This is the example of grabbing a branch only

```git clone --single-branch -b react-mini https://github.com/KidPluto/youtube.git .```

  * Open project in IDE
  * Update a file
  * Commit and Push









