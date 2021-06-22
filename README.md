# GitHub, Git and SSH key set-up

- Download and install GitBash and Git version control onto your computer. [https://git-scm.com/](Git Download)
- Create a GitHub account by visiting the GitHub homepage [https://github.com/](GitHub)
- Open GitBash from start button as an administrator to generate an SSH key
- Type in `mkdir .ssh` to create a new directory
- Copy and paste `s0sh-keygen -t rsa -b 4096 -C "your_email@example.com"` replacing the email with your GitHub email. This is for windows only
- Type in Use `cd .ssh` into the terminal
- Keep pressing enter until a .pub appears
- Type in `cat id_rsa.pub` to find the content
- Copy and paste this .pub to GitHub. `Settings -> SSH keys -> New key`
  
# Summary image of the steps
- ![img.png](img.png) 

# Simple Steps for pushing code from PyCharm to GitHub
- ![img_1.png](img_1.png)