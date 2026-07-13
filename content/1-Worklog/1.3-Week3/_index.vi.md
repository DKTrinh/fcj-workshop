---
title: "Worklog Tuần 3"
date: 2026-06-29
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Khởi tạo dự án Backend (Spring Boot/Node.js) và kết nối Cơ sở dữ liệu.
* Xây dựng các RESTful API cơ bản phục vụ thao tác CRUD.
* Viết tài liệu mô tả API (API Documentation).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Khởi tạo project Backend <br> - Cấu hình file properties/env kết nối Database <br> - Thêm các dependencies/packages cần thiết                                                             | 29/06/2026   | 29/06/2026      | Tài liệu Framework Backend                |
| 3   | - Xây dựng các lớp Thực thể (Entity/Model) mapping với CSDL <br> - Tạo các lớp Repository/DAO để tương tác với cơ sở dữ liệu                                                                | 30/06/2026   | 30/06/2026      | Tài liệu ORM (JPA/Sequelize)              |
| 4   | - Thiết kế Data Transfer Object (DTO) <br> - Xây dựng tầng Service để xử lý logic nghiệp vụ (Business logic)                                                                                | 01/07/2026   | 01/07/2026      | Clean Code & Architecture                 |
| 5   | - Triển khai tầng Controller, định nghĩa các endpoints (GET, POST, PUT, DELETE) <br> - Xử lý bắt lỗi (Exception Handling) <br> - Chuẩn hóa format response trả về                           | 02/07/2026   | 02/07/2026      | REST API Design Guidelines                |
| 6   | - **Thực hành:** <br>&emsp; + Tích hợp Swagger tạo tài liệu API tự động <br>&emsp; + Dùng Postman test các API <br> - Review code với Mentor                                                | 03/07/2026   | 03/07/2026      | Tài liệu Swagger & Postman                |

### Kết quả đạt được tuần 3:

* Cấu hình và khởi chạy thành công dự án Backend dưới môi trường local, kết nối thông suốt với cơ sở dữ liệu.
* Áp dụng đúng kiến trúc phân tầng (Controller - Service - Repository) trong lập trình.
* Hoàn thành bộ API CRUD cho các tính năng cốt lõi.
* Xử lý tốt các ngoại lệ (Exception), đảm bảo API trả về mã lỗi (HTTP Status Code) và thông báo chuẩn xác.
* Tài liệu hóa toàn bộ API bằng Swagger, sẵn sàng cho việc ghép nối Frontend.