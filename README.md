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

Tell me how to delete tag locally and remotely.
local
git tag -d v1.7
remote
git push origin --delete v1.7

![Screenshot from 2024-06-30 15-36-31](https://github.com/Abdelrahman120/Test2/assets/99983778/c1d33d00-dfd8-4bbd-8108-49c8b063176a)

