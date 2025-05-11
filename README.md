Notes

I have kali linux installed on virtualbox for the purpose of this final.

After opening and booting linux on my selected VM, I navigated to the terminal and did the following the following:

1) Choosing the directory and creating the script using these commands...
"cd ~/Documents" to change my directory to documents
"touch count.sh" to create the count script
"nano" count.sh to edit the script file contents

2) Making and Testing the Script
"chmod +x count.sh" allowed me to run the script
"./count.sh" executed the script

3) GitHub Credentials and Cloning
"git config --global user.name 'cloyloys'"
and
"git config --global user.mail 'c------@gmail.com'" stores my user and token in case I make mistakes and need
to make updates to the Repository... which I did
"git clone (url)" set up and downloaded the (empty) project onto my machine.

4) Generating a Personal Access Token and Pushing to GitHub
On the website (https://github.com/settings/tokens) I generated a new classic token to authenticate on to
my user profile. Using that token, I ran the following commands:
"git add ." to add all contents I want to commit that are in the folder
"git commit -m" to save a snapshot of the files
"git push -u origin main" to upload them committed files
