**Flutter Web Deployment to UAT and QA Environments**

**Overview**

This CI/CD pipeline automates the deployment of a Flutter web application to UAT and QA environments on AWS S3. It triggers on a push to tags that start with uat- or qa-.

**Triggering Deployment:**

To deploy to the UAT environment, push a tag that starts with uat- (e.g., uat-v1.0).
To deploy to the QA environment, push a tag that starts with qa- (e.g., qa-v1.0).
The workflow will automatically build and deploy the Flutter web application to the respective S3 bucket based on the tag prefix.
