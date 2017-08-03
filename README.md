# Git workshop - May the 4th - Melbourne
slides on the git workshop

# Github Education

Studenst can apply for an Education account with GitHub to access to unlimited private repositories.
Please see [here](https://education.github.com). Simply, apply for a student pack with you student email address.

# GitHub RStudio creating and setting up SSH keys
To avoid entering login details regularly, we can create SSH key pairs. This [GitHub Help] (https://help.github.com/articles/connecting-to-github-with-ssh/) page shows the process from command line. If you have never created SSH key pairs, you can skip straight to the section on [Generating a new SSH key and adding it to the ssh-agent] (https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/). Again all this is via the command line.

This can also be done from RStudio and is much simpler. For generating an SSH key pair, go to *Tools -> Global Options...* and the popup below will appear. Go to the *Git/SVN* section and click on *Create RSA Key...*. This will create a prompt asking you for a pass phrase. You can leave this empty if you don't want to be bothered with typing it for every request to your repository. This will create an ssh key and save it on the path displayed below *SSH RSA Key:*. After creating the Key pair, click on *View public key*, copy the public key and upload it to your GitHub account by following the step 2-8 at [Adding a new SSH key to your GitHub account](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)

[! Global Options... popup window] (https://support.rstudio.com/hc/en-us/article_attachments/203718287/Screen_Shot_2015-11-09_at_4.59.40_PM.png)

While writing this I (Dharmesh) realized that I had no clue of how to write up a README.md file on GitHub, so heres a quick [link](https://guides.github.com/features/mastering-markdown/) to get started.

