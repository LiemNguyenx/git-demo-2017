Script:
git init
git remote add https://github.com/LiemNguyenx/git-demo-2017
git checkout develop
// tao file create-to-remove
git add create-to-remove
git commit -m "add file"
git push origin develop
// xoa file 
git rm create-to-remove
git commit -m "rm file"
git push origin develop
// Tao pull request
// Kiem tra conflict
// Merge voi master
