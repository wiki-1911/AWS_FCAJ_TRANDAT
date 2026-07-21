---
title: "Sự kiện 1"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 4.1. </b> "
---

# Cảm nhận về sự kiện "FCAJ Community Day"

## Mục đích của sự kiện

**FCAJ Community Day** được tổ chức nhằm chia sẻ những kiến thức thực tiễn về **Điện toán đám mây (AWS)** và **Trí tuệ nhân tạo (AI)**. Sự kiện mang đến góc nhìn toàn diện về cách xây dựng, triển khai và vận hành các hệ thống AI trong môi trường doanh nghiệp, đồng thời tạo cơ hội để cộng đồng AWS gặp gỡ, giao lưu và học hỏi lẫn nhau.

---

## Diễn giả tham gia

Sự kiện có sự góp mặt của nhiều chuyên gia và thành viên giàu kinh nghiệm trong lĩnh vực Cloud và AI:

- **Đức Đào** – Solution Architect tại Cloud Kinetics
- **Vy Lâm** – Senior Business Systems Analyst tại VPBank
- **Phạm Ngô Hải Anh** – Cloud Consulting Specialist tại G-AsiaPacific Vietnam, AWS Community Builder
- **Nguyễn Tuấn Thịnh** – DevOps Engineer tại First Cloud AI Journey
- **Đội VIB** – Nhóm tham gia LotusHacks 2026
- **Trương Tịnh** – Platform Engineer tại GoTymeX

---

## Những nội dung nổi bật

### AI không hoàn toàn mang tính xác định

Một chủ đề rất thú vị được chia sẻ là việc thiết lập **Temperature = 0** không đồng nghĩa với việc mô hình AI sẽ luôn tạo ra kết quả giống nhau. Nguyên nhân đến từ sai số trong quá trình tính toán dấu chấm động trên GPU cũng như cách các nhà cung cấp tối ưu hệ thống xử lý. Qua đó, em hiểu rằng các mô hình AI hiện nay vẫn mang bản chất xác suất và cần được thiết kế để chấp nhận một mức sai số nhất định.

### Kiến trúc Multi-Agent trong doanh nghiệp

Các diễn giả giới thiệu mô hình **Multi-Agent AI**, trong đó nhiều Agent chuyên biệt cùng phối hợp để giải quyết một bài toán thay vì chỉ sử dụng một mô hình duy nhất. Mỗi Agent đảm nhận một lĩnh vực riêng như tài chính, thị trường, nhân sự, rủi ro hoặc tuân thủ, sau đó kiểm tra chéo lẫn nhau để nâng cao độ chính xác và khả năng kiểm soát của hệ thống.

### Amazon Q và trợ lý AI cho doanh nghiệp

Buổi chia sẻ cũng giới thiệu **Amazon Q** như một trợ lý AI dành cho doanh nghiệp, có khả năng tổng hợp dữ liệu nội bộ và hỗ trợ tự động hóa nhiều công việc như ghi biên bản họp, soạn email, quản lý công việc hay hỗ trợ quản lý dự án.

### Tối ưu hạ tầng với Amazon CloudFront

Một nội dung khác tập trung vào **Amazon CloudFront**, giải thích cách dịch vụ này giúp tăng tốc website, giảm chi phí vận hành và tăng cường bảo mật thông qua các công nghệ như AWS WAF, DDoS Protection, Origin Cloaking và HTTP/3.

### Chia sẻ từ LotusHacks 2026

Đội thi VIB đã chia sẻ hành trình phát triển dự án **UTMorpho** trong vòng 36 giờ tại cuộc thi LotusHacks. Dự án sử dụng AI để chuyển đổi bản phác thảo giao diện thành Wireframe, đồng thời trình bày những khó khăn trong việc kiểm soát đầu ra của AI và tối ưu số lượng token sử dụng.

### Context quyết định chất lượng của AI

Một thông điệp quan trọng được nhấn mạnh là **AI chỉ thực sự hiệu quả khi được cung cấp đầy đủ ngữ cảnh**. Các diễn giả giới thiệu phương pháp xây dựng Prompt dựa trên bốn thành phần:

- Mục tiêu (Objective)
- Thông tin liên quan (Relevant Information)
- Các ràng buộc (Constraints)
- Tiêu chí thành công (Success Criteria)

Cách tiếp cận này giúp AI tạo ra các phản hồi chính xác và phù hợp hơn với yêu cầu thực tế.

---

## Những điều em học được

Sau khi tham gia sự kiện, em rút ra nhiều bài học hữu ích.

### AI luôn tồn tại tính xác suất

Em nhận thấy rằng AI không phải lúc nào cũng đưa ra kết quả giống nhau. Vì vậy, khi xây dựng các ứng dụng AI trong thực tế, cần có cơ chế kiểm tra, đánh giá và xác thực kết quả thay vì hoàn toàn phụ thuộc vào mô hình.

### Tư duy thiết kế hệ thống

Đối với những bài toán phức tạp, việc phân chia nhiệm vụ cho nhiều Agent chuyên biệt sẽ giúp hệ thống dễ mở rộng, dễ kiểm soát và có độ tin cậy cao hơn so với chỉ sử dụng một mô hình duy nhất.

### Tối ưu hệ thống Cloud

CloudFront không chỉ giúp tăng tốc website mà còn góp phần giảm chi phí, nâng cao khả năng bảo mật và bảo vệ hệ thống backend khỏi các truy cập trực tiếp.

---

## Khả năng áp dụng vào dự án

Những kiến thức thu được từ sự kiện có thể áp dụng trực tiếp vào quá trình phát triển dự án của em.

- Áp dụng kiến trúc Multi-Agent cho các bài toán AI phức tạp trong tương lai.
- Xây dựng Prompt theo cấu trúc rõ ràng gồm mục tiêu, ngữ cảnh, ràng buộc và kết quả mong muốn.
- Tận dụng Amazon CloudFront để tối ưu hiệu năng, giảm băng thông và tăng cường bảo mật cho ứng dụng.
- Quan tâm đến yếu tố bảo mật và tối ưu chi phí ngay từ giai đoạn thiết kế hệ thống thay vì chỉ xử lý khi dự án hoàn thành.

---

## Cảm nhận sau khi tham dự

Tham gia **FCAJ Community Day** là một trong những trải nghiệm đáng nhớ nhất trong quá trình thực tập của em. Không chỉ được cập nhật các xu hướng mới về Cloud Computing và AI, em còn có cơ hội lắng nghe những chia sẻ thực tế từ các chuyên gia đang làm việc trong ngành.

Thông qua các bài trình bày, em hiểu rõ hơn cách các doanh nghiệp xây dựng và vận hành những hệ thống Cloud quy mô lớn, cũng như vai trò của AI trong việc giải quyết các bài toán thực tế. Những kiến thức này giúp em kết nối tốt hơn giữa lý thuyết đã học ở trường với môi trường làm việc chuyên nghiệp.

Bên cạnh đó, sự kiện cũng là cơ hội để em gặp gỡ và giao lưu với cộng đồng AWS. Những câu chuyện, kinh nghiệm và tinh thần sẵn sàng chia sẻ của các diễn giả đã tạo thêm động lực để em tiếp tục học tập, nghiên cứu và theo đuổi lĩnh vực Cloud Computing trong tương lai.

---

## Một số hình ảnh tại sự kiện

![Event1](/images/4-Events/Event1a.png)

![Event1](/images/4-Events/Event1b.png)
