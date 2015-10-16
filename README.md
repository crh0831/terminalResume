# terminalResume

A command line Resume for sysadmins

Ever see a chef's resume?  Maybe in the format of a menu with photos of plated meals and skills instead of prices?
How about an accountant's with education and references listed in a ledger format?
What are we System Administrator's to do?  We that spend all day in a terminal window typing white (or green) text onto a black screen?
How can we make our Resumes eye catching or at least memorable?

Forked from Daniel Hauck's inspired [terminalCV](https://github.com/hauckd/terminalCV), I wanted to change the 'CV' (Curriculum Vitæ) to 'Resume' and add and
remove some features to better suit me.

# See it in action

Mine (a work in progress): [http://resume.planethawleywood.com](http://resume.planethawleywood.com)

# Usage
terminalResume is a python script that uses jinja2 to render a html-template with javascript stuff in it.  After it is rendered, you just need to upload it to
your webroot or subdirectory.

To use it, clone the repository and install requirements with pip:

    $  git clone git@github.com:crh0831/terminalResume.git && cd terminalResume
    $  sudo pip install -r requirements.txt

Modify the `about.yml` with your favorite text editor (your favorite editor is vim, right?)

And finally render:

    $  python render.py

If everything worked you can just upload the directory www to your DocumentRoot 
  
# Jquery-Terminal
terminalResume makes use of J. Cubics [JQuery-Terminal](http://terminal.jcubic.pl/) 
Thanks for this!

### Disclaimer

This is my first fork on github - let me know if I'm doing something wrong :)
