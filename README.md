# **CI/CD Pipeline Project**

This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline for deploying a simple HTML-based web application. The pipeline leverages **AWS services** for automating the deployment process.

---

## **Project Overview**

The primary goal of this project is to showcase how a simple static website can be deployed seamlessly using a CI/CD pipeline. By integrating the pipeline with AWS services, every change in the code repository triggers an automated build, testing, and deployment process.

---

## **Features**

- **Static Website**: Simple HTML-based web application with images and basic functionality.
- **Automated CI/CD**: 
  - Continuous Integration: Ensures code changes are tested and packaged.
  - Continuous Deployment: Automatically deploys tested changes to a live environment.
- **AWS Integration**:
  - CodePipeline for orchestration.
  - S3 for hosting the static website.
  - CodeBuild for building and testing.
  - CodeDeploy for deployment to the S3 bucket.

---

## **Technologies Used**

- **Frontend**: HTML, CSS, and images.
- **CI/CD Tools**:
  - **AWS CodePipeline**: Orchestrates the CI/CD process.
  - **AWS CodeBuild**: Builds and packages the application.
  - **AWS CodeDeploy**: Deploys the application to the hosting environment.
- **Hosting**:
  - **AWS S3**: Used as the hosting service for the static website.

---

## **Project Workflow**

1. **Push Code**: Code changes are pushed to a version control system like GitHub.
2. **Pipeline Trigger**: AWS CodePipeline detects the changes and initiates the pipeline.
3. **Build**:
   - AWS CodeBuild compiles and prepares the HTML files for deployment.
   - Runs any predefined tests.
4. **Deploy**:
   - AWS CodeDeploy uploads the website files to an S3 bucket.
   - The website is hosted directly from S3 with public read access.
5. **Verify**: Ensure the changes are live by accessing the S3 static website URL.

---

## **Getting Started**

### **Prerequisites**
- AWS Account.
- S3 bucket configured for static website hosting.
- Permissions for AWS services (CodePipeline, CodeBuild, CodeDeploy, and S3).

### **Setup Instructions**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/cicd-project.git
   cd cicd-project
2. # **CI/CD Pipeline Project**

This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline for deploying a simple HTML-based web application. The pipeline leverages **AWS services** for automating the deployment process.

---

## **Project Overview**

The primary goal of this project is to showcase how a simple static website can be deployed seamlessly using a CI/CD pipeline. By integrating the pipeline with AWS services, every change in the code repository triggers an automated build, testing, and deployment process.

---

## **Features**

- **Static Website**: Simple HTML-based web application with images and basic functionality.
- **Automated CI/CD**: 
  - Continuous Integration: Ensures code changes are tested and packaged.
  - Continuous Deployment: Automatically deploys tested changes to a live environment.
- **AWS Integration**:
  - CodePipeline for orchestration.
  - S3 for hosting the static website.
  - CodeBuild for building and testing.
  - CodeDeploy for deployment to the S3 bucket.

---

## **Technologies Used**

- **Frontend**: HTML, CSS, and images.
- **CI/CD Tools**:
  - **AWS CodePipeline**: Orchestrates the CI/CD process.
  - **AWS CodeBuild**: Builds and packages the application.
  - **AWS CodeDeploy**: Deploys the application to the hosting environment.
- **Hosting**:
  - **AWS S3**: Used as the hosting service for the static website.

---

## **Project Workflow**

1. **Push Code**: Code changes are pushed to a version control system like GitHub.
2. **Pipeline Trigger**: AWS CodePipeline detects the changes and initiates the pipeline.
3. **Build**:
   - AWS CodeBuild compiles and prepares the HTML files for deployment.
   - Runs any predefined tests.
4. **Deploy**:
   - AWS CodeDeploy uploads the website files to an S3 bucket.
   - The website is hosted directly from S3 with public read access.
5. **Verify**: Ensure the changes are live by accessing the S3 static website URL.

---

## **Getting Started**

### **Prerequisites**
- AWS Account.
- S3 bucket configured for static website hosting.
- Permissions for AWS services (CodePipeline, CodeBuild, CodeDeploy, and S3).

### **Setup Instructions**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/cicd-project.git
   cd CI-CD
# **CI/CD Pipeline Project**

This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline for deploying a simple HTML-based web application. The pipeline leverages **AWS services** for automating the deployment process.

---

## **Project Overview**

The primary goal of this project is to showcase how a simple static website can be deployed seamlessly using a CI/CD pipeline. By integrating the pipeline with AWS services, every change in the code repository triggers an automated build, testing, and deployment process.

---

## **Features**

- **Static Website**: Simple HTML-based web application with images and basic functionality.
- **Automated CI/CD**: 
  - Continuous Integration: Ensures code changes are tested and packaged.
  - Continuous Deployment: Automatically deploys tested changes to a live environment.
- **AWS Integration**:
  - CodePipeline for orchestration.
  - S3 for hosting the static website.
  - CodeBuild for building and testing.
  - CodeDeploy for deployment to the S3 bucket.

---

## **Technologies Used**

- **Frontend**: HTML, CSS, and images.
- **CI/CD Tools**:
  - **AWS CodePipeline**: Orchestrates the CI/CD process.
  - **AWS CodeBuild**: Builds and packages the application.
  - **AWS CodeDeploy**: Deploys the application to the hosting environment.
- **Hosting**:
  - **AWS S3**: Used as the hosting service for the static website.

---

## **Project Workflow**

1. **Push Code**: Code changes are pushed to a version control system like GitHub.
2. **Pipeline Trigger**: AWS CodePipeline detects the changes and initiates the pipeline.
3. **Build**:
   - AWS CodeBuild compiles and prepares the HTML files for deployment.
   - Runs any predefined tests.
4. **Deploy**:
   - AWS CodeDeploy uploads the website files to an S3 bucket.
   - The website is hosted directly from S3 with public read access.
5. **Verify**: Ensure the changes are live by accessing the S3 static website URL.

---

## **Getting Started**

### **Prerequisites**
- AWS Account.
- S3 bucket configured for static website hosting.
- Permissions for AWS services (CodePipeline, CodeBuild, CodeDeploy, and S3).

### **Setup Instructions**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/cicd-project.git
   cd CI-CD
2. Set Up AWS S3:

Create an S3 bucket and enable static website hosting.
Configure the bucket policy to allow public access to objects.
Create the CI/CD Pipeline:

3. Set up an AWS CodePipeline.
Integrate the pipeline with:
Source: Connect to your GitHub repository.
Build: Configure AWS CodeBuild for any required build steps.
Deploy: Use AWS CodeDeploy to push the files to the S3 bucket.
Push Changes to GitHub:

Any updates to the HTML or assets will trigger the pipeline.
3. Verify Deployment:

Access the static website using the S3 bucket's public URL.
