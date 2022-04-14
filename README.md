# Hosting a Full-Stack Application

In this project, we take a newly developed full stack application and deploy it to a cloud service provider so that it is available to customers. This application contains the main components of a 3-tier full stack application (UI, API, and Database).

In this project, we are using a starter application (Udagram).

## Project Environment

- Node v14.15.1 (LTS), or more recent.
- npm 6.14.8 (LTS), or more recent.
- AWS CLI v2.

## Docs folder overview

1. Screenshots of Udagram app in all steps.
2. Two diagrams for an overview of the infrastructure and the pipeline.
3. RunBooks (md format).

## Application URL

- Please visit `http://mahmoud758453.s3-website-us-east-1.amazonaws.com` for hosted Front-End Application.
- Please visit `http://udagram-env.eba-r4taa6qq.us-east-1.elasticbeanstalk.com` for hosted Back-End Application.

## Deployment Process

1. Run the project locally first to ensure it is working without errors.
2. Set up a production environment.
    - Configuring the database using RDS service.
    - Configuring The server using Elastic Beanstalk service.
    - Configuring S3 Service for Web Hosting.
3. Interact with the cloud Services via a CLI.
    - install AWS CLI and EB CLI.
    - Deploy the backend code to Elastic Beanstalk
    - Deploy the frontend code to AWS S3.
4. Configure a Pipeline
    - Create the configuration file `.circleci/config.yml`.
    - Connect the Pipeline to GitHub
    - In the root level package.json package.json write scripts for: Continuous Integration, and Continuous Delivery and Deployment.
