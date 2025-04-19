# Bài tập 4 - Dương Anh Kiên
# yêu cầu bài toán:
# - Nguồn dữ liệu: TMS.tnut.edu.vn
# - Tạo các bảng tuỳ ý (3nf)
# - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
 #  trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.

# các bước thực hiện:
# 1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
# 2. tạo file readme.md, edit online nó:
  # paste những ảnh chụp màn hình
  # gõ text mô tả cho ảnh đó

# BÀI LÀM:
## 1. tạo csdl cho hệ thống TKB
- để tạo csdl thì dữ liệu phải được chuẩn hóa về dạng 3nf
- Ta có các bảng sau: 
+ giaovien: #magv, tengv
+ lop: #malop, tenlop
+ monhoc: #mamon, tenmon
+ phong: #maphong, tenphong
+tkb: #id, @magv, @mamon, @malop, thu,  sotiet, giovao, Giora, ngay
## 2. Tạo các bảng trong csdl 
### 2.1. Bảng giáo viên
 ![image](https://github.com/user-attachments/assets/356af405-dfff-4917-894b-c0884bc87f8f)

2.2. Bảng lớp
 ![image](https://github.com/user-attachments/assets/4b72bc0c-a110-4831-8cbd-838783cf7526)

### 2.3. Bảng môn học 
 
![image](https://github.com/user-attachments/assets/125cf9bb-9ea6-4601-a783-0e895c412d48)

### 2.5. Bảng TKB 
 
![image](https://github.com/user-attachments/assets/ecc180d7-4101-482a-b381-0aaf8c9d80c9)

## 3. Nhập dữ liệu cho các bảng
### 3.1. nhập dữ liệu cho bảng giáo viên
 ![image](https://github.com/user-attachments/assets/28adc578-a83e-4a49-b36d-1442261d453e)

### 3.2. Nhập dữ liệu cho bảng lớp 
 
![image](https://github.com/user-attachments/assets/4f3482b6-f861-45a8-be5a-7d40c210e7cc)

### 3.3. Nhập dữ liệu cho bảng môn học 
 ![image](https://github.com/user-attachments/assets/113a4cff-013f-412b-a728-b4ff825017d1)


### 3.4. nhập dữ liệu cho bảng TKB
 
![image](https://github.com/user-attachments/assets/5505aba6-70df-44e5-88e3-d1152c9ea556)


## 4. Lệnh truy vấn

![image](https://github.com/user-attachments/assets/ff372768-6efc-4540-9600-75d1da53a1e1)

### - Kết quả:
![image](https://github.com/user-attachments/assets/2874af43-1288-4937-837b-9ba52247c718)

 
