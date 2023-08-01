## Brief

### Self Study Check In

**Q1: According to Agile manifesto -**

A: Individuals and interactions over people and technique

B: Individuals and interactions over projects and tools

C: Individuals and interactions over processes and tools.

D: Individuals and interactions over products and tools


**Q2: What are the 3 Questions usually be asked during daily huddle?**

**Q3: Explain the relation Agile Method with DevOps.**



### Lesson Overview

A compound of development (Dev) and operations (Ops), DevOps is the union of people, process, and technology to continually provide value to customers.

A DevOps approach is one of many techniques IT staff use to execute IT projects that meet business needs. DevOps can coexist with Agile software development; IT service management frameworks, such as ITIL; project management directives, such as Lean and Six Sigma; and other strategies.

Some IT professionals believe that the simple combination of Dev and Ops is not enough, and the term DevOps should explicitly include business (BizDevOps), security (DevSecOps) or other areas.



---

## Part 1 - Recap about Agile Methodology (2.8 Software Deployment Requirements)

### What is Agile Methodology?

![image](https://user-images.githubusercontent.com/106639884/212619082-ce5f2828-1b26-4bd0-89b0-3898cf2e8422.png)


Agile Methodology meaning a practice that promotes continuous iteration of development and testing throughout the software development lifecycle of the project. In the Agile model in software testing, both development and testing activities are concurrent, unlike the Waterfall model.


### How DevOps and agile work together?

Both DevOps and agile offer a structure and framework that can speed software delivery. You do not need to choose between DevOps or agile—instead, you can make use of both methodologies. Agile is strong on methods to organize work, such as through Scrum or Kanban, and DevOps drives a broader culture of getting software delivered faster and more reliably.

Instead of a decision of DevOps versus agile, the question—actually—is how to practice both. When considering how to build a development practice with the best of DevOps and agile, here are some examples of key benefits and features that can help you create a highly optimized development environment.

---

## Part 2 - DevOps


![image](https://user-images.githubusercontent.com/106639884/212624203-29d7d7e5-8273-4b52-8132-c3748af20f35.png)


A compound of development (Dev) and operations (Ops), DevOps is the union of people, process, and technology to continually provide value to customers.

What does DevOps mean for teams? DevOps enables formerly siloed roles—development, IT operations, quality engineering, and security—to coordinate and collaborate to produce better, more reliable products. By adopting a DevOps culture along with DevOps practices and tools, teams gain the ability to better respond to customer needs, increase confidence in the applications they build, and achieve business goals faster.


### How does DevOps work?

DevOps is a methodology that emphasizes collaboration and communication between development and operations teams throughout the entire product lifecycle. This approach aims to improve the speed and quality of software deployment by breaking down silos between development and operations teams, and by using tools to automate and accelerate processes.

Under a DevOps model, development and operations teams may merge into a single team, where engineers have a range of multidisciplinary skills and work across the entire application lifecycle, from development and testing to deployment and operations.

DevOps teams use a set of tools, commonly referred to as a toolchain, to automate and streamline processes. These tools help teams to implement key DevOps practices such as continuous integration, continuous delivery, automation, and collaboration.

The DevOps approach can also be applied to teams outside of development, such as security teams. This is known as DevSecOps, in which security becomes an integrated and active part of the development process.

### DevOps lifecycle

DevOps is characterized by its constant and cyclical nature, and practitioners often use the infinity loop symbol to illustrate this. The different stages of the DevOps lifecycle are depicted as interconnected and continuously flowing, this loop serves as a reminder of the need for ongoing collaboration and continuous improvement throughout the entire product lifecycle.

![image](https://user-images.githubusercontent.com/106639884/212791522-916e438d-07e0-4038-a326-b7054969f5e6.png)

The DevOps lifecycle, also known as the continuous delivery pipeline, is a set of automated and iterative processes that are executed within a larger development lifecycle, to optimize the rapid delivery of high-quality software. There may be variations in the number and names of workflows depending on the organization, but generally, these six stages are included:

1. Planning - This stage involves scoping out new features and functionality for the next release, based on feedback from end-users and other internal stakeholders.
2. Development - In this stage, developers test, code, and build new and enhanced features, based on user stories and work items from the backlog.
3. Integration - This stage involves integrating the new code into the existing codebase, testing, and packaging it into an executable for deployment.
4. Deployment - This stage is where the runtime build output is deployed to a runtime environment, usually a development environment, where runtime tests are executed for quality, compliance, and security.
5. Operations - This stage involves monitoring the performance, behavior, and availability of the deployed features, to ensure they provide value to end-users.
6. Learning - This stage involves gathering feedback from end-users and customers on features, functionality, performance, and business value, to take back to the planning stage for future enhancements and features.


In addition to the main stages of the CICD pipeline, there are three other important continuous workflows that occur in between these stages:

1. Continuous Testing: Traditional DevOps lifecycles include a separate testing stage that occurs between integration and deployment. However, in recent times, testing has been integrated throughout the entire pipeline, occurring during planning, development, integration, deployment, operations, and learning stages. This approach aims to identify and address risks and vulnerabilities early on, making it easier and less expensive to fix them.
2. Security: In the past, security was often an afterthought in waterfall methodologies and agile implementations, added only after delivery or deployment. DevOps, however, incorporates security from the planning stage, and continuously throughout the rest of the development cycle, this approach is known as "shifting left". This approach aims to address security issues early on, when they are easiest and least expensive to fix.
3. Compliance: Compliance with regulatory requirements is also best addressed early and throughout the development lifecycle. Industries that are regulated often need to provide a certain level of observability, traceability and access of how features are delivered and managed in the runtime operational environment. This requires planning, development, testing, and enforcement of policies throughout the CICD pipeline and in the runtime environment. Auditability of compliance measures is crucial for proving compliance to third-party auditors.

### CICD Pipeline, Workflow and Jobs.

CICD (Continuous Integration and Continuous Deployment) pipeline or workflow is a set of automated processes that are used to build, test, and deploy software. The pipeline is designed to ensure that code is tested and deployed quickly and efficiently, while minimizing the risk of errors and downtime.

A typical CICD workflow is composed of several stages, each with a specific purpose. The main stages of a CICD workflow are:

- Build: This stage is used to compile the code, create executable files, and package the application.
- Test: This stage is used to run automated tests to ensure that the application is working as expected. This may include unit tests, integration tests, and end-to-end tests.
- Deploy: This stage is used to deploy the application to a staging or production environment.
- Monitor: This stage is used to monitor the deployed application for errors and performance issues.

Each stage of the CICD workflow is typically composed of one or more jobs. A job is a specific task that needs to be executed in order to accomplish a certain stage. For example, the build stage may have jobs that compile the code, create executable files, and package the application.

The workflow of the pipeline describes the order in which these jobs are executed, and how they interact with each other. For example, the pipeline may be configured so that the build job is executed first, followed by the test job, and then the deploy job. The pipeline can also be designed to automatically trigger the next stage when the previous stage is completed successfully.

CICD workflow can be implemented in different ways, it could be a self-hosted solution like Jenkins, or a cloud-based one like AWS CodePipeline, Gitlab CI, CircleCI, etc. The choice of the workflow tool depends on the specific requirements of the organization.


---

## Part 3 - AWS DevOps

### AWS DevOps Tools

AWS (Amazon Web Services) provides a wide range of tools for implementing DevOps in the cloud, including:

- AWS Cloud Development Kit (CDK): an open-source framework for modeling and provisioning cloud resources using familiar programming languages.
- AWS CodeBuild: a service for building and testing code with continuous scaling.
- AWS CodeDeploy: a tool for automating software deployments to various services such as Amazon EC2, AWS Fargate, AWS Lambda, or on-premises servers.
- AWS CodePipeline: a tool for automating the continuous delivery of code for rapid and accurate updates.
- AWS CodeStar: a comprehensive DevOps tool for developing, building, and deploying applications on AWS, with an easy-to-use interface.
- AWS Device Farm: a tool for testing web and mobile apps across real mobile devices and desktop browsers hosted in the AWS cloud, allowing developers to improve the quality of their apps.

### AWS DevOps Best Practices

Here are some best practices for implementing DevOps on AWS:

- Use version control: Use a version control system such as Git to manage and track changes to your code. This makes it easier to collaborate with others and roll back changes if necessary.
- Automate your infrastructure: Use AWS CloudFormation or AWS Elastic Beanstalk to automate the provisioning and management of your infrastructure. This allows you to quickly and easily deploy new resources or roll back changes.
- Use CodePipeline and CodeBuild: Use AWS CodePipeline and CodeBuild to automate the process of building, testing, and deploying your code. This allows you to quickly and easily deploy new features and updates to your customers.
- Monitor your resources: Use AWS CloudWatch to monitor the performance of your resources and to receive notifications when certain thresholds are breached.
- Enable security and compliance: Use AWS services such as IAM and Config to enable security and compliance for your resources.
- Use CloudTrail and CloudWatch: Use AWS CloudTrail to log all of your AWS account activity and use CloudWatch to monitor the logs.
- Use AWS CodeStar: Use AWS CodeStar to create a comprehensive and easy-to-use DevOps toolchain for your application.
- Implement disaster recovery: Use AWS services such as S3 and RDS to implement disaster recovery for your application.
- Use AWS Elastic Beanstalk for Deployment: Use AWS Elastic Beanstalk for easy deployment of your applications, it provides a platform for deploying web apps and services, handling capacity provisioning, load balancing, and automatic scaling.
- Continuously measure, monitor, and improve: Continuously measure the performance of your system, monitor its availability and scalability, and continuously improve it using the feedback collected by monitoring.


---

## Part 4 - Additional - DevSecOps

DevSecOps (Development, Security, and Operations) is a software development approach that integrates security practices into the entire software development lifecycle (SDLC) from design to deployment. It emphasizes collaboration and communication between development, security, and operations teams in order to ensure that security is an integral part of the software development process.

DevSecOps aims to integrate security into the CICD pipeline, by automating security testing, vulnerability scanning, and compliance checking, as well as security-related code reviews, so that security issues can be identified and addressed early in the development process. It also includes continuous monitoring and threat detection, to ensure that security issues are identified and resolved as quickly as possible.

DevSecOps also promotes a culture of collaboration, communication, and shared responsibility for security among development, security, and operations teams. This helps to ensure that security considerations are integrated into the development process, and that the resulting software is secure and compliant.

DevSecOps enables teams to deliver software faster and more frequently, while maintaining a high level of security and compliance. It also helps to identify and mitigate security risks early in the development process, reducing the chance of a security incident occurring in production.
