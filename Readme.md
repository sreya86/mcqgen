This is Readme file.
#setting your username for every git repository on your computer.
git config --global user.name "sreya_ku"
(in ".." u can also set your email)
#confirm that you have set the git username correctly:
git config --global user.name 
#to create virtual env:
conda create -p env python=3.8 -y
#to activate the env:
source activate ./env
(because conda activate cmd may give some errors)
#to clear screen
clear
#after creating 5k+ files are seen on git source control icon
#we don't want to include all these into git, so we take env folder to seperate folder named:".gitignore"
touch .gitignore
#open gitignore file and write env inside it.

