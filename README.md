<h1><a href="https://github.com/prsilvaa"> Cloud Computing </a></h1>

<h2>Project Objective</h2>
<p>To configure and test read/write access from an EC2 Linux instance to an S3 bucket by assigning proper IAM role permissions. This involves creating and configuring the S3 bucket, launching an EC2 instance, attaching IAM roles, and using AWS CLI commands to verify access. The solution ensures secure data exchange between EC2 and S3 services within the AWS environment.</p>

<h2>Tools Used</h2>
<ul>
    <li>AWS Academy Learner Lab – Foundation Services</li>
    <li>AWS IAM</li>
    <li>Amazon EC2</li>
    <li>Amazon S3</li>
    <li>AWS CLI</li>
    <li>Linux Commands</li>
</ul>

<h2>Skills Gained</h2>
<ul>
    <li>Configuring IAM roles and permissions</li>
    <li>Managing EC2 instances</li>
    <li>Creating and managing S3 buckets</li>
    <li>Using AWS CLI for S3 operations</li>
    <li>Linux terminal operations</li>
</ul>

<h2>Outcome</h2>
<p>Successful access to the S3 bucket from the EC2 Linux instance was achieved by verifying permissions using AWS CLI commands. The required text file was accessed and successfully copied from the S3 bucket to the EC2 instance using AWS CLI and Linux commands, confirming read and write permissions were correctly configured through the attached IAM role.</p>

<div align="center">
    <h3>EC2 Instance Setup</h3>
    <img src="ec2.png" alt="EC2 Instance" height="80%" width="80%">
    <p>EC2 Linux instance launched with Ubuntu 20.04 LTS, configured for secure access and AWS CLI installation.</p>
</div>

<div align="center">
    <h3>S3 Bucket Configuration</h3>
    <img src="s3.png" alt="S3 Bucket" height="80%" width="80%">
    <p>S3 bucket created with public access disabled. Text file uploaded to bucket for read/write access testing.</p>
</div>

<div align="center">
    <h3>IAM Role Permissions</h3>
    <img src="iam.png" alt="IAM Role" height="80%" width="80%">
    <p>IAM LabRole modified by attaching AmazonS3FullAccess policy to enable S3 bucket access from EC2 instance.</p>
</div>


