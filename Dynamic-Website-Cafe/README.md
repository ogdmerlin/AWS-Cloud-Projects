Challenge Lab: Creating a Dynamic Website for the Café
===================================================================

![Lab Description](Media/Lab_start.png)

```markdown
Lab Objectives
```

In this lab, you will deploy an application on an Amazon Elastic Compute Cloud (Amazon EC2) instance. The application gives the café the ability to accept online orders. After testing that the application works as intended in the first AWS Region (the development environment), you will then create an Amazon Machine Image (AMI) from the EC2 instance. You will also deploy a second instance of the same application as the production environment in another AWS Region.

After completing this lab, you should be able to do the following:

- Connect to the AWS Cloud9 integrated development environment (IDE) on an existing EC2 instance.

- Analyze the EC2 instance environment and confirm web server accessibility.

- Install a web application on an EC2 instance that also uses AWS Secrets Manager.

- Test the web application.

- Create an AMI.

- Deploy a second copy of the web application to another AWS Region.

*At the end of this lab, your architecture should look like the following example*:

![Lab Architecture](Media/Lab_Architecture.png)

```markdown
A business request for the café: Preparing an EC2 instance to host a website (challenge #1)
```

The café wants to introduce online ordering for customers and give café staff the ability to view submitted orders. Their current website architecture, where the website is hosted on Amazon S3, does not support the new business requirements.

In the first part of this lab, you take on the role of Sofía. You configure an EC2 instance so that it is ready to host a website for the café.
