---
title: "Worklog Tuần 9"
date: 2026-07-22
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---


### Mục tiêu tuần 9:

* Xây dựng prompt đánh giá CV bằng Amazon Bedrock/Nova Lite
* Trích xuất và chuẩn hóa skills, projects, experience, certificates, suggested roles và score
* Làm cho AI response ổn định để backend và Dashboard sử dụng

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ 6 | - Thiết kế prompt phân tích CV và tiêu chí chấm điểm mức độ sẵn sàng của ứng viên. | 12/06/2026 | 12/06/2026 | |
| Thứ 7 | Ngày nghỉ | 13/06/2026 | 13/06/2026 | |
| Chủ nhật | Ngày nghỉ | 14/06/2026 | 14/06/2026 | |
| Thứ 2 | - Xây dựng prompt template cho Bedrock/Nova Lite để trích xuất CV summary, skills, projects, experience và certificates | 15/06/2026 | 15/06/2026 | |
| Thứ 3 | - Chuẩn hóa JSON output cho score, suggested roles, strengths, weaknesses và recommendations | 16/06/2026 | 16/06/2026 | |
| Thứ 4 | - Test prompt với nhiều CV mẫu và sửa lỗi field không đồng nhất hoặc response không đúng JSON | 17/06/2026 | 17/06/2026 | |
| Thứ 5 | - Tinh chỉnh prompt phân tích CV và ghi chú fallback structure khi AI response lỗi | 18/06/2026 | 18/06/2026 | |

### Kết quả đạt được tuần 9:

* Chuẩn hóa Định dạng Đầu ra (JSON Output Schema):
  * Thống nhất cấu trúc dữ liệu JSON trả về với đầy đủ các trường thông tin: điểm số (score), vị trí đề xuất (suggested roles), điểm mạnh (strengths), điểm yếu (weaknesses) và gợi ý phát triển (recommendations)

* Kiểm thử Thực tế & Tối ưu hóa Độ ổn định AI:
  * Luyện tập Test prompt với nhiều mẫu CV có định dạng khác nhau để xử lý triệt để hiện tượng bất đồng nhất giữa các trường thông tin hoặc AI trả về sai định dạng JSON
  * Tinh chỉnhPrompt tối ưu chi phí/độ trễ và xây dựng thành công cấu trúc dữ liệu dự phòng (Fallback Structure) giúp Backend không bị ngắt quãng khi AI xảy ra lỗi phản hồi





