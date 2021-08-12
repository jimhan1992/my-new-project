-	1	Chuyển Terminal đến thư mục "my-new-project" vừa tạo và sử dụng lệnh git init để khởi tạo Repository mới.
-	2	Tiếp theo, sử dụng lệnh git remote add origin để kết nối tới Remote Repository (chú ý sử dụng dúng đường dẫn của Repository mà bạn vừa tạo):
		
		git remote add origin https://github.com/codegym-vn/my-new-project.git
		
-	3	 Sử dụng câu lệnh git add để đưa file README.md vào trong chỉ mục của Git.	
			
			git add README.md
			
-	4	Sử dụng câu lệnh git commit để lưu lại các thay đổi.

			git commit -m "Add README.md file"
			
		Trong câu lệnh trên, tuỳ chọn -m được sử dụng để ghi một "message" đánh dấu cho thay đổi vừa rồi. Nó giải thích rằng chúng ta vừa thêm một file README.md mới. Chúng ta cần ghi các thông điệp có ý nghĩa để dễ dàng cho việc hiểu và cộng tác nhóm sau này.
-	5	Sử dụng câu lệnh git push để đẩy các thay đổi ở Local Repository lên trên Remote Repository kkkkkkkkkkk
	
		git push origin master
		
	Như vậy là chúng ta đã hoàn thành một luồng làm việc cơ bản với GitHub. Local Repository và Remote Repository đã được đồng bộ với nhau.
	
	