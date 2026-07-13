---
title: "Worklog Tuần 2"
date: 2026-06-22
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

* Phân tích chi tiết logic nghiệp vụ và các luồng hoạt động (user flow) của hệ thống.
* Thiết kế hoàn chỉnh kiến trúc dữ liệu và sơ đồ quan hệ thực thể (ERD).
* Khởi tạo cơ sở dữ liệu và chuẩn bị dữ liệu mẫu (mock data).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Phân tích chi tiết yêu cầu (Requirements Analysis) <br> - Xác định các tác nhân (Actors) <br> - Vẽ sơ đồ Use-Case cho các tính năng chính                                                 | 22/06/2026   | 22/06/2026      | Tài liệu đặc tả (SRS)                     |
| 3   | - Thiết kế Sơ đồ quan hệ thực thể (ERD) <br>&emsp; + Xác định các thực thể (Entities) <br>&emsp; + Định nghĩa thuộc tính (Attributes) <br>&emsp; + Thiết lập mối quan hệ (1-1, 1-N, N-N)    | 23/06/2026   | 23/06/2026      | Công cụ thiết kế (Draw.io/dbdiagram)      |
| 4   | - Lựa chọn hệ quản trị cơ sở dữ liệu phù hợp <br> - Sử dụng Docker để khởi tạo container chứa Database chạy dưới local                                                                      | 24/06/2026   | 24/06/2026      | Tài liệu Docker & Database                |
| 5   | - Viết các câu lệnh SQL (DDL) để tạo bảng <br> - Thiết lập các ràng buộc toàn vẹn: <br>&emsp; + Khóa chính (PK) <br>&emsp; + Khóa ngoại (FK) <br>&emsp; + Unique, Not Null                  | 25/06/2026   | 25/06/2026      | Tài liệu thiết kế CSDL                    |
| 6   | - **Thực hành:** <br>&emsp; + Chạy script tạo CSDL <br>&emsp; + Viết script tạo dữ liệu mẫu (Seeder) <br> - Trình bày và Review thiết kế Database với Mentor                                | 26/06/2026   | 26/06/2026      | Nhật ký công việc cá nhân                 |

### Kết quả đạt được tuần 2:

* Nắm vững toàn bộ luồng nghiệp vụ cốt lõi mà hệ thống cần giải quyết.
* Hoàn thiện bản thiết kế sơ đồ cơ sở dữ liệu (ERD) và đã được Mentor phê duyệt.
* Khởi tạo thành công cơ sở dữ liệu trên môi trường local với đầy đủ các bảng và ràng buộc chặt chẽ.
* Tạo sẵn bộ dữ liệu mẫu (mock data) đầy đủ, sẵn sàng cho việc kết nối và viết API ở tuần tiếp theo.
* Xác định rõ ràng các rủi ro về mặt lưu trữ và có phương án mở rộng (scale) các bảng trong tương lai.