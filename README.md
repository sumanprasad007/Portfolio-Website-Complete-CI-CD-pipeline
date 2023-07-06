# BTech_CTIS-_Complete-CI-CD-pipeline-using-AWS-for-an-Application_2019-B-15112001A

![image](https://user-images.githubusercontent.com/55047333/232679755-4521f08d-be8a-41cc-b8f0-eb48403483ce.png)

# Detailed Blog Link:
🔗 https://sumanprasad.hashnode.dev/end-to-end-cicd-pipeline-using-aws-cloud-for-my-portfolio-website

# ABSTRACT 

The rapid growth of cloud computing has revolutionized the way software is developed, deployed and managed. In this context, Continuous Integration (CI) and Continuous Deployment (CD) pipelines have become crucial for organizations looking to streamline their software delivery processes. This research paper presents a comprehensive study of implementing a complete CI/CD pipeline for an application using Amazon Web Services (AWS). The paper focuses on the different components of a CI/CD pipeline, including source code management, build and test, and deployment. The authors explore the various AWS services that can be used to automate these steps, such as GitHub, AWS CodeBuild, AWS CodeDeploy, and AWS CodePipeline. Furthermore, the paper highlights the benefits of using AWS to create a CI/CD pipeline, such as increased speed, reduced errors, and improved collaboration. The paper concludes with a case study demonstrating how a complete CI/CD pipeline can be created using AWS, providing insights and recommendations for organizations looking to adopt this approach[1].

INTRODUCTION

The concept of Continuous Integration (CI) and Continuous Deployment (CD) has become increasingly popular in the software development industry, as organizations strive to streamline their software delivery processes and reduce errors. CI/CD are practices that aim to automate the process of building, testing, and deploying software, enabling developers to deliver new features and bug fixes to production faster and with greater confidence. Implementing CI/CD pipelines has been made easier by the usage of cloud computing platforms like Amazon Web Services (AWS) [1,2,4].


AWS provides a range of services that can be used to automate the various stages of a CI/CD pipeline, from source code management to build and test, and finally deployment. This includes services such as GitHub, AWS CodeBuild, and AWS CodeDeploy, which can be combined to create a complete CI/CD pipeline. By utilising these services, businesses can speed up cooperation, decrease the likelihood of errors, and cut down on the time and effort needed to deploy software [2,4,5].


In this Report, we will examine the benefits of using AWS to create a complete CI/CD pipeline for an application, and explore the various AWS services that can be used to automate the different stages of the pipeline. We will provide insights and recommendations for organizations looking to adopt this approach, and present a case study demonstrating how a complete CI/CD pipeline can be created using AWS. In addition to the benefits outlined above, using AWS for a CI/CD pipeline also provides the added advantage of scalability. With AWS, organizations can easily scale their infrastructure to meet the demands of their software delivery process, without the need for significant upfront investments in hardware. This makes AWS an ideal choice for organizations of all sizes, from small startups to large enterprises [7,8,9]. 
 


# Features of Project: 

1.	Comprehensive Study: The Report provides a comprehensive analysis of the steps involved in implementing a complete CI/CD pipeline using AWS. The study covers all the key components of a CI/CD pipeline and explains how they can be automated using various AWS services. This allows organizations to understand the end-to-end process of creating a CI/CD pipeline, from code management to deployment.

2.	The Benefits of using AWS: The Report highlights the key benefits of using AWS to create a CI/CD pipeline. These benefits include increased speed, as automation reduces the time taken for manual processes, reduced errors, as automation eliminates human error, improved collaboration, as developers can work together on the same source code, scalability, as organizations can scale their infrastructure as required, and enhanced security, as AWS implements various security measures to ensure the safety of customer data.

3.	Case Study: The Report includes a case study that demonstrates how a complete CI/CD pipeline can be created using AWS. This provides organizations with a practical example of how the different components of a CI/CD pipeline can be automated using AWS services. The case study also provides recommendations for organizations looking to adopt a similar approach, allowing them to learn from the experience of others.

4.	AWS Services: The Report explores the various AWS services that can be used to automate the different stages of a CI/CD pipeline, such as GitHub for code management, AWS CodeBuild for building and testing code, and AWS CodeDeploy for deployment. The Report explains how each of these services can be used and how they integrate with each other to create a complete CI/CD pipeline.

5.	Recommendations: The Report ends with a list of suggestions for businesses wishing to use Amazon to construct a full CI/CD pipeline. These suggestions include advice on best practices, such as how to choose the proper Amazon services, how to assure security, and how to grow the infrastructure to meet the requirements of the software delivery process.

6.	Security: The Report also addresses the security aspect of using AWS for a CI/CD pipeline, highlighting the various measures implemented by AWS to ensure the safety of customer data. These measures include network security, data encryption, and access control.

7.	Scalability: While discussing the scalability of utilising Amazon for a CI/CD pipeline, the Report emphasises how simple it is for businesses to extend their infrastructure to match the needs of their software delivery process. With AWS services, businesses can scale their infrastructure up or down as needed without having to make substantial initial hardware expenditures.


## 1.1	EXISTING DEFENCE SYSTEMS AND SOLUTIONS
Before the adoption of CI/CD pipelines, software deployment was often a manual and time-consuming process that involved several stages. Here are some of the common steps involved in manual software deployment:

•	Code development: Developers write code on their local machines, and then commit it to a shared code repository. They may use a version control system like Git to manage changes to the codebase.

•	Build: Once the code is committed, it needs to be compiled and built into a deployable artifact. This involves running a series of commands to compile the code, resolve dependencies, and package it into a format suitable for deployment.

•	Testing: After the build process is complete, the application needs to be tested to ensure that it functions correctly. This may involve manual testing by a quality assurance (QA) team or automated testing using tools like Selenium or JUnit.

•	Deployment: Once the code is built and tested, it needs to be deployed to the production environment. This involves copying the artifacts to the server, configuring the server settings, and ensuring that the application is up and running.

•	Monitoring: After deployment, the application needs to be monitored to ensure that it continues to function correctly. This may involve setting up alerts and notifications to notify the operations team of any issues that arise.

Manual software deployment can be a time-consuming and error-prone process. With CI/CD pipelines, these stages can be automated, resulting in faster, more reliable software delivery. 

## 1.2	HOW A NEW SOLUTION CAN IMPROVE CERTAIN ISSUES
Implementing an AWS CI/CD pipeline can help to address several issues with traditional manual software deployment processes. By automating the build, test, and deployment stages of software development, CI/CD pipelines can help to reduce errors, increase collaboration, and speed up the delivery of new features and bug fixes to production.
However, even with a CI/CD pipeline in place, there may still be some challenges that need to be addressed. Here are some examples of how a new solution could improve certain issues with the AWS CI/CD pipeline:

•	Limited Integration with Existing Tools: One issue with using AWS for CI/CD is that it may not integrate well with existing tools and systems. For example, if an organization is using a different code repository than GitHub, it may be challenging to integrate that repository with AWS CodeBuild and CodeDeploy. A new solution could be developed to provide better integration between AWS services and existing tools. For example, a third-party integration tool could be developed that allows organizations to connect their preferred code repository with AWS CodeBuild and CodeDeploy.

•	Difficulty in Scaling Up: Another challenge with the AWS CI/CD pipeline is that it may be difficult to scale up quickly to meet the needs of a growing organization. As demand for software delivery increases, organizations may need to add more resources to their pipeline to keep up with demand. A new solution could be developed to make it easier to scale up the AWS CI/CD pipeline. For example, a tool could be developed that allows organizations to easily add more computing resources to their pipeline as needed, without having to manually configure and manage those resources.

•	Security Concerns: Security is always a concern when it comes to software development and deployment. While AWS provides a number of security features and best practices, there may still be vulnerabilities that need to be addressed. A new solution could be developed to provide additional layers of security for the AWS CI/CD pipeline. For example, a security tool could be developed that scans code for vulnerabilities before it is deployed to production, or a monitoring tool could be developed that alerts organizations to potential security breaches in real-time.

In summary, while the AWS CI/CD pipeline offers many benefits, there may still be issues that need to be addressed. A new solution could be developed to address these issues and provide additional benefits to organizations using the AWS CI/CD pipeline.  
CHAPTER 2

# METHODOLOGY
## 2.1	PROPOSED SYSTEM
The proposed solution to improve the above-mentioned issues is to implement a CI/CD pipeline using AWS services. The methodology involves the following steps:
 

Figure 2: High level architecture of proposed solution



The methodology involves the following steps:

1.	Planning: In this phase, the project team will define the requirements, objectives, and scope of the CI/CD pipeline. They will also identify the AWS services needed to implement the pipeline and create a plan for their integration.

2.	Design: In this phase, the team will create a design for the CI/CD pipeline, including the architecture, workflows, and integration of AWS services. They will also create a design for the infrastructure required to support the pipeline, such as servers and databases.

3.	Implementation: In this phase, the team will implement the CI/CD pipeline by setting up the AWS services and configuring them to work together. They will also create the necessary scripts and automation to ensure that the pipeline runs smoothly and efficiently.

4.	Testing: In this phase, the team will test the CI/CD pipeline to ensure that it is working as intended. This will involve testing the various stages of the pipeline, from code management to deployment, and verifying that the automation is functioning correctly.

Deployment: In this phase, the team will deploy the CI/CD pipeline to the production environment. They will also monitor the pipeline and make any necessary adjustments to ensure that it is running optimally.

## Proposed Solution:

The proposed solution involves implementing a CI/CD pipeline using AWS services. The following AWS services can be used to automate the different stages of the pipeline:

•	GitHub: A fully-managed source control service that makes it easy for teams to collaborate on code. GitHub eliminates the need for manual code management and enables teams to store and version their code in a secure and scalable manner.

•	AWS CodeBuild: A fully-managed build service that compiles source code, runs tests, and produces software packages that are ready to deploy. CodeBuild eliminates the need for manual build processes and provides a scalable, reliable, and secure way to build and test code.

•	AWS CodeDeploy: A fully-managed deployment service that automates software deployments to a variety of compute services, including Amazon EC2 instances, AWS Lambda functions, and on-premises servers. CodeDeploy eliminates the need for manual deployment processes and provides a reliable, repeatable, and automated way to deploy software.

•	AWS CloudFormation: A fully-managed service that enables teams to define and deploy infrastructure as code. CloudFormation eliminates the need for manual infrastructure management and enables teams to create, manage, and update infrastructure in a repeatable and automated way.

By using these AWS services, teams can create a complete CI/CD pipeline that automates the entire software delivery process, from code management to deployment. This will help teams to deliver software faster, with fewer errors, and with greater confidence. Additionally, the use of AWS services provides the added advantage of scalability, allowing teams to easily scale their infrastructure to meet the demands of their software delivery process.

## 2.2	HARDWARE REQUIREMENTS
    The hardware and software requirements to use a CI/CD pipeline on AWS will depend on the specific services being used and the size of the project. However, some general requirements can be outlined as follows:
Hardware requirements:

•	A computer or server with internet access
•	Adequate storage space to store code and build artifacts
•	Enough processing power and memory to run the necessary tools and services

## 2.3	SOFTWARE REQUIREMENTS
 To effectively implement a CI/CD pipeline using AWS, there are several software requirements that need to be in place:
1.	Operating System: The system should have an operating system that supports the tools and services being used. Commonly used operating systems include Windows, Linux, and macOS. The choice of operating system will depend on the specific requirements of the project.

2.	Code Editor or Integrated Development Environment (IDE): A code editor or integrated development environment (IDE) is required for writing and editing code. The choice of code editor or IDE will depend on the programming languages and frameworks being used for the project.

3.	Programming Languages and Frameworks: The necessary programming languages and frameworks required for the project must be installed on the system. The specific languages and frameworks required will depend on the requirements of the project.

4.	Version Control System: A version control system such as Git is required for code management. This is used to store code in a central repository and to manage changes made to the code by different developers.

5.	Continuous Integration Server: A continuous integration server such as Jenkins or AWS CodeBuild is required for building and testing code. These tools automate the process of building, testing, and reporting on code changes.

6.	Continuous Deployment Tool: A continuous deployment tool such as AWS CodeDeploy is required for deploying code to production environments. This tool automates the deployment process, making it faster and more reliable.

7.	AWS Account and Necessary Permissions: Access to an AWS account is necessary, and the user must have the necessary permissions to create and configure services. This includes permissions to create and manage AWS services such as AWS CodeBuild and AWS CodeDeploy.

It is important to note that specific software requirements will vary depending on the project and the services being used. Additionally, AWS provides many of the necessary services and tools, so there may be no need for additional software beyond what is provided by AWS.





## 2.4	ARCHITECTURE OF PROPOSED SOLUTION IN TESTING

CI/CD (Continuous Integration and Continuous Deployment) pipelines are software development practices that enable developers to build, test, and deploy code in a fast and efficient manner. The CI/CD pipeline automates the process of integrating modified code into the existing source code and deploying it to the production environment. The key components of a CI/CD pipeline include code version control, continuous build and testing, and continuous deployment.
CI/CD pipelines provide several benefits, such as reduced deployment time, improved collaboration between developers, reduced risk of errors, and increased software quality. However, implementing a CI/CD pipeline can also present several challenges, such as security, scalability, and integration with existing systems. The evolution of CI/CD pipelines has been rapid, and the practice has become an essential component of modern software development. In the past, software deployments were manual and time-consuming processes, but with the advancement of technology and the introduction of new tools and practices, the process of software deployment has become much more streamlined.
AWS (Amazon Web Services) provides a comprehensive platform for the implementation of CI/CD pipelines. The use of AWS for CI/CD pipelines provides several benefits, including increased speed, reduced errors, improved collaboration, scalability, and enhanced security. AWS provides a wide range of services that can be used to automate the different stages of a CI/CD pipeline, such as code version control, build and testing, and deployment. The use of these services provides increased speed, as the pipeline can be automated, reducing the time required for deployment. The use of AWS also reduces the risk of errors, as the pipeline can be configured to catch and correct any errors before deployment.

AWS also provides improved collaboration, as multiple developers can work on the same source code simultaneously. The platform is also highly scalable, making it suitable for organizations of all sizes. Finally, the use of AWS for CI/CD pipelines enhances security, as the platform provides secure data storage and protection against cyber-attacks [12,13].

Overview of AWS Services for CI/CD:
AWS provides several services that can be used to automate the different stages of a CI/CD pipeline. Some of the key services include [1, 12, 14]:
•	GitHub: This service provides a secure code repository for version control.
•	AWS CodeBuild: This service provides a fast and scalable environment for building and testing code.
•	AWS CodeDeploy: This service automates the deployment process, making it fast and efficient.
These services provide a comprehensive platform for the implementation of a CI/CD pipeline. They can be used in combination to automate the different stages of the pipeline, from code version control to deployment.
The proposed solution architecture consists of the following components:
•	Source code management - GitHub: The source code management is done using GitHub, which provides version control, issue tracking, and collaboration features for software development teams.
•	Continuous integration - AWS CodeBuild: The CI process is automated using AWS CodeBuild, which is a fully-managed build service that compiles source code, runs tests, and produces software packages that are ready for deployment.
•	Continuous deployment - AWS CodeDeploy: The CD process is automated using AWS CodeDeploy, which automates the deployment of software to EC2 instances or on-premises servers.
•	Infrastructure as code - AWS CloudFormation: The infrastructure is defined as code using AWS CloudFormation, which enables developers to create and manage AWS resources in a repeatable and automated way.
•	Monitoring and logging - Amazon CloudWatch: The system is monitored and logged using Amazon CloudWatch, which provides real-time monitoring of AWS resources and applications.
•	Security - AWS Identity and Access Management (IAM): The security of the system is managed using AWS IAM, which enables you to control access to AWS services and resources.
•	Notification - AWS SNS: Notification is sent to developers and other stakeholders using AWS SNS, which is a fully-managed messaging service that enables you to send messages to applications and other services.

The above architecture provides an end-to-end solution for the entire software delivery process, from code management to deployment, using AWS services. This solution provides automation and scalability, which helps organizations to speed up their software delivery process, reduce errors, and cut down on the time and effort needed to deploy software.


## 2.5	TESTING PROPOSED SOLUTION
Project Creation step by step:
Step 1: Creating Pre-requisites [3, 13]:
IAM Role Creations:
i.	 Role for CodeBuild: AWSCodePipelineServiceRole-us-east-1-website_pipeline [3,4]
Policy Names:
•	AmazonS3FullAccess
•	CloudWatchFullAccess
•	AWSCodeBuildAdminAccess

ii.	Role for CodeDeploy: devopsCodeDeployRole [5]
Policy Names:
•	AmazonS3FullAccess

iii.	 Role for EC2 Instance: CodeDeploy-Role-for-EC2 [7]
Policy Names:
•	AmazonEC2FullAccess
•	AmazonEC2RoleforAWSCodeDeploy
•	AmazonS3FullAccess
•	AWSCodeDeployFullAccess
•	AWSCodeDeployRole
•	AmazonEC2RoleforAWSCodeDeployLimitation

# Step 2: Now, it’s time to create An EC2 Instance & configure it:
 
Figure 3: An EC2 Instance Created Successfully
Step 3: Creating the Build Stage [4, 9]
a.	Source Stage Configuration:

 
Figure 4: Source Stage configuration by providing GitHub path 
b.	Build Stage Configuration: 

 
Figure 5: Build Stage Configuration using CodeBuild
c.	Deploy Stage Configuration:

 
Figure 6: Deploy Stage Configuration using CodeDeploy
d.	Created Pipeline with all the stages defined: [12, 13]
 
Figure 7: Code Pipeline created successfully - part 1
 
Figure 8: Code Pipeline created successfully - part 2

e.	Encountered Unknown error due to lack of CodeDeploy agent on EC2 Server: [5, 7]
This problem was caused by us failing to install the Code Deploy agent on our EC2 server:
Let us Install and Configure CodeDeploy Agent:
f.	Below are commands to install it:
 
Figure 9: Commands to fix the Build Phase Error
Step 6: Source Code Modification to Re-run the Pipeline: [8, 9, 12]
a.	Source Code After Modification: [12, 13]
 
Figure 10: Source Code After Modification
b.	Committed & pushed the changes to the repository:
 
Figure 11: Pushing Modified Code to GitHub repository

c.	Our website is live and running using Public Ip of our EC2 Instance: [7, 12]
 
Figure 12: Website is up and running – Home Page

 
Figure 13: Website is up and running – Services Page

d.	Server Monitoring: [10, 11]
 
Figure 14: Monitoring using EC2 Graphical Logs
CHAPTER 3

# RESULTS AND DISCUSSION

The proposed solution of implementing a CI/CD pipeline using AWS services has shown significant improvements in the software delivery process. The key benefits of using AWS for CI/CD include increased speed, reduced errors, improved collaboration, scalability, and enhanced security. The use of AWS services such as GitHub for code management, AWS CodeBuild for building and testing code, and AWS CodeDeploy for deployment has automated the process of software delivery, reducing the time and effort required for manual processes.

With the proposed solution, the development team can easily track changes in the code repository and collaborate on the same source code. This has resulted in faster development and delivery of new features and bug fixes to production, reducing the time to market. The automated testing using AWS CodeBuild has significantly reduced the occurrence of errors, as it eliminates human error in the testing process. This has led to increased confidence in the software delivery process and improved customer satisfaction.

The scalability of the proposed solution has been a significant advantage, as organizations can easily scale their infrastructure as required without having to make substantial initial hardware expenditures. This has allowed small startups to compete with large enterprises, providing a level playing field in the software development industry. The security measures implemented by AWS have ensured the safety of customer data, protecting it from unauthorized access and cyber-attacks. This has increased customer trust and confidence in the software delivery process. Overall, the proposed solution of implementing a CI/CD pipeline using AWS services has shown significant improvements in the software delivery process, reducing errors, increasing speed, and improving collaboration, scalability, and security.



# CHAPTER 4

# CONCLUSION & FUTURE SCOPE

4.1	CONCLUSION
In conclusion, implementing a complete CI/CD pipeline using AWS can provide significant benefits to organizations looking to streamline their software delivery processes. By automating the different stages of the pipeline using services such as GitHub, AWS CodeBuild, and AWS CodeDeploy, organizations can speed up cooperation, decrease the likelihood of errors, and cut down on the time and effort needed to deploy software.

The proposed solution for the implementation of the CI/CD pipeline using AWS is a comprehensive approach that includes several stages, from source code management to testing and deployment. The architecture of the proposed solution includes various AWS services, such as GitHub, CodeBuild, CodeDeploy, and CloudFormation, which are combined to create a complete CI/CD pipeline. The testing results show that the proposed solution can improve the speed and reliability of software delivery processes. By automating the different stages of the pipeline, the proposed solution reduces the time taken for manual processes, eliminates human error, and provides enhanced collaboration among developers. Additionally, the scalability of AWS allows organizations to easily scale their infrastructure to meet the demands of their software delivery process, without significant upfront investments in hardware.

Overall, the adoption of AWS for a CI/CD pipeline provides a range of benefits, including increased speed, reduced errors, improved collaboration, scalability, and enhanced security. Organizations of all sizes, from small startups to large enterprises, can benefit from the implementation of a complete CI/CD pipeline using AWS. However, it is important to carefully consider the hardware and software requirements, as well as the security measures that need to be implemented to ensure the safety of customer data.

## 4.2	FUTURE SCOPE

The proposed solution for implementing a CI/CD pipeline using AWS offers several opportunities for future development and expansion. Some of the potential future scopes are:

•	Integration with other cloud providers: Although the proposed solution utilizes AWS services, the architecture can be modified to integrate with other cloud providers such as Microsoft Azure or Google Cloud Platform. This would enable organizations to choose their preferred cloud provider and still enjoy the benefits of a comprehensive CI/CD pipeline.

•	Further automation: While the proposed solution automates the building, testing, and deployment process, there is still scope for further automation. For example, automated testing of new features and bug fixes can be implemented to enhance the quality of the software being deployed.

•	Optimization of resource utilization: The proposed solution utilizes AWS services to enable scaling of infrastructure as required. However, there is still potential for optimizing resource utilization to reduce costs further. For instance, auto-scaling based on application usage patterns can be implemented to optimize resource utilization.

•	Monitoring and reporting: The proposed solution provides a comprehensive CI/CD pipeline, but there is a need to monitor the performance of the pipeline and generate reports for better decision-making. Therefore, future development can include implementing monitoring tools such as Amazon CloudWatch and reporting tools such as AWS CloudTrail.

•	Security enhancements: Although AWS provides several security features, there is still a need to continuously monitor and enhance the security of the CI/CD pipeline. Future developments can focus on implementing advanced security features such as intrusion detection and prevention systems.

•	Integration with DevOps tools: The proposed solution utilizes AWS services such as GitHub, AWS CodeBuild, and AWS CodeDeploy. Future developments can integrate with other DevOps tools such as Jira, Slack, and Jenkins to create a more comprehensive DevOps platform.

•	Continuous improvement: Finally, future developments can focus on continuously improving the CI/CD pipeline by incorporating user feedback and implementing the latest best practices in software development and delivery. This would enable organizations to stay ahead of the competition and continually enhance their software delivery process.

•	Integration with Other Tools: There is scope for further integration of the CI/CD pipeline with other tools such as monitoring and logging tools. This will enable better visibility and tracking of the performance of the pipeline, and help in identifying and resolving issues quickly.

•	Enhanced Security Measures: While AWS already provides robust security measures, there is always room for improvement. Further enhancements to security measures can be made to ensure the safety of customer data, and to prevent unauthorized access.

•	Improved Performance: As technology continues to advance, there is always scope for further improvements in the performance of the CI/CD pipeline. Organizations can explore the use of newer technologies and tools to improve the speed and efficiency of the pipeline.

•	Increased Automation: While the proposed solution is highly automated, there is always scope for further automation. Organizations can explore the use of artificial intelligence and machine learning technologies to further automate the pipeline, and to improve the accuracy and efficiency of the pipeline.

•	Cloud-Native Solutions: Cloud-native solutions are becoming increasingly popular, and there is scope for organizations to explore the use of cloud-native solutions for their CI/CD pipeline. This will enable organizations to take full advantage of the benefits of cloud computing, such as scalability and flexibility.

# REFERENCES

1.	Overview of Deployment Options on AWS [Online] Available at: https://www.freecodecamp.org/news/what-is-ci-cd/
2.	AWS Official Documentation [Online] Available at: https://docs.aws.amazon.com/index.html
3.	Project Pre-requisites [Online] Available at: https://www.bluelabellabs.com/blog/part-i-setting-up-aws-codedeploy-codepipeline-to-automate-the-deployment-of-a-node-web-service/
4.	 AWS CodeBuild [Online] Available at: https://docs.aws.amazon.com/codepipeline/latest/userguide/action-reference-CodeBuild.html
5.	AWS CodeDeploy [Online] Available at: https://docs.aws.amazon.com/codepipeline/latest/userguide/action-reference-CodeDeploy.html
6.	AWS S3 [Online] Available at: https://docs.aws.amazon.com/codepipeline/latest/userguide/action-reference-S3.html
7.	AWS EC2 [Online] Available at: https://docs.aws.amazon.com/autoscaling/ec2/userguide/get-started-with-ec2-auto-scaling.html
8.	AWS Code Pipeline Project [Online] Available at:  https://awstip.com/simple-ci-cd-codepipeline-to-deploy-code-on-ec2-9bc9467fb58b
9.	CodePipeline Steps [Online] Available at: https://medium.com/@arliber/continuous-deployment-with-aws-codepipeline-codedeploy-and-github-on-ec2-36eeccfb7a5e
10.	AWS CloudWatch [Online] Available at: https://docs.aws.amazon.com/codepipeline/latest/userguide/incident-response.html
11.	CI/CD on AWS [Online] Available at: https://docs.aws.amazon.com/whitepapers/latest/cicd_for_5g_networks_on_aws/cicd-on-aws.html
12.	Method for Continuous Integration and Deployment Using a Pipeline Generator for Agile Software Projects [Online] Available at: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9231338/
13.	AWS CI/CD Pipeline Best Practices [Online] Available at: https://codefresh.io/learn/ci-cd/ci-cd-on-aws-the-   basics-and-4-best-practices/



