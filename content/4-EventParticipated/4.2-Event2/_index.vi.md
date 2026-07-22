---
title: "Event 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---


# Bài thu hoạch “Event 06-06-2026”

### Mục Đích Của Sự Kiện
- Chia sẻ những kiến thức của anh chị đi trước, sự kiện được tổ chức nhằm mang đến cho cộng đồng lập trình viên và sinh viên Công nghệ thông tin một góc nhìn toàn diện về quy trình phát triển, triển khai và bảo mật các ứng dụng hiện đại trên nền tảng điện toán đám mây

### Danh Sách Diễn Giả

- **Bảo Huỳnh** - Docker - A containerization technology
- **Lê Hoàng Gia Đại** -  Combining AWS WAF with Machine Learning for Cyber Attack Detection on AWS
- **Nguyễn Quốc Bảo** - Topic: Multiplayer in the Cloud: Connecting Godot Clients with AWS WebSockets
- **Trương Phước** - Topic: cách làm việc nhóm hiệu quả.
- **Việt Phát** - Topic: AWS Neptune for Building a Graph Knowledge Base for GraphRAG
- **Vinh Trần** - Topic: Từ IT Helpdesk lên Senior Sysadmin: Hành trình tự học và Lộ trình dịch chuyển sang Cloud/DevOps
### Nội Dung Nổi Bật
- Chuyển đổi Hạ tầng & Đóng gói Ứng dụng (Docker & DevOps):
Nắm vững cốt lõi công nghệ đóng gói Container với Docker — nền tảng không thể thiếu giúp chuẩn hóa môi trường phát triển, hỗ trợ các hệ thống dễ dàng mở rộng và chuyển dịch lên Cloud
- An ninh mạng thông minh với AI/ML (AWS WAF + Machine Learning):
Khám phá phương pháp bảo mật thế hệ mới: Kết hợp AWS WAF với các mô hình Machine Learning để tự động hóa việc nhận diện, phân tích và ngăn chặn các đợt tấn công mạng phức tạp theo thời gian thực
- Hệ thống Game Đa người chơi trên Cloud (Godot + AWS WebSockets):
Giải mã kiến trúc kết nối Real-time độ trễ thấp giữa các game client Godot với đám mây AWS thông qua WebSockets, giải quyết bài toán quy mô cho các tựa game Multiplayer
- Đón đầu xu hướng AI nâng cao (GraphRAG & AWS Neptune):
Cập nhật công nghệ Tri thức dạng Đồ thị (Graph Knowledge Base) trên AWS Neptune để tối ưu hóa mô hình GraphRAG — giải pháp giúp ứng dụng AI/LLM truy xuất dữ liệu thông minh, chính xác và ngữ cảnh hơn
- Lộ trình thăng tiến Sự nghiệp IT (Sysadmin -> Cloud/DevOps):
Lắng nghe chia sẻ thực tế về hành trình tự học và các cột mốc quan trọng để dịch chuyển sự nghiệp thành công từ vị trí IT Helpdesk lên Senior Sysadmin và tiến tới Cloud/DevOps Engineer
- Kỹ năng mềm cho Kỹ sư Công nghệ (Effective Teamwork):
Bí quyết phối hợp hiệu quả giữa các vai trò (Dev, Ops, Security, Data) trong một đội ngũ công nghệ, giúp tối ưu quy trình làm việc và đẩy nhanh tốc độ ra mắt sản phẩm

#### Event-Driven Architecture

- **3 patterns tích hợp**: Publish/Subscribe, Point-to-point, Streaming
- **Lợi ích**: Loose coupling, scalability, resilience
- **So sánh sync vs async**: Hiểu rõ trade-offs (sự đánh đổi)

#### Compute Evolution

- **Shared Responsibility Model**: Từ EC2 → ECS → Fargate → Lambda
- **Serverless benefits**: No server management, auto-scaling, pay-for-value
- **Functions vs Containers**: Criteria lựa chọn phù hợp

#### Amazon Q Developer

- **SDLC automation**: Từ planning đến maintenance
- **Code transformation**: Java upgrade, .NET modernization
- **AWS Transform agents**: VMware, Mainframe, .NET migration

### Những Gì Học Được

#### Tư Duy Thiết Kế

- **Business-first approach**: Luôn bắt đầu từ business domain, không phải technology
- **Ubiquitous language**: Importance của common vocabulary giữa business và tech teams
- **Bounded contexts**: Cách identify và manage complexity trong large systems

#### Kiến Trúc Kỹ Thuật

- **Event storming technique**: Phương pháp thực tế để mô hình hóa quy trình kinh doanh
- Sử dụng **Event-driven communication** thay vì synchronous calls
- **Integration patterns**: Hiểu khi nào dùng sync, async, pub/sub, streaming
- **Compute spectrum**: Criteria chọn từ VM → containers → serverless

#### Chiến Lược Hiện Đại Hóa

- **Phased approach**: Không rush, phải có roadmap rõ ràng
- **7Rs framework**: Nhiều con đường khác nhau tùy thuộc vào đặc điểm của mỗi ứng dụng
- **ROI measurement**: Cost reduction + business agility

### Ứng Dụng Vào Công Việc

- **Áp dụng DDD** cho project hiện tại: Event storming sessions với business team
- **Refactor microservices**: Sử dụng bounded contexts để identify service boundaries
- **Implement event-driven patterns**: Thay thế một số sync calls bằng async messaging
- **Serverless adoption**: Pilot AWS Lambda cho một số use cases phù hợp
- **Try Amazon Q Developer**: Integrate vào development workflow để boost productivity

### Trải nghiệm trong event

Tham gia workshop **“GenAI-powered App-DB Modernization”** là một trải nghiệm rất bổ ích, giúp tôi có cái nhìn toàn diện về cách hiện đại hóa ứng dụng và cơ sở dữ liệu bằng các phương pháp và công cụ hiện đại. Một số trải nghiệm nổi bật:

#### Học hỏi từ các diễn giả có chuyên môn cao
- Các diễn giả đến từ AWS và các tổ chức công nghệ lớn đã chia sẻ **best practices** trong thiết kế ứng dụng hiện đại.
- Qua các case study thực tế, tôi hiểu rõ hơn cách áp dụng **Domain-Driven Design (DDD)** và **Event-Driven Architecture** vào các project lớn.

#### Trải nghiệm kỹ thuật thực tế
- Tham gia các phiên trình bày về **event storming** giúp tôi hình dung cách **mô hình hóa quy trình kinh doanh** thành các domain events.
- Học cách **phân tách microservices** và xác định **bounded contexts** để quản lý sự phức tạp của hệ thống lớn.
- Hiểu rõ trade-offs giữa **synchronous và asynchronous communication** cũng như các pattern tích hợp như **pub/sub, point-to-point, streaming**.

#### Ứng dụng công cụ hiện đại
- Trực tiếp tìm hiểu về **Amazon Q Developer**, công cụ AI hỗ trợ SDLC từ lập kế hoạch đến maintenance.
- Học cách **tự động hóa code transformation** và pilot serverless với **AWS Lambda**, từ đó nâng cao năng suất phát triển.

#### Kết nối và trao đổi
- Workshop tạo cơ hội trao đổi trực tiếp với các chuyên gia, đồng nghiệp và team business, giúp **nâng cao ngôn ngữ chung (ubiquitous language)** giữa business và tech.
- Qua các ví dụ thực tế, tôi nhận ra tầm quan trọng của **business-first approach**, luôn bắt đầu từ nhu cầu kinh doanh thay vì chỉ tập trung vào công nghệ.

#### Bài học rút ra
- Việc áp dụng DDD và event-driven patterns giúp giảm **coupling**, tăng **scalability** và **resilience** cho hệ thống.
- Chiến lược hiện đại hóa cần **phased approach** và đo lường **ROI**, không nên vội vàng chuyển đổi toàn bộ hệ thống.
- Các công cụ AI như Amazon Q Developer có thể **boost productivity** nếu được tích hợp vào workflow phát triển hiện tại.

#### Một số hình ảnh khi tham gia sự kiện
* Thêm các hình ảnh của các bạn tại đây
> Tổng thể, sự kiện không chỉ cung cấp kiến thức kỹ thuật mà còn giúp tôi thay đổi cách tư duy về thiết kế ứng dụng, hiện đại hóa hệ thống và phối hợp hiệu quả hơn giữa các team.
