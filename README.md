*** create branch
git branch -m <new-branch>

*** checkout new branch 
git checkout -b <new-branch>

*** checkout branch exists
git checkout <branch-exists>

*** pull code to branch
git pull origin <branch-parent>

*** push code
git push origin <branch>

note: Trước khi đẩy code của mình lên thì phải pull code từ nhánh parent trước
Trường hợp bạn đang code thì bạn có thể dùng stash 

****
git stash (dùng để lưu lại những code của bạn đang code)
sau khi stash thì bạn có thể pull
tiếp tục bạn sử dụng:
git stash pop (dùng để lấy ra những thứ bạn đã code trước đó)