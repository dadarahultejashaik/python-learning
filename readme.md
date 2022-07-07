first error.
the commit pointed to the global git user not the local user.

I had to use  git commit --amend --reset-author for it to point to the local user. 
