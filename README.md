### Phân công Nhiệm vụ Thiết kế Use Case

**Link Use case diagram:** https://drive.google.com/file/d/1AlGgOBkA-VMXcrtFmoZGLJOnVdcZ14gY/view

| Thành viên     | Phân hệ phụ trách | Nhiệm vụ chi tiết                                                                                               |
| :------------- | :---------------- | :-------------------------------------------------------------------------------------------------------------- |
| **Gia Khiêm**  | Guest & Xác thực  | Xây dựng Use Case cho Guest và quy trình Xác thực hệ thống (Authentication).                                    |
| **Huân Thành** | Student           | Thiết kế và hoàn thiện toàn bộ Use Case cho vai trò Người mắc các bệnh tâm lý (Student).                        |
| **Xuân Thịnh** | Expert            | Thiết kế và hoàn thiện toàn bộ Use Case cho vai trò Chuyên gia (Expert).                                        |
| **Công Toàn**  | Admin             | Thiết kế và hoàn thiện toàn bộ Use Case cho vai trò Quản trị viên (Admin).                                      |
| **Hoàng Phúc** | Tổng quan Dự án   | Tổng hợp hệ thống Use Case, chuẩn hóa cấu trúc, chỉnh sửa và kiểm duyệt (review) chất lượng trước khi bàn giao. |

### Phân công Nhiệm vụ Thiết kế Class Diagram

**Link Class diagram:** https://drive.google.com/file/d/1zqDX0qE_A3i6-uX_Isg5WP1cM45Qucd0/view?usp=sharing

| Thành viên     | Các lớp (Classes) phụ trách                                                      | Lĩnh vực chuyên môn                                 |
| :------------- | :------------------------------------------------------------------------------- | :-------------------------------------------------- |
| **Gia Khiêm**  | Transaction, Invoice, CommissionRate, SystemRevenue                              | Quản lý Giao dịch và Doanh thu hệ thống.            |
| **Huân Thành** | ChatRoom, Message, AISession, AIPromptLog                                        | Quản lý Tương tác Chat và Tích hợp AI.              |
| **Xuân Thịnh** | User, StudentProfile, ExpertProfile, AdminProfile, Certificate, Role, Permission | Quản lý Người dùng, Hồ sơ và Phân quyền.            |
| **Công Toàn**  | ScheduleConfig, TimeSlot, Appointment, PriceChangeRequest                        | Quản lý Lịch trình, Cuộc hẹn và Yêu cầu thay đổi.   |
| **Hoàng Phúc** | Category, ForumPost, Comment, Report, BanHistory                                 | Quản lý Diễn đàn, Nội dung, Danh mục và Kiểm duyệt. |
