to delete locally
1 git branch -d dev 
2 git branch -d test

to delete remotely
2 git bush origin :dev 
2 git bush origin :test 

Tell me how to checkout another branch without commit changes.
git stash save #this will save the changes
git checkout name_of_branch
git stash pop #to get all your changes back when you get back to the old branch.
