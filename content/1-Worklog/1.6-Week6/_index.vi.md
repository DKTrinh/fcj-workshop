---
title: "Worklog Tuần 6"
date: 2024-07-20
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Triển khai hệ thống Xác thực (Authentication) và Phân quyền (Authorization).
* Hoàn thiện các luồng logic nghiệp vụ nâng cao của dự án.
* Bảo vệ tài nguyên, API khỏi các truy cập trái phép.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Cấu hình Security trên Backend <br> - Triển khai cơ chế xác thực bằng JWT cho API Đăng nhập/Đăng ký                                                                                       | 20/07/2026   | 20/07/2026      | Tài liệu Security & JWT                   |
| 3   | - Xây dựng giao diện Login/Register trên Frontend <br> - Xử lý lưu trữ Access Token an toàn (Cookie/Local Storage)                                                                          | 21/07/2026   | 21/07/2026      | Best Practices lưu trữ Token              |
| 4   | - Triển khai Phân quyền (RBAC) <br> - Thiết lập Private/Protected Routes trên Frontend chặn truy cập trái phép                                                                              | 22/07/2026   | 22/07/2026      | Tài liệu Route Guard                      |
| 5   | - Bảo vệ các Endpoint trên Backend theo Role <br> - Phát triển các logic nghiệp vụ nâng cao theo đặc tả (phê duyệt, thống kê...)                                                            | 23/07/2026   | 23/07/2026      | Tài liệu nghiệp vụ dự án                  |
| 6   | - **Thực hành:** <br>&emsp; + Cấu hình cơ chế Refresh Token gia hạn phiên đăng nhập <br>&emsp; + Kiểm tra chéo (Cross-check) phân quyền <br> - Review bảo mật cùng Mentor                   | 24/07/2026   | 24/07/2026      | Handling Refresh Token                    |

### Kết quả đạt được tuần 6:

* Hệ thống tính năng đăng nhập/đăng ký hoạt động ổn định và bảo mật.
* Luồng xác thực JWT giữa Frontend và Backend diễn ra trơn tru.
* Phân quyền (Admin, User...) được thực hiện chặt chẽ ở cả 2 phía: ẩn/hiện UI tương ứng và từ chối truy cập API nếu sai quyền.
* Giải quyết xong các bài toán nghiệp vụ phức tạp cốt lõi của ứng dụng.
* Cơ chế Refresh Token tự động làm mới phiên làm việc hiệu quả.