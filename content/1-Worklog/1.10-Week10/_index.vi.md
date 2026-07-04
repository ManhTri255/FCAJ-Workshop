---
title: "Worklog Tuần 10"
date: 2026-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Triển khai hạ tầng AWS cho Workshop ZeroBug Agent.
* Hoàn thành cấu hình Amazon EC2, Application Load Balancer và Amazon SQS.
* Kiểm tra khả năng hoạt động của hệ thống trước khi tích hợp.

### Các công việc cần triển khai trong tuần này:
<table class="worklog-table">
<colgroup>
  <col class="col-day" style="width:5%">
  <col class="col-task" style="width:42%">
  <col class="col-start" style="width:13%">
  <col class="col-end" style="width:13%">
  <col class="col-ref" style="width:27%">
</colgroup>
  <thead>
    <tr>
      <th>Ngày</th>
      <th>Công việc</th>
      <th>Ngày bắt đầu</th>
      <th>Ngày hoàn thành</th>
      <th>Nguồn tài liệu</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="col-day">22/06</td>
      <td class="col-task">- Xây dựng kiến trúc mạng VPC hai lớp (Public/Private) <br> - Chuẩn bị Key Pair EC2 <br> - Build file zerobug-agent-app-1.0.0.jar và chuẩn bị file cloud.env</td>
      <td class="col-date">22/06/2026</td>
      <td class="col-date">22/06/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">23/06</td>
      <td class="col-task">- Tạo VPC với CIDR 10.0.0.0/16 <br> - Tạo Public Subnet và Private Subnet <br> - Cấu hình Internet Gateway và NAT Gateway</td>
      <td class="col-date">23/06/2026</td>
      <td class="col-date">23/06/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">24/06</td>
      <td class="col-task">- Cấu hình Route Tables <br> - Tạo Security Groups cho ALB, EC2 và RDS <br> - Kiểm tra kết nối giữa các thành phần trong VPC</td>
      <td class="col-date">24/06/2026</td>
      <td class="col-date">24/06/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">25/06</td>
      <td class="col-task">- Khởi tạo Amazon EC2 Instance trong Private Subnet <br> - Cấu hình IAM Role cho EC2 (Bedrock, S3, Secrets Manager) <br> - Deploy ứng dụng Spring Boot lên EC2</td>
      <td class="col-date">25/06/2026</td>
      <td class="col-date">25/06/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">26/06</td>
      <td class="col-task">- Cấu hình systemd service <br> - Kiểm tra ứng dụng thông qua endpoint /api/health <br> - Tạo Target Group (Port 8080) <br> - Tạo Application Load Balancer và cấu hình Listener HTTP</td>
      <td class="col-date">26/06/2026</td>
      <td class="col-date">26/06/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">27/06</td>
      <td class="col-task">- Tạo Standard Queue zerobug-jobs <br> - Cấu hình ứng dụng gửi message đến Amazon SQS</td>
      <td class="col-date">27/06/2026</td>
      <td class="col-date">27/06/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">28/06</td>
      <td class="col-task">- Kiểm tra message trong Amazon SQS <br> - Hoàn thiện phần triển khai Workshop được phân công</td>
      <td class="col-date">28/06/2026</td>
      <td class="col-date">28/06/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
  </tbody>
</table>


### Kết quả đạt được tuần 10:

* Hoàn thành triển khai hạ tầng AWS gồm VPC, EC2, Application Load Balancer và Amazon SQS.
* Kiểm tra thành công luồng hoạt động của ứng dụng Spring Boot trên AWS.
* Hoàn thành phần Workshop triển khai ZeroBug Agent trên AWS được phân công.
* Sẵn sàng tích hợp với hệ thống chung của nhóm.
