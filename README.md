# RandomNotes
Just a place to keep some notes

## Setting up IntelliJ
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

## Populatinng GitHub repo
* Good description [here](https://docs.github.com/en/github/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line)
    * Following the non GitHub CLI section in the article above
  ```
  $> git init -b main
  $> git add . 
  $> git commit -m "First commit"
  $> $ git remote add origin  <REMOTE_URL> 
  $> git remote -v
  $> git push -u origin main
  Enter username
  Enter token
  ```
    * The authorization is failing on the push
    * https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/accessing-github-using-two-factor-authentication
    * https://github.com/settings/tokens


