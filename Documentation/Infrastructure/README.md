# Udagram App

- this app used Aws services to deploy frontend and backend apps.
- The database used in this app is postgresql with port 5432.

### To run this app

- visit frontend website to run app:

```
http://ahmed-udagram.s3-website-us-east-1.amazonaws.com
```

- to check api visit:

```
http://udagram-app-dev.eba-gkritgsz.us-east-1.elasticbeanstalk.com/
```

### Folders

The app contains `package.json` file, that combine neccessary scripts for installing, building, testing, and deployment, for backend and frontend app,

the app folder devided into two folders (`udagram-frontend` for the frontend and `udagram-api` for backend) each folder contains the complete project with `package.json` for specific independices and scripts for them.

a `.circleci` folder contains `config.yml` file, that is responsible for pipeline and ci/cd.

### Deployment to AWS

1. database used RDS postgres database.
2. deploying the api used elastic beanstalk service.
3. deploying the frontend used S3 bucket service.
