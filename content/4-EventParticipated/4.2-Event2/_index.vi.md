---
title: "Event 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---

# Bài thu hoạch – GenAI-powered App-DB Modernization Workshop

### I. Mục đích và ý nghĩa của việc tham gia sự kiện

Việc tham gia hội thảo **GenAI-powered App-DB Modernization** mang lại cho em cơ hội hiểu rõ hơn về cách các hệ thống phần mềm hiện đại được thiết kế và đổi mới. Ngoài nội dung kỹ thuật, sự kiện còn giúp em nhìn thấy cách doanh nghiệp tiếp cận chiến lược hiện đại hóa hệ thống, dữ liệu và vận hành trong bối cảnh công nghệ thay đổi nhanh.

### II. Danh sách các diễn giả

- **Jignesh Shah** – Director, Open Source Databases
- **Erica Liu** – Sr. GTM Specialist, AppMod
- **Fabrianne Effendi** – Assc. Specialist SA, Serverless Amazon Web Services

### III. Tổng hợp nội dung nổi bật từ các phiên chia sẻ

#### 1. Đưa ra các ảnh hưởng tiêu cực của kiến trúc ứng dụng cũ

- Thời gian phát hành sản phẩm kéo dài dẫn đến mất cơ hội và doanh thu
- Quy trình vận hành chưa hiệu quả khiến chi phí tăng và năng suất giảm
- Việc thiếu tuân thủ các tiêu chuẩn bảo mật có thể gây rủi ro về uy tín và an toàn

#### 2. Chuyển đổi sang kiến trúc ứng dụng mới – Microservice Architecture

Workshop cho thấy việc chuyển sang hệ thống modular không chỉ là tách chức năng ra thành nhiều phần mà còn cần xây dựng cách giao tiếp rõ ràng giữa các đơn vị. Mỗi chức năng có thể vận hành như một **dịch vụ độc lập**, trao đổi qua các **sự kiện** và dựa trên ba nền tảng cốt lõi:

- **Queue Management**: Quản lý các tác vụ chạy bất đồng bộ
- **Caching Strategy**: Tăng hiệu suất bằng cách giảm tải cho hệ thống
- **Message Handling**: Tạo kênh truyền thông tin linh hoạt giữa các service

#### 3. Domain-Driven Design (DDD)

- **Phương pháp 4 bước**: Xác định domain events, sắp xếp dòng thời gian, nhận diện actors và phân chia bounded contexts
- **Case study bookstore**: Minh họa cách áp dụng DDD trong tình huống thực tế
- **Context mapping**: Sử dụng 7 pattern để kết nối các bounded contexts một cách có tổ chức

#### 4. Event-Driven Architecture

- **3 pattern tích hợp**: Publish/Subscribe, Point-to-point và Streaming
- **Lợi ích**: Giảm phụ thuộc chặt chẽ, tăng khả năng mở rộng và độ bền của hệ thống
- **So sánh sync vs async**: Giúp hiểu rõ khi nào nên dùng cách tiếp cận nào

#### 5. Compute Evolution

- **Shared Responsibility Model**: Từ EC2 sang ECS, Fargate và Lambda
- **Serverless benefits**: Loại bỏ việc quản trị máy chủ, tự động mở rộng và chỉ trả tiền cho phần sử dụng thực tế
- **Functions vs Containers**: Cách lựa chọn công nghệ phù hợp với từng loại workload

#### 6. Amazon Q Developer

- **SDLC automation**: Hỗ trợ từ khâu lập kế hoạch đến bảo trì
- **Code transformation**: Hỗ trợ nâng cấp Java và hiện đại hóa .NET
- **AWS Transform agents**: Ứng dụng cho VMware, Mainframe và chuyển đổi .NET

### IV. Tổng hợp những kiến thức và kỹ năng ghi nhận được

#### Về mặt Tư duy Thiết kế

- **Business-first approach**: Luôn đặt nhu cầu nghiệp vụ lên trước công nghệ
- **Ubiquitous language**: Tầm quan trọng của một ngôn ngữ chung giữa business và tech
- **Bounded contexts**: Cách phân chia độ phức tạp trong các hệ thống lớn

#### Về mặt Kiến trúc Kỹ thuật

- **Event storming technique**: Một cách thực tế để mô hình hóa quy trình kinh doanh
- Sử dụng **Event-driven communication** thay cho các cuộc gọi đồng bộ truyền thống
- **Integration patterns**: Hiểu rõ thời điểm nên dùng sync, async, pub/sub hoặc streaming
- **Compute spectrum**: Lựa chọn giữa VM, container và serverless theo mục tiêu phát triển

#### Về mặt Chiến lược Hiện đại hóa

- **Phased approach**: Không nên thúc ép chuyển đổi mà cần có lộ trình rõ ràng
- **7Rs framework**: Có nhiều hướng hiện đại hóa phù hợp với từng ứng dụng
- **ROI measurement**: Đánh giá hiệu quả thông qua giảm chi phí và tăng tính linh hoạt của doanh nghiệp

### V. Định hướng ứng dụng vào học tập và công việc

- **Áp dụng DDD** cho các dự án hiện tại bằng các buổi event storming với đội business
- **Refactor microservices**: Sử dụng bounded contexts để xác định ranh giới dịch vụ hợp lý
- **Implement event-driven patterns**: Thay một phần giao tiếp đồng bộ bằng async messaging
- **Serverless adoption**: Thử nghiệm AWS Lambda cho các trường hợp phù hợp
- **Try Amazon Q Developer**: Tích hợp vào quy trình phát triển để tăng hiệu quả làm việc

### VI. Trải nghiệm thực tế tại sự kiện

#### Học hỏi từ các diễn giả có chuyên môn cao

- Các diễn giả đến từ AWS và các tổ chức công nghệ lớn đã đưa ra nhiều góc nhìn thực tế về cách xây dựng ứng dụng hiện đại.
- Qua các case study, tôi hiểu rõ hơn cách áp dụng **Domain-Driven Design (DDD)** và **Event-Driven Architecture** vào các dự án có quy mô lớn.

#### Trải nghiệm kỹ thuật thực tế

- Các buổi thảo luận về **event storming** giúp tôi hình dung cách biến quy trình nghiệp vụ thành các domain events có ý nghĩa.
- Tôi cũng hiểu rõ hơn cách chia nhỏ hệ thống thành **microservices** và dùng **bounded contexts** để kiểm soát độ phức tạp.
- Sự khác biệt giữa **synchronous và asynchronous communication** cùng các pattern như **pub/sub, point-to-point, streaming** trở nên rõ ràng hơn nhiều.

#### Ứng dụng công cụ hiện đại

- Tôi có cơ hội tìm hiểu sâu về **Amazon Q Developer**, một công cụ AI hỗ trợ nhiều giai đoạn của SDLC.
- Buổi chia sẻ cũng giúp tôi thấy được khả năng tự động hóa **code transformation** và vận hành serverless với **AWS Lambda**.

#### Kết nối và trao đổi

- Sự kiện tạo điều kiện để tôi trao đổi trực tiếp với chuyên gia, đồng nghiệp và các thành viên từ phía business.
- Những câu chuyện thực tế giúp tôi nhận ra rằng việc xây dựng hệ thống tốt không chỉ dựa vào công nghệ, mà còn cần sự hiểu nhau giữa các bên liên quan.

### VII. Bài học rút ra sau sự kiện

Bài học lớn nhất là hiện đại hóa hệ thống cần đi kèm với lộ trình chiến lược rõ ràng. Việc áp dụng DDD và các pattern hướng sự kiện giúp hệ thống linh hoạt hơn, giảm phụ thuộc và tăng khả năng thích ứng. Đồng thời, các công cụ AI như Amazon Q Developer có thể mang lại lợi ích rất lớn nếu được sử dụng đúng ngữ cảnh và đúng mục tiêu.

#### Một số hình ảnh khi tham gia sự kiện

![Ảnh sự kiện 2](/images/Event2.png)

