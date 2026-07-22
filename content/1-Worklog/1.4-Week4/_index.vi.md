---
title: "Worklog Tuần 4"
date: 2026-07-22
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---


### Mục tiêu tuần 4:

* Hiểu cách lưu và truy xuất dữ liệu phân tích CV
* Tìm hiểu API Gateway và Lambda pattern cho các route AI
* Bắt đầu nghiên cứu cấu trúc prompt Amazon Bedrock

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ 6 | - Xem lại các trường DynamoDB cần lưu cho kết quả AI như CV score, extracted skills, projects và suggested roles | 08/05/2026 | 08/05/2026 | |
| Thứ 7 | Ngày nghỉ | 09/05/2026 | 09/05/2026 | |
| Chủ nhật | Ngày nghỉ | 10/05/2026 | 10/05/2026 | |
| Thứ 2 | - Mapping các route AI như analyze_cv, create_interview và submit_answer với trách nhiệm backend | 11/05/2026 | 11/05/2026 | |
| Thứ 3 | - Tìm hiểu Amazon Bedrock cơ bản, model access, cấu trúc request/response và cách dùng Nova Lite | 12/05/2026 | 12/05/2026 | |
| Thứ 4 | - Phác thảo prompt cho CV context, output rules, JSON format, thang điểm và fallback handling | 13/05/2026 | 13/05/2026 | |
| Thứ 5 | - Chuẩn bị checklist tích hợp AI đầu tiên cho giai đoạn triển khai đồ án. | 14/05/2026 | 14/05/2026 | |
### Kết quả đạt được tuần 4:
* Phân định kiến trúc Backend & API Routing: 
  * Mapping rõ ràng trách nhiệm của Backend qua các route chính
* Nghiên cứu & Thiết kế Prompt trên Amazon Bedrock:
  * Nắm vững cơ chế hoạt động của Amazon Bedrock, cấp quyền truy cập mô hình (Model Access) và cấu trúc Request/Response của Nova Lite
  * Phác thảo bộ Prompt chuyên sâu bao gồm: ngữ cảnh CV, quy tắc đầu ra, định dạng dữ liệu trả về,thang điểm đánh giá.

