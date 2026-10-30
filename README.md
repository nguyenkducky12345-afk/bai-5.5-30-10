# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Nguyễn Khánh Đức
- **Mã số sinh viên:** 24810320072
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI TẬP 5.5: HỆ THỐNG QUẢN LÝ QUY TRÌNH XUẤT - NHẬP KHO
NGUYÊN VẬT LIỆU (INVENTORY MANAGEMENT)

---

## KẾT QUẢ THỰC HÀNH

- Giao diện chính
<img width="969" height="696" alt="Screenshot 2026-10-30 094112" src="https://github.com/user-attachments/assets/4e4e13e8-7848-4b1b-b998-c19c78169574" />

- Giao diện phần quản lí/cảnh báo tồn kho
<img width="965" height="692" alt="Screenshot 2026-10-30 094139" src="https://github.com/user-attachments/assets/e7856d75-9fb6-4e63-a3b0-d37190262e4a" />

- Lỗi khi nhập dữ liệu kho khi chưa có mặt hàng nào
<img width="968" height="695" alt="Screenshot 2026-10-30 094127" src="https://github.com/user-attachments/assets/ba9898ca-108c-480b-96cb-e0c7ca25ce1a" />

- Thêm các mặt hàng vào phiếu
<img width="973" height="690" alt="Screenshot 2026-10-30 094155" src="https://github.com/user-attachments/assets/91c65475-c6ef-4d9c-b8b9-970624aeed63" />

- Xác nhận lưu trữ mặt hàng vào phiếu
<img width="964" height="689" alt="Screenshot 2026-10-30 094202" src="https://github.com/user-attachments/assets/aa0dbab3-fedd-4a93-9337-3b1dca2b3f82" />

## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `InventoryDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `Dbhelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
