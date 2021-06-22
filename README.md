# GitHub, Git and SSH key set-up

## Download and Installation
- Download and install GitBash and Git version control onto your computer. [https://git-scm.com/]
- Create a GitHub account by visiting the GitHub homepage [https://github.com/]
## Open terminal and create directory  
- Open GitBash from start button as an administrator to generate an SSH key
- Type in `mkdir .ssh` to create a new directory
## Create the SSH key  
- Copy and paste `s0sh-keygen -t rsa -b 4096 -C "your_email@example.com"` replacing the email with your GitHub email. This is for windows only
- Type in Use `cd .ssh` into the terminal
- Keep pressing enter until a .pub appears
- Type in `cat id_rsa.pub` to find the content
## Using the key  
- Copy and paste this .pub to GitHub. `Settings -> SSH keys -> New key`
  
# Summary image of the steps
Diagram showing the link between github, git and gitbash using SSH keys.
- ![img.png](img.png) 

# Simple Steps for pushing code from PyCharm to GitHub
Simplified steps for pushing code.
- ![img_1.png](img_1.png)
