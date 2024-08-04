### setting

#### installing github
* terminal > `brew install git`

#### set user name and email
* terminal > `git config --global user.name "juheefatal"`
* termimal > `git config --global user.email "salesiogirl@gmail.com"`
* check : terminal > `git config --global --list`

#### set local storage
* finder > select the parent folder of the folder I want to upload
  * confirm that the .git folder is created
* terminal > `git commit -m "(my message)"`
  * need to be careful!


#### upload files
* check : git remote -v
  * if nothing, `git remote add origin "(my github url)"`
* create branch : terminal > `git push origin main`
* 
