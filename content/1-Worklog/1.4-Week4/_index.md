---
title: "Week 4 Worklog"
date: 2026-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---


### Week 4 Objectives:

* Continue learning and practicing AWS Labs.
* Learn about routing and Internet connectivity in VPC.
* Practice configuring Security Groups.

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
      <td class="col-day">11/05</td>
      <td class="col-task">- Complete Module 02-Lab03-01.4 - NAT Gateway <br> - Learn the role of NAT Gateway in providing Internet connectivity for Private Subnet</td>
      <td class="col-date">05/11/2026</td>
      <td class="col-date">05/11/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">12/05</td>
      <td class="col-task">- Complete Module 02-Lab03-04.3 - Create NAT Gateway <br> - Create a NAT Gateway <br> - Verify Internet connectivity from Private Subnet</td>
      <td class="col-date">05/12/2026</td>
      <td class="col-date">05/12/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">13/05</td>
      <td class="col-task">- Complete Module 02-Lab03-01.2 - Route Table <br> - Learn the principles of routing in Amazon VPC</td>
      <td class="col-date">05/13/2026</td>
      <td class="col-date">05/13/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">14/05</td>
      <td class="col-task">- Complete Module 02-Lab03-03.4 - Create Route Table for Outbound Internet <br> - Create a Route Table <br> - Configure routes to Internet Gateway and NAT Gateway</td>
      <td class="col-date">05/14/2026</td>
      <td class="col-date">05/14/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">15/05</td>
      <td class="col-task">- Complete Module 02-Lab03-02.1 - Security Group <br> - Learn about access control mechanisms using Security Groups</td>
      <td class="col-date">05/15/2026</td>
      <td class="col-date">05/15/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">16/05</td>
      <td class="col-task">- Complete Module 02-Lab03-03.5 - Create Security Groups <br> - Create Security Groups for resources in the VPC <br> - Verify Inbound and Outbound rules</td>
      <td class="col-date">05/16/2026</td>
      <td class="col-date">05/16/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">17/05</td>
      <td class="col-task">- Review the completed Labs <br> - Summarize knowledge about NAT Gateway, Route Table, and Security Groups</td>
      <td class="col-date">05/17/2026</td>
      <td class="col-date">05/17/2026</td>
      <td class="col-ref">https://cloudjourney.awsstudygroup.com/</td>
    </tr>
  </tbody>
</table>


### Week 4 Achievements:

* Understood the mechanisms of Internet connectivity in Amazon VPC.
* Successfully created NAT Gateway and Route Table.
* Successfully configured Security Groups.
* Mastered routing mechanisms and access control in VPC.

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
      <td class="col-day">1</td>
      <td class="col-task">- Explore the application authorization problem when interacting with AWS resources <br> - Set up prerequisite infrastructure: create an EC2 Instance and an S3 Bucket for the lab</td>
      <td class="col-date">05/11/2026</td>
      <td class="col-date">05/11/2026</td>
      <td class="col-ref">https://000048.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">2</td>
      <td class="col-task">- Study Access Key authorization: create an IAM User and generate an Access Key / Secret Access Key pair</td>
      <td class="col-date">05/12/2026</td>
      <td class="col-date">05/12/2026</td>
      <td class="col-ref">https://000048.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">3</td>
      <td class="col-task">- Practice configuring and using Access Keys so that the EC2 application can connect to and interact with data in the S3 Bucket</td>
      <td class="col-date">05/13/2026</td>
      <td class="col-date">05/13/2026</td>
      <td class="col-ref">https://000048.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">4</td>
      <td class="col-task">- Deep-dive analysis of security risks when storing Access Keys in source code <br> - Understand why static Access Keys should not be used for real-world applications</td>
      <td class="col-date">05/14/2026</td>
      <td class="col-date">05/14/2026</td>
      <td class="col-ref">https://000048.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">5</td>
      <td class="col-task">- Research the safer alternative using IAM Roles <br> - Create a new IAM Role with the appropriate Policy to access S3 in place of Access Keys</td>
      <td class="col-date">05/15/2026</td>
      <td class="col-date">05/15/2026</td>
      <td class="col-ref">https://000048.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">6</td>
      <td class="col-task">- Attach the IAM Role to the EC2 Instance Profile <br> - Test access from EC2 to S3 without configuring any static key pair</td>
      <td class="col-date">05/16/2026</td>
      <td class="col-date">05/16/2026</td>
      <td class="col-ref">https://000048.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">7</td>
      <td class="col-task">- Evaluate the automatic rotation mechanism of Temporary Credentials provided by IAM Roles <br> - Clean up all created resources (EC2, S3, IAM) to optimize costs</td>
      <td class="col-date">05/17/2026</td>
      <td class="col-date">05/17/2026</td>
      <td class="col-ref">https://000048.awsstudygroup.com</td>
    </tr>
  </tbody>
</table>


### Week 4 Achievements:

* Clearly understood and differentiated the security levels between static Access Keys and dynamic IAM Roles.
* Proficient in creating, configuring, and attaching IAM Roles to EC2 for safe AWS resource access.
* Successfully applied cloud security standards, eliminating hardcoded credentials from application source code.
* Completed a proper resource cleanup process, protecting the Free Tier account from unexpected charges.
