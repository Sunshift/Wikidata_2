# Information regarding project

More information coming soon. 

## shortcuts

git clone --> works only with the HTTPS
cd --> change directory to git file 
ls -la --> show hidden git file - la doesnt work here
git status --> status of files but not saved 
git add . --> save all the files 
git commit -m "" --> message needed for in general update
git push --> to remote repository 

ssh-keygen -t rsa -b 4096 -C "frederik.behets@gmail.com" --> to make a keygen for pushing to git 
--> Give the key a name 
--> ls | grep testkey --> find the key 
--> .pub for public github interface 
cat testkey.pub --> print out key for push --> paste into github 
pbcopy <.../WikiKey.pub>