/ Kiến thức Github cơ bản /

1. lý thuyết cơ bản về git

?Source control/ version control là gì?

+ hệ thống giúp lưu trữ mọi thay đổi của source code
+ Hỗ trợ nhiều người làm việc cùng lúc
+ Xem ai thay đổi code
+ Revert các thay đổi, đưa code về version cũ hơn, không lo mất code

2. Git là gì?

+ ra đời năm 2005
+ 3 khái niệm cơ bản: repo, commit, branch

* repo: là 1 dự án 
* commit: mỗi lần thay đổi code lưu lại 
* repo: local và remote
* branch: nhánh

// các lệnh cơ bản 

+ git init: tạo một repo trên máy

+ git clone: lấy từ trên máy về

+ git pull: đồng bộ từ mạng về máy

* git add: thêm file
* git commit: comment thao tác
* git push: đồng bộ từ máy trên mạng

- git log: xem trạng thái
- git log - decerate - graph - oneline


/* các bước tạo file và đẩy code lên github*/

git init
git add . 
git commit -m "add file"
git push origin...
git remote...
git push... origin...

// sửa file
git status
git add .
git commit -m "update file"
git push

// conflich

git pull 
select 
git add .
git commit -m "resolve conflich"
git push

// 



