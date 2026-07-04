---
title: "Week 10 Worklog"
date: 2026-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Deploy AWS infrastructure for Workshop ZeroBug Agent.
* Complete configuration of Amazon EC2, Application Load Balancer, and Amazon SQS.
* Verify system functionality before integration.

### Tasks to be carried out this week:
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
      <th>Day</th>
      <th>Task</th>
      <th>Start Date</th>
      <th>Completion Date</th>
      <th>Reference Material</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="col-day">22/06</td>
      <td class="col-task">- Build two-tier VPC network architecture (Public/Private) <br> - Prepare EC2 Key Pair <br> - Build zerobug-agent-app-1.0.0.jar file and prepare cloud.env file</td>
      <td class="col-date">06/22/2026</td>
      <td class="col-date">06/22/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">23/06</td>
      <td class="col-task">- Create VPC with CIDR 10.0.0.0/16 <br> - Create Public Subnet and Private Subnet <br> - Configure Internet Gateway and NAT Gateway</td>
      <td class="col-date">06/23/2026</td>
      <td class="col-date">06/23/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">24/06</td>
      <td class="col-task">- Configure Route Tables <br> - Create Security Groups for ALB, EC2, and RDS <br> - Verify connectivity between VPC components</td>
      <td class="col-date">06/24/2026</td>
      <td class="col-date">06/24/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">25/06</td>
      <td class="col-task">- Launch Amazon EC2 Instance in Private Subnet <br> - Configure IAM Role for EC2 (Bedrock, S3, Secrets Manager) <br> - Deploy Spring Boot application to EC2</td>
      <td class="col-date">06/25/2026</td>
      <td class="col-date">06/25/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">26/06</td>
      <td class="col-task">- Configure systemd service <br> - Test application via /api/health endpoint <br> - Create Target Group (Port 8080) <br> - Create Application Load Balancer and configure HTTP Listener</td>
      <td class="col-date">06/26/2026</td>
      <td class="col-date">06/26/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">27/06</td>
      <td class="col-task">- Create Standard Queue zerobug-jobs <br> - Configure application to send messages to Amazon SQS</td>
      <td class="col-date">06/27/2026</td>
      <td class="col-date">06/27/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">28/06</td>
      <td class="col-task">- Verify messages in Amazon SQS <br> - Finalize assigned Workshop deployment portion</td>
      <td class="col-date">06/28/2026</td>
      <td class="col-date">06/28/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
  </tbody>
</table>


### Week 10 Achievements:

* Completed AWS infrastructure deployment including VPC, EC2, Application Load Balancer, and Amazon SQS.
* Successfully verified Spring Boot application workflow on AWS.
* Completed assigned Workshop ZeroBug Agent deployment portion on AWS.
* Ready for integration with team's shared system.
