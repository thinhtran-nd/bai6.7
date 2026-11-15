# bai6.7
# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Trần Xuân Thịnh
- **Mã số sinh viên:** 24810320263
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI 6.7: HỆ THỐNG QUẢN LÝ PHÒNG KHÁM & KÊ ĐƠN THUỐC (CLINIC & PHARMACY MANAGEMENT SYSTEM)
---

## KẾT QUẢ THỰC HÀNH
1. Màn hình Chính / Tổng quan hệ thống:
<img width="888" height="613" alt="GD" src="https://github.com/user-attachments/assets/6232284e-2bb0-4c83-9ddc-90e2deb4312d" />



2. Màn hình Quản lý Danh mục (CRUD - Thêm/Sửa/Xóa):
<img width="951" height="673" alt="CN1" src="https://github.com/user-attachments/assets/129ec5fa-b276-4d7b-aa1a-54918ecf45ac" />


3. Màn hình Thực thi Nghiệp vụ chính (Lập Hóa đơn / Bán hàng /Chấm công / Đặt phòng):
<img width="883" height="607" alt="CN4" src="https://github.com/user-attachments/assets/73cea167-eabf-4636-944d-24484bbb531d" />
<img width="841" height="711" alt="CN3" src="https://github.com/user-attachments/assets/258a3b80-8637-4e54-a7ff-796443654d91" />
<img width="995" height="652" alt="CN2" src="https://github.com/user-attachments/assets/5e4fbcb7-2140-4326-a134-0db9d88c51cc" />


4. Màn hình Báo cáo - Thống kê:
<img width="982" height="707" alt="KQ" src="https://github.com/user-attachments/assets/54edb59e-1545-4216-bbe6-1003dcf69d70" />


5. Minh họa An toàn Dữ liệu (Phòng chống SQL Injection / Báo lỗi Transaction Rollback):
<img width="986" height="710" alt="CN5" src="https://github.com/user-attachments/assets/6fc4c6bc-2152-4a32-8501-2820552a08a1" />




## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `SaleDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `Dbhelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
