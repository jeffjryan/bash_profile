# bash_profile
My .bash_profile
# Credits:  
I copied this profile directly from Nate and all creative credit goes to him.  From the following page: https://natelandau.com/my-mac-osx-bash_profile/

# Caution
Prior to using any of the steps below, be sure to back up your .bashrc and .bash_profile files!

# Disclaimers
I code for recreational use only and do not take responsibility for any problems that my repo may cause you!
This configuration is specific to my Mac set up with homebrew and a specific env.  This should be changed to work on a standard linux build.

# Configuration Steps
## Step 1: 
  cd ~
## Step 2:
For Mac --> curl https://raw.githubusercontent.com/jeffjryan/bash_profile/master/bash_profile.txt > .bash_profile
For Linux --> curl https://raw.githubusercontent.com/jeffjryan/bash_profile/master/linux.txt > .bash_profileThis will establish a redirect from your .bash_profile to your .bashrc file.
## Step 3:
curl https://raw.githubusercontent.com/jeffjryan/bash_profile/master/bashrc.txt > .bashrc

This will replace your existing .bashrc file with the one from this repo.

