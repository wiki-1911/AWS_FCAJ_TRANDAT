---
title: "Nhật ký tuần 12"
date: 2026-07-20
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

{{% notice info %}}
📅 **Thời gian:** 20/07/2026 – 26/07/2026
{{% /notice %}}

### Mục tiêu tuần 12

- Tăng cường bảo mật và quản lý hạ tầng AWS của dự án.
- Xây dựng hệ thống giám sát và theo dõi hoạt động của ứng dụng.
- Kiểm thử, tối ưu và hoàn thiện dự án.
- Hoàn thành workshop AWS và tài liệu dự án.
- Hoàn thành báo cáo thực tập.

### Công việc thực hiện

| Ngày | Nội dung                                                                                                                                                            | Bắt đầu    | Hoàn thành | Tài liệu tham khảo     |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- | ---------------------- |
| 1    | Tạo **IAM User** cho nhóm phát triển để quản lý Amazon Cognito; cấu hình **AWS KMS** và **AWS Secrets Manager** để quản lý khóa mã hóa và thông tin bí mật.         | 20/07/2026 | 21/07/2026 | AWS Management Console |
| 2    | Cấu hình **Amazon SQS** để kích hoạt Lambda **Post Match Worker**, kiểm tra quy trình xử lý bất đồng bộ sau mỗi trận đấu.                                           | 22/07/2026 | 22/07/2026 | AWS Management Console |
| 3    | Cấu hình **Amazon CloudWatch** để thu thập nhật ký (logs), metrics, lỗi Lambda và độ trễ; sử dụng **AWS X-Ray** để theo dõi luồng xử lý giữa API Gateway và Lambda. | 23/07/2026 | 24/07/2026 | AWS Management Console |
| 4    | Thực hiện kiểm thử toàn bộ hệ thống, hoàn thành workshop AWS, hoàn thiện dự án và viết báo cáo thực tập.                                                            | 25/07/2026 | 26/07/2026 | Project Documentation  |

### Kết quả đạt được

- Tạo thành công **IAM User** với quyền truy cập phù hợp để các thành viên trong nhóm quản lý tài nguyên **Amazon Cognito**.
- Cấu hình **AWS Key Management Service (AWS KMS)** và **AWS Secrets Manager** để lưu trữ, quản lý khóa mã hóa và thông tin nhạy cảm một cách an toàn.
- Tích hợp **Amazon SQS** với Lambda **Post Match Worker**, giúp xử lý các tác vụ sau trận đấu theo cơ chế bất đồng bộ, tăng khả năng mở rộng của hệ thống.
- Thiết lập **Amazon CloudWatch** để theo dõi logs, metrics, lỗi thực thi Lambda và độ trễ của ứng dụng.
- Sử dụng **AWS X-Ray** để theo dõi toàn bộ luồng xử lý giữa **Amazon API Gateway** và **AWS Lambda**, giúp nhanh chóng xác định nguyên nhân khi xảy ra lỗi và tối ưu hiệu năng hệ thống.
- Hoàn thành quá trình kiểm thử chức năng và tích hợp, đảm bảo hệ thống hoạt động ổn định.
- Hoàn thành toàn bộ workshop AWS và dự án web game theo kế hoạch.
- Hoàn thiện báo cáo thực tập, tổng hợp quá trình triển khai, các dịch vụ AWS đã sử dụng và kết quả đạt được trong suốt kỳ thực tập.
