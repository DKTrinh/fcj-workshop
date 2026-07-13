---
title: "Blog 2"
date: 2026-07-13
weight: 2
chapter: false
pre: " <b> 3.2. </b> "
---

 

# TRIỂN KHAI ỨNG DỤNG DOCKER LÊN AWS ECS VỚI FARGATE

Khi phát triển các ứng dụng web phức tạp, Docker là công cụ không thể thiếu để đảm bảo môi trường đồng nhất từ local lên production. Trong bài blog này, chúng ta sẽ khám phá cách triển khai các container Docker lên đám mây AWS sử dụng Amazon ECS (Elastic Container Service) kết hợp với AWS Fargate.

Các điểm chính cần nắm:

* **AWS Fargate là gì:** Là một serverless compute engine dành cho container. Thay vì phải tự tạo, cấu hình và bảo trì các máy ảo EC2, Fargate sẽ tự động cấp phát tài nguyên cần thiết để chạy container của bạn.
* **Tích hợp Amazon ECR (Elastic Container Registry):** ECR đóng vai trò như một Docker Hub riêng tư trên AWS, nơi bạn push các Docker image lên một cách bảo mật trước khi ECS kéo (pull) về để chạy.
* **Task Definition:** Đây là bản thiết kế (blueprint) cho ứng dụng của bạn, nơi bạn định nghĩa image nào sẽ được sử dụng, CPU/RAM cần bao nhiêu, và các biến môi trường (Environment Variables) kèm theo.
* **Khả năng mở rộng (Auto Scaling):** Fargate kết hợp với Application Load Balancer giúp ứng dụng tự động tăng số lượng container khi lượng truy cập tăng đột biến và giảm đi khi rảnh rỗi.
* **Tối ưu chi phí:** Bạn chỉ trả tiền cho lượng tài nguyên vCPU và bộ nhớ mà ứng dụng thực sự tiêu thụ trong lúc chạy.

Tính năng này đặc biệt hữu ích cho các dự án Backend (ví dụ như Spring Boot hoặc Node.js) đã được đóng gói bằng Docker, giúp team dev tập trung hoàn toàn vào việc viết code thay vì quản lý hạ tầng hệ thống.

...Hình ảnh...

...Link...

...Hướng dẫn...