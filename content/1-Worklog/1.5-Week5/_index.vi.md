---
title: "Worklog Tuần 5"
date: 2026-07-13
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Thiết lập kết nối (Call API) giữa Frontend và Backend.
* Quản lý trạng thái (State) xử lý luồng dữ liệu bất đồng bộ.
* Thay thế dữ liệu giả bằng dữ liệu thực từ CSDL.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Cài đặt thư viện HTTP Client (Axios/Fetch) <br> - Cấu hình Base URL <br> - Thiết lập Interceptors xử lý request/response chung                                                            | 13/07/2026   | 13/07/2026      | Tài liệu Axios                            |
| 3   | - Gọi API GET lấy dữ liệu danh sách/chi tiết <br> - Xử lý các trạng thái: <br>&emsp; + Loading <br>&emsp; + Success <br>&emsp; + Error                                                      | 14/07/2026   | 14/07/2026      | Tài liệu API (Swagger)                    |
| 4   | - Tích hợp API POST/PUT vào các Form <br> - Validate dữ liệu phía Client trước khi gửi <br> - Hiển thị lỗi từ Backend trả về                                                                | 15/07/2026   | 15/07/2026      | Form Validation Libraries                 |
| 5   | - Tích hợp API DELETE <br> - Cập nhật lại State (danh sách hiển thị) ngay sau khi CRUD thành công mà không cần reload trang                                                                 | 16/07/2026   | 16/07/2026      | State Management Guidelines               |
| 6   | - **Thực hành:** <br>&emsp; + Xử lý triệt để lỗi bảo mật CORS <br>&emsp; + Test luồng CRUD xuyên suốt (End-to-End) <br> - Báo cáo tiến độ với Mentor                                        | 17/07/2026   | 17/07/2026      | Tài liệu cấu hình CORS                    |

### Kết quả đạt được tuần 5:

* Ghép nối thành công Frontend và Backend, luồng dữ liệu chạy xuyên suốt.
* Nắm vững cách quản lý vòng đời component và xử lý bất đồng bộ (Async/Await).
* Hoàn thiện các thao tác CRUD cơ bản trên giao diện thực tế. Form nhập liệu có cảnh báo lỗi rõ ràng.
* Xử lý thành công các vấn đề kỹ thuật phát sinh khi kết nối, đặc biệt là lỗi CORS.
* Giao diện đã hiển thị dữ liệu động (Dynamic Data).