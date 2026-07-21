---
title: "Nhật ký tuần 11"
date: 2026-07-13
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

{{% notice info %}}
📅 **Thời gian:** 13/07/2026 – 19/07/2026
{{% /notice %}}

### Mục tiêu tuần 11

- Xây dựng cơ chế chơi game theo thời gian thực bằng WebSocket.
- Phát triển hệ thống ghép trận dựa trên chỉ số Elo.
- Cải thiện quy trình đăng ký tài khoản bằng Amazon Cognito với chức năng gửi lại mã OTP cho người dùng chưa xác thực.
- Tích hợp Amazon DynamoDB làm cơ sở dữ liệu chính cho ứng dụng web game.
- Xây dựng các AWS Lambda Function phục vụ xử lý logic của trò chơi.

### Công việc thực hiện

| Ngày | Nội dung                                                                                                                                                                                               | Bắt đầu    | Hoàn thành | Tài liệu tham khảo     |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ---------- | ---------------------- |
| 1    | Xây dựng cơ chế giao tiếp thời gian thực bằng **WebSocket** để đồng bộ trạng thái trận đấu giữa các người chơi.                                                                                        | 13/07/2026 | 14/07/2026 | Project Source Code    |
| 2    | Phát triển hệ thống **ghép trận theo Elo** và tính toán lại điểm Elo sau mỗi trận đấu.                                                                                                                 | 15/07/2026 | 16/07/2026 | Project Documentation  |
| 3    | Hoàn thiện quy trình đăng ký bằng **Amazon Cognito**, bổ sung chức năng **gửi lại mã OTP** cho tài khoản ở trạng thái **UNCONFIRMED**.                                                                 | 17/07/2026 | 17/07/2026 | Amazon Cognito         |
| 4    | Tích hợp **Amazon DynamoDB** để quản lý dữ liệu của web game và xây dựng các **AWS Lambda Function** gồm **Start Match**, **Process Game Engine**, **Save Deck**, **Handle Timeout** và **End Match**. | 18/07/2026 | 19/07/2026 | AWS Management Console |

### Kết quả đạt được

- Xây dựng thành công cơ chế **WebSocket**, cho phép người chơi tham gia các trận đấu theo thời gian thực với trạng thái được đồng bộ liên tục.
- Hoàn thiện hệ thống **ghép trận theo Elo**, giúp người chơi được ghép với đối thủ có trình độ tương đương và cập nhật điểm Elo sau mỗi trận thắng hoặc thua.
- Cải thiện quy trình xác thực của **Amazon Cognito** bằng cách bổ sung chức năng gửi lại mã OTP cho các tài khoản ở trạng thái **UNCONFIRMED**, nâng cao trải nghiệm đăng ký tài khoản.
- Tích hợp thành công **Amazon DynamoDB** làm cơ sở dữ liệu chính, đáp ứng yêu cầu truy vấn nhanh, khả năng mở rộng cao và tối ưu chi phí cho ứng dụng web game.
- Xây dựng các **AWS Lambda Function** phục vụ các chức năng cốt lõi của hệ thống, bao gồm:
  - **Start Match**
  - **Process Game Engine**
  - **Save Deck**
  - **Handle Timeout**
  - **End Match**
- Hoàn thiện kiến trúc backend theo hướng **serverless**, giúp hệ thống dễ mở rộng, giảm chi phí vận hành và đáp ứng tốt yêu cầu của một trò chơi nhiều người chơi theo thời gian thực.
