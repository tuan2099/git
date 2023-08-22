Thao tác với nhánh
- Đặt tên nhanh feature/ + chức năng
	+ git branch -> danh sách nhánh trên local
	+ git branch -r -> danh sách nhánh trên remote
	+ git branch -a  -> cả 2 danh sách local + remote
	+ git fetch -> nếu ko thấy nhánh đã tạo thì gõ lệnh
	+ git branch + tên nhánh mới -> tạo nhánh mới dựa trên nhánh cũ 
	+ git checkout -b + tên nhánh -> tạo 1 nhánh mới và di chuyển qua nhánh đó luôn
	+ git checkout + tên nhánh -> di chuyển về nhánh
	+ git switch -c + tên nhánh -> tạo nhánh mới giống checkout -b
	+ git branch -m + tên mới -> đổi tên nhánh hiện tại ở local
	+ git branch -m + tên cũ + tên mới -> đổi tên nhánh khác ở local
	+ git branch -D + tên nhánh -> xóa nhánh local
	+ git push origin --delete + tên nhánh -> xóa ở remote
	+ git push -u origin + tên nhánh ở local -> tạo nhánh giống vs nhánh ở local
	+ git fetch -p -> cập nhật local + remote sau khi bị xóa trên remote
