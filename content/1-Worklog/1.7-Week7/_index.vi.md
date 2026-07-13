---
title: "Worklog Tuần 7"
date: 2024-07-27
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Rà soát và tối ưu hóa mã nguồn (Refactoring) đạt chuẩn Clean Code.
* Tối ưu hiệu năng truy vấn Database và tốc độ API.
* Tinh chỉnh Giao diện (UI) và Trải nghiệm người dùng (UX).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Review cấu trúc code Frontend & Backend <br> - Gom nhóm các hàm lặp lại thành helpers/utils chung (chuẩn DRY)                                                                             | 27/07/2026   | 27/07/2026      | Clean Code Guidelines                     |
| 3   | - Tối ưu Backend: <br>&emsp; + Xử lý lỗi N+1 query <br>&emsp; + Đánh index cho các bảng CSDL                                                                                                | 28/07/2026   | 28/07/2026      | SQL Optimization                          |
| 4   | - Tối ưu Frontend: <br>&emsp; + Tách nhỏ component phức tạp <br>&emsp; + Viết Custom Hooks quản lý logic dùng chung                                                                         | 29/07/2026   | 29/07/2026      | Frontend Best Practices                   |
| 5   | - Tinh chỉnh UI/UX: <br>&emsp; + Thêm Loading Skeletons/Spinners <br>&emsp; + Tích hợp Toast Notifications thông báo kết quả                                                                | 30/07/2026   | 30/07/2026      | Tài liệu UX Design                        |
| 6   | - **Thực hành:** <br>&emsp; + Kiểm tra độ tương thích đa trình duyệt (Cross-browser) <br>&emsp; + Chốt bản code chuẩn bị cho Testing <br> - Họp Mentor đánh giá source code                 | 31/07/2026   | 31/07/2026      | Nhật ký công việc cá nhân                 |

### Kết quả đạt được tuần 7:

* Mã nguồn trở nên gọn gàng, có tính module hóa cao, dễ bảo trì.
* Xử lý triệt để các vấn đề hiệu năng, thời gian phản hồi của API nhanh hơn đáng kể.
* Trải nghiệm người dùng (UX) được nâng cấp nhờ phản hồi trực quan (loading, toast).
* Giao diện (UI) hiển thị nhất quán trên các trình duyệt và màn hình khác nhau.
* Codebase đã sẵn sàng để bước sang giai đoạn Kiểm thử.