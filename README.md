# Baitap4
bai tap 4: (sql server)
- yêu cầu bài toán:
 - Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
 - Nguồn dữ liệu: TMS.tnut.edu.vn
 - Tạo các bảng tuỳ ý (3nf)
 - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
   trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.
- các bước thực hiện:
1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
2. tạo file readme.md, edit online nó:
   paste những ảnh chụp màn hình
   gõ text mô tả cho ảnh đó
- Gợi ý:
  sử dung tms => dữ liệu thô => tiền xử lý => dữ liệu như ý (3nf)
  tạo các bảng với struct phù hợp
  insert nhiều rows từ excel vào cửa sổ edit dữ liệu 1 table (quan sát thì sẽ làm đc)
  # Tạo Bảng
  ## Bảng GV
 ![Ảnh chụp màn hình 2025-04-15 183750](https://github.com/user-attachments/assets/42fc87e5-0246-4d71-be15-9cdd4d5d8b20)

  ## Bảng Null
![Ảnh chụp màn hình 2025-04-15 180042](https://github.com/user-attachments/assets/6ee775b6-821b-4a74-ae2f-3c6d92629ed0)

  ## Bảng Lớp
![Ảnh chụp màn hình 2025-04-15 183734](https://github.com/user-attachments/assets/aa5ceebb-9a4f-4b5c-9640-6a01e35bc076)

  ## Bảng Null
![Ảnh chụp màn hình 2025-04-15 180120](https://github.com/user-attachments/assets/f50f7d2e-94c9-44eb-9c84-04bcd188cc9c)
  ## Bảng Môn học
![Ảnh chụp màn hình 2025-04-15 183718](https://github.com/user-attachments/assets/46cff3dd-4b66-49b7-8e92-af24a2b7f2a3)

  ## Bảng NUll
![Ảnh chụp màn hình 2025-04-15 180131](https://github.com/user-attachments/assets/540054d9-a48d-4cde-86eb-7584cbc49bec)

  ## Bảng TKB
![Ảnh chụp màn hình 2025-04-15 183658](https://github.com/user-attachments/assets/543aade1-92ff-42ba-9c64-053dab5d2a84)

  ## Bảng NULL
![Ảnh chụp màn hình 2025-04-15 183648](https://github.com/user-attachments/assets/7b9358c4-92cd-4c71-8b51-c9195e7b59b2)

  ## Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
  ## trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.
  ![Ảnh chụp màn hình 2025-04-15 180335](https://github.com/user-attachments/assets/276c7e14-7719-461b-b87f-93bbe908efb9)

  ![Ảnh chụp màn hình 2025-04-15 180704](https://github.com/user-attachments/assets/0ab09bb9-b75d-4e9a-8e95-1607d6f42905)

