# git-command




git init
git --version
git add .
git commit -m "adding files for project llika"

//wrong way// 
git remote rm origin https://github.com/IgnacioGans/llika-remking/tree/master/base_remking
//good way//
git remote rm origin

git remote add origin https://github.com/IgnacioGans/llika-remking

git push -u origin master

//if have trouble, type this//
git push --force origin master


//windows for show all history command prompt//
doskey /History
