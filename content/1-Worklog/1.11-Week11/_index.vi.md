---
title: "Worklog Tuần 11"
date: 2026-07-22
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---


### Mục tiêu tuần 11:

* Kết nối tính năng voice với AI Interview bằng Polly và Transcribe.
* Chuẩn bị fallback nếu dịch vụ voice AWS lỗi khi demo.
* Đảm bảo transcript câu trả lời có thể đưa vào logic chấm điểm AI.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ 6 | - Phân tích workflow voice: text câu hỏi -> Polly audio -> ghi âm câu trả lời -> Transcribe text -> AI evaluation | 26/06/2026 | 26/06/2026 | |
| Thứ 7 | Ngày nghỉ | 27/06/2026 | 27/06/2026 | |
| Chủ nhật | Ngày nghỉ | 28/06/2026 | 28/06/2026 | |
| Thứ 2 | - Chuẩn bị kế hoạch tích hợp Polly để chuyển câu hỏi phỏng vấn thành audio | 29/06/2026 | 29/06/2026 | |
| Thứ 3 | - Chuẩn bị kế hoạch tích hợp Transcribe để chuyển audio câu trả lời thành text | 30/06/2026 | 30/06/2026 | |
| Thứ 4 | - Thiết kế fallback bằng browser speech khi dịch vụ voice AWS không khả dụng | 01/07/2026 | 01/07/2026 | |
| Thứ 5 | - Test luồng voice-to-evaluation và ghi lại các bước fallback khi demo | 02/07/2026 | 02/07/2026 | |


### Kết quả đạt được tuần 11:

* Sơ đồ hóa & Thiết kế Quy trình Voice End-to-End:
  * Sơ đồ hóa thành công luồng tương tác thoại hoàn chỉnh: Text câu hỏi -> Polly Audio -> Ghi âm phản hồi ứng viên -> Transcribe Text -> AI Evaluation
* Xây dựng Kế hoạch Tích hợp Dịch vụ Voice của AWS:
 * Lập lộ trình kỹ thuật tích hợp Amazon Polly để tự động chuyển đổi bộ câu hỏi phỏng vấn dạng văn bản thành file âm thanh phát cho ứng viên
 * Thiết kế cơ chế tích hợp Amazon Transcribe để nhận dữ liệu ghi âm câu trả lời và chuyển đổi thành văn bản phục vụ phân tích
* Xử lý Ngoại lệ & Chuẩn bị Kịch bản Demo
  * Xây dựng thành công cơ chế Fallback Strategy linh hoạt: Tự động chuyển sang sử dụng Web Speech API của trình duyệt khi dịch vụ AWS Voice gián đoạn hoặc bị nghẽn mạng
  * Kiểm thử thành công chuỗi luồng từ giọng nói đến chấm điểm, ghi chép kỹ lưỡng tài liệu hướng dẫn chuyển đổi trạng thái khi Demo để đảm bảo buổi trình diễn diễn ra trơn tru



