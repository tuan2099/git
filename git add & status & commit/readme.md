Git status: kiểm tra xem bạn đang ở nhánh nào

Khu vực làm việc với git 

1- Khu làm việc ( code ) --> ở local
2- Khu staging ( sau khi git add ) --> ở local 
3- Khu committed ( sau khi git commit ) --> ở local 
4- Khu remote ( sau khi dùng git push )	--> đã đc đưa lên


- Đưa file -> staging 
	+ git add + tên file -> đưa 1 file 
	+ git add . -> đưa tất cả
	+ git reset + tên file -> đưa file nhất định trước khi add
	+ git reset . đưa tất cả file về trc khi add
	
- Đưa file -> committed 
	+ git commit -m "text" -> commit code
	+ git restore --source= + tên mã commit + tên file hoàn tác những commit trong quá khứ 
	+ git rebase -i + mã commit -> sửa message 1 commit đã push 