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

![Alt text](https://www.google.com/imgres?q=imgs&imgurl=https%3A%2F%2Fimgs.ie%2Fwp-content%2Fuploads%2F2020%2F08%2FIMGS_Logo_White-1024x357.png&imgrefurl=https%3A%2F%2Fimgs.ie%2F&docid=LAtwU6uVfVaLmM&tbnid=ALVVp6v6nApj4M&vet=12ahUKEwiF3qKxroOHAxWlcKQEHcBhDL8QM3oECEwQAA..i&w=1024&h=357&hcb=2&ved=2ahUKEwiF3qKxroOHAxWlcKQEHcBhDL8QM3oECEwQAA)
