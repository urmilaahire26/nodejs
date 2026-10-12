# Node.js Application Deployment Using Jenkins and PM2 on AWS EC2

## 📌 Project Overview

This project demonstrates the deployment of a Node.js web application on an AWS EC2 instance using Jenkins, webhook integration, and PM2 process management.

The application was hosted on a cloud-based Linux server and accessed through a web browser using the EC2 public IP address and port `3000`.

PM2 was installed to manage the Node.js application process. Jenkins and webhook integration were used as part of the deployment workflow.

The project provides practical experience in cloud deployment, application process management, and DevOps concepts.

## 🎯 Objectives

- Deploy a Node.js application on AWS EC2.
- Configure the Linux environment for application execution.
- Use Jenkins as part of the deployment workflow.
- Configure webhook integration.
- Manage the application process using PM2.
- Verify application availability through a web browser.

## 🛠️ Technologies Used

- **Node.js** – JavaScript runtime for the application.
- **AWS EC2** – Cloud-based virtual server.
- **Jenkins** – Automation and deployment workflow.
- **Webhook** – Event-based automation trigger.
- **PM2** – Process manager for Node.js applications.
- **Linux** – Server administration and command-line operations.
- **npm** – Node.js package management.

## ⚙️ Project Implementation

### 1. AWS EC2 Setup

Accessed an EC2 Linux instance and prepared the environment for running the Node.js application.

### 2. Node.js Application

The application was placed in a project directory containing the `app.js` file.

### 3. PM2 Installation

Installed PM2 globally using the following command:

```bash
sudo npm install -g pm2
```

PM2 was used to manage the application's execution as a background process.

### 4. Application Execution

Started the Node.js application using PM2:

```bash
sudo pm2 start app.js
```

The PM2 status output showed the application with an **online** status.

### 5. Jenkins and Webhook Integration

Used Jenkins and webhook integration as part of the application deployment workflow.

### 6. Deployment Verification

Opened the application in a web browser using the EC2 public IP address and port `3000`.

The deployed page displayed the message:

**"Hiii from jenkins, added webhook, we are from 18 May Devops batch"**

This verified that the Node.js application was accessible through the browser.

## 🚀 Key Features

- Node.js web application deployment.
- Cloud hosting using AWS EC2.
- Jenkins-based deployment workflow.
- Webhook integration.
- PM2 process management.
- Browser-based application verification.

## 📸 Project Screenshots

Add your screenshots to a folder named `screenshots` in your repository.

Suggested screenshots:

1. `nodejs-app-output.png` – Deployed Node.js application in the browser.
2. `pm2-status.png` – PM2 output showing the application status.

Display them in this section using:

```markdown
![Node.js Application Output](screenshots/nodejs-app-output.png)

![PM2 Application Status](screenshots/pm2-status.png)
```

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Deploying Node.js applications on AWS EC2.
- Running and managing applications on Linux.
- Installing Node.js packages using npm.
- Managing application processes using PM2.
- Understanding Jenkins and webhook integration.
- Learning the fundamentals of DevOps and cloud deployment.

## 🔮 Future Enhancements

- Build a complete CI/CD pipeline with automated testing.
- Configure PM2 startup to manage application restarts after server reboots.
- Configure HTTPS and a domain name.
- Add application logs and monitoring.
- Improve application error handling and security.

## ✅ Conclusion

This project demonstrated the deployment of a Node.js web application on AWS EC2 with Jenkins and webhook integration, along with PM2 for process management.

The application was successfully started using PM2 and verified through a web browser. This project strengthened my understanding of cloud infrastructure, application deployment, process management, and DevOps practices.

---

**Project Type:** Node.js Application Deployment  
**Runtime:** Node.js  
**Cloud Platform:** AWS EC2  
**Automation Tool:** Jenkins  
**Process Manager:** PM2  
**Integration:** Webhook
