# bash_profile
My .bash_profile
# Credits:  
Much of the basis for this .bashrc I copied directly from Nate Landau https://natelandau.com/my-mac-osx-bash_profile/.  All creative credit goes to him.  From this file as a basis, I modified a few items for myself.  It is an ongoing effort.

# Caution
Prior to using any of the steps below, be sure to back up your .bashrc and .bash_profile files!

# Disclaimers
I code for recreational use only and do not take responsibility for any problems that my repo may cause you!
This configuration is specific to my Mac set up with homebrew and a specific env.  This should be changed to work on a standard linux build.

# Configuration Steps
## Step 1: 
  ```cd ~```
## Step 2:
  ```curl https://raw.githubusercontent.com/jeffjryan/bash_profile/master/bash_profile.txt > .bash_profile```

This will establish a redirect from your .bash_profile to your .bashrc file.
## Step 3:
For Mac ```curl https://raw.githubusercontent.com/jeffjryan/bash_profile/master/bashrc.txt > .bashrc```

For Linux ```curl https://raw.githubusercontent.com/jeffjryan/bash_profile/master/linux.txt > .bashrc```

This will replace your existing .bashrc file with the one from this repo.
## Step 4:
Restart your terminal to pick up the env changes.
