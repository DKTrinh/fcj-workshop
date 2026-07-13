---
title: "Blog 1"
date: 2026-07-13
weight: 1
chapter: false
pre: " <b> 3.1. </b> "
---

 

# SESSION POLICIES TRONG AMAZON EKS POD IDENTITY

Amazon EKS Pod Identity vừa bổ sung tính năng session policies, cho phép bạn thu hẹp quyền IAM một cách linh hoạt và chính xác cho từng pod mà không cần tạo thêm nhiều IAM roles riêng biệt. Đây là bước tiến quan trọng giúp áp dụng nguyên tắc least privilege hiệu quả hơn trong môi trường Kubernetes quy mô lớn.

Các điểm chính cần nắm:

* Session policy là một IAM policy inline được chỉ định khi tạo hoặc cập nhật Pod Identity association.
* Quyền hiệu quả bằng giao giữa permissions của IAM role và session policy. Nói cách khác, session policy chỉ có thể thu hẹp quyền, không thể mở rộng quyền.
* Giúp tránh tình trạng over-permissioning khi một IAM role được chia sẻ cho nhiều workloads với nhu cầu khác nhau.
* Hỗ trợ cả môi trường same-account và cross-account thông qua IAM role chaining.
* Giảm đáng kể số lượng IAM roles cần quản lý, đồng thời giúp tránh chạm giới hạn quota IAM trong cluster lớn.
* Có thể cấu hình dễ dàng qua AWS Management Console, AWS CLI hoặc AWS SDK khi tạo association giữa Kubernetes ServiceAccount và IAM role.

Tính năng này đặc biệt hữu ích khi nhiều ứng dụng chạy cùng một IAM role nhưng lại cần giới hạn quyền khác nhau. Ví dụ, một pod chỉ được phép đọc một S3 bucket cụ thể, trong khi pod khác chỉ được phép gọi một nhóm API nhất định.

...Hình ảnh...

...Link...

...Hướng dẫn...