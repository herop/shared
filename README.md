# Shared - Snippets that might change your worldview to the better
Share with anybody.

## What you always wanted to know about initial setup of **Magit** with **Github** but never bothered to ask.
.. or rather nobody is telling you (at least not the way I was able to grasp).

### First - The Groundwork

Create a folder (or of course use an existing one) for using with GitHub.

### Second - Dear GitHub, if you wouldn't mind

Create (or use an existing GitHub repo) and copy the code-url from GitHub.

### Third - Let's get to work Magit, shall we

+ Open the folder in Emacs and use "magit-init" (Magit will prepare your folder with anything needed further use)
+ Then, withing the Magit interface (magit-status if not already open) use "C" to clone the existing repo and fill in a name plus the URL above)

### Fourth - Where where we? Ahh, right

You should now be ready to "stage" "commit" and "push/pull" files from your folder.
