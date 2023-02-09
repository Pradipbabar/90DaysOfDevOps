## Day 29 Task: Jenkins Important interview Questions.

 <p align="center"><img align="center" src="https://user-images.githubusercontent.com/115981550/215283081-1c77ac18-4825-49d1-8727-7f0940846fff.png" /></p>
 

## Jenkins Interview
 Here are some Jenkins-specific questions related to Docker that one can use during a DevOps Engineer interview:
 
## Questions

### What’s the difference between continuous integration, continuous delivery, and continuous deployment?
 Continuous Integration (CI), Continuous Delivery (CD), and Continuous Deployment (CD) are three related software engineering practices that aim to make the software development process more efficient and streamlined.

Here's a brief explanation of each of these practices:

Continuous Integration (CI): CI is a software development practice where developers integrate their code changes into a shared repository several times a day. Each integration is verified by an automated build and test process to catch integration issues early and ensure that the overall codebase remains in a stable and usable state.

Continuous Delivery (CD): CD is a software development practice that extends the principles of CI by automating the entire process of software delivery. This includes not just the build and test process, but also deployment to pre-production environments, such as staging and QA, and the release process. The goal of CD is to be able to release software to production at any time with confidence, by ensuring that the code has been thoroughly tested and validated in a pre-production environment.

Continuous Deployment (CD): Continuous Deployment is an extension of Continuous Delivery, in which every code change is automatically deployed to production. In other words, every successful build is automatically pushed to production, without manual intervention. This requires a high level of automation and a rigorous focus on software quality and stability, as there is no human review before deployment. 

### Benefits of CI/CD 
- Smaller Code Changes. ...
- Fault Isolations. ...
- Faster Mean Time To Resolution (MTTR) ...
- Faster Release Rate. ...
- Smaller Backlog. ...
- Customer Satisfaction. ...
- Increase Team Transparency and Accountability. ...
- Easy Maintenance and Updates

### What is meant by CI-CD?
  CI and CD stand for continuous integration and continuous delivery/continuous deployment.
### What is Jenkins Pipeline?
Jenkins Pipeline (or simply "Pipeline") is a suite of plugins which supports implementing and integrating continuous delivery pipelines into Jenkins. A continuous delivery pipeline is an automated expression of your process for getting software from version control right through to your users and customers.

### How do you configure the job in Jenkins?
[follow this link] (https://www.tutorialspoint.com/jenkins/jenkins_setup_build_jobs.htm)

### Where do you find errors in Jenkins?
In Jenkins, in the pipeline where failure occurred, in the pane, select the latest build, and click Console Output. On the Console Output page, check the logs to find the reason for the failure

### In Jenkins how can you find log files?
/var/log/jenkins/jenkins

### Jenkins workflow and write a script for this workflow?
[follow this documentation] (https://www.jenkins.io/doc/book/pipeline/)

### How to create continuous deployment in Jenkins?
[follow this documentation] (https://www.jenkins.io/doc/pipeline/tour/deployment/)

### How build job in Jenkins?
[follow this documentation] (https://www.jenkins.io/doc/pipeline/steps/pipeline-build-step/)

### Why we use pipeline in Jenkins? 
Jenkins pipeline allows us to define a complete list of events that happen in the code lifecycle. Starting from the build, to testing and deployment. We can use a set of plugins that help in the implementation of certain processes as a continuous delivery pipeline

### Is Only Jenkins enough for automation?
For small to medium-sized projects with simple build, test, and deployment processes, Jenkins might be sufficient. However, for large and complex projects, or for organizations that require more advanced features such as parallel builds, distributed builds, or more sophisticated deployment pipelines, there might be other tools that are better suited.

### How will you handle secrets?
The easiest way to store secrets is to store them in a field of the type Secret, and access that field in your other code via a getter that returns the same type. Jenkins will transparently handle the encryption and decryption for on-disk storage.

### Explain diff stages in CI-CD setup
Continuous Integration (CI) and Continuous Delivery (CD) involve several stages in the software development process that help ensure that code changes are integrated, tested, and deployed to production in a reliable and efficient manner. Here are some of the key stages in a typical CI-CD setup:

- Code Commit: The first stage of the CI-CD process is when developers commit their code changes to the code repository. This is typically done several times a day, and each code commit triggers the CI/CD process.

- Build: In this stage, the code is built and compiled, and any necessary dependencies are retrieved and installed. The build process also includes running automated tests to catch any issues early.

- Test: Automated tests are run to validate the functionality and quality of the code. This stage includes unit tests, integration tests, and functional tests, and the goal is to catch any issues as early as possible in the process.

- Package: In this stage, the code is packaged and prepared for deployment. This might involve creating a Docker image, creating an executable binary, or creating an installable package, depending on the specific needs of the project.

- Deployment to Pre-production Environments: In this stage, the code is deployed to a pre-production environment, such as a staging or QA environment, where it can be further tested and validated before being deployed to production.

- Release: In this stage, the code is released to production. This stage is typically automated in a CD setup, and it involves deploying the code to production servers and making it available to end-users.


### Name some of the plugins in Jenkin?
[follow this link] (https://plugins.jenkins.io/)


These questions will help you in your next DevOps Interview.
Write a Blog and share it on LinkedIn.

*Happy Learning :)*
