# template to create basic scala sbt projects

# make sure you have installed sbt 
> brew install sbt  ( version 0.13.11 should be downloaded)

# clone this project
> git clone https://github.com/mravind3r/scala-sbt-project-script.git

# cd into the clone project
> cd scala-sbt-project-script

# give permissions to the shell script 
> chmod u+x scala-project-template.sh

# check the path variable 
> echo $PATH

# you would see /usr/bin , we create a symlink here so that the script is  available to be run from anywhere on the command line.
> cd /usr/bin

# create the symlink, check using ls command is the symlink was created
> sudo ln -s  pathtotheclonedproject/scala-project-template.sh

# go to home 
> cd ~

# usage of this shell script 
> scala-project-template.sh test-project

