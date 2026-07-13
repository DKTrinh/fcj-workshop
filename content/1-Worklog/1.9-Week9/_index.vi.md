---
title: "Worklog Tuần 9"
date: 2024-08-10
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Hoàn thiện tài liệu kỹ thuật (API, Setup Guide) chuẩn bị bàn giao.
* Đóng gói ứng dụng (Containerization) và thiết lập môi trường Cloud.
* Triển khai hệ thống lên môi trường thực tế (Production).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Hoàn thiện API Docs <br> - Cập nhật file `README.md` hướng dẫn setup, liệt kê các biến môi trường (ENV)                                                                                   | 10/08/2026   | 10/08/2026      | Markdown & API Documentation              |
| 3   | - Viết `Dockerfile` đóng gói Backend & Frontend <br> - Tạo `docker-compose.yml` chạy đồng bộ hệ thống                                                                                       | 11/08/2026   | 11/08/2026      | Tài liệu Docker                           |
| 4   | - Thiết lập máy chủ Cloud (VPS/AWS EC2) <br> - Cài đặt môi trường server (Docker, Nginx) và cấu hình bảo mật Firewall                                                                       | 12/08/2026   | 12/08/2026      | Hướng dẫn triển khai Cloud                |
| 5   | - Thiết lập quy trình CI/CD cơ bản (GitHub Actions) tự động hóa build và push code                                                                                                          | 13/08/2026   | 13/08/2026      | CI/CD Pipeline Docs                       |
| 6   | - **Thực hành:** <br>&emsp; + Deploy hệ thống lên server <br>&emsp; + Cấu hình Nginx Reverse Proxy và trỏ Domain <br> - Chạy Sanity Test trên bản live                                      | 14/08/2026   | 14/08/2026      | Nginx Configuration & DNS                 |

### Kết quả đạt được tuần 9:

* Bộ tài liệu kỹ thuật được cập nhật đầy đủ, rõ ràng.
* Đóng gói thành công hệ thống bằng Docker, loại bỏ vấn đề xung đột môi trường.
* Khởi tạo và cấu hình thành công máy chủ đám mây an toàn.
* Triển khai thành công ứng dụng ra Internet, người dùng có thể truy cập qua tên miền.
* Xây dựng được luồng CI/CD cơ bản tiết kiệm thời gian release.