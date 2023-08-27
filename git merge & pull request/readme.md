git merge - gộp 2 nhánh

ví dụ: 
có 3 nhánh: - main 
			- anpha được check out từ main và thêm 2 comit A & B
			- beta được check out từ main và thêm 2 comit C & D
--> merge nhánh anpha-> beta
	- git checkout beta
	- git merge alpha


* khi merge bị confic thì phải làm s
	- Tìm file conflix
		+ tím trong phần merge change hoặc trên terminal
	- Fix xong thì git add 
	- Commit
		+ git merge --continue --no-edit (ko custom commit đẩy lên)
		+ git merge --continue (custom commit đẩy lên)
	- Push lên


Tạo merge request
	- vào mục pull request 
		+ base : nhánh muôn merge  
		+ compare: nhánh merge
	- chọn 
	- r ấn tạo
	- git pull (fetch + merge)

Hoàn tác lệnh merge
	- git reset --hard + tên mã commit
	- git push -f 