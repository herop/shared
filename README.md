# Shared - Snippets that might change your worldview to the better
Share with anybody.

## What you always wanted to know about initial setup of **Magit** with **Github** but never bothered to ask.
.. or rather nobody is telling you (at least not the way I was able to grasp).

### First - The Groundwork

Create a (or use an existing, like "shared") folder for using with GitHub.

+ Magit will need to create a folder in order to clone a repository (see below)
+ I didn't find a way to just _connect_ an existing folder to a repo

### Second - Dear GitHub, if you wouldn't mind

Create (or use an existing GitHub repo) and copy the code-url from GitHub.

### Third - Let's get to work Magit, shall we

+ Open your folder (see above) in Emacs and use "magit-init" (Magit will prepare your folder with anything needed for further use)
+ Then, within the Magit interface (magit-status if not already open) use ´C´ to clone the existing repo (´?´ for a list of available commands inside Magit)
+ Fill in a name plus the URL from above, like so: shared/<new-folder-name> 

### Fourth - Where where we? Ahh, right

You should now be ready to "stage" "commit" and "push/pull" files from your folder.
