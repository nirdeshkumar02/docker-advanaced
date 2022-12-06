# This Project is basically used to deploy multi container full stack application through CI on AWS.

## Applicaiton - This is a basic application which used to calculate the fibonnaci series and save the data to postgres server. and redis used to show data quickly.
## Dev - There is Dockerfile.dev which is used to run development server. Use Docker-Compose.yml file to deploy the application for Development Environment.
## Prod - There is a workflow directory that have a yaml file which helps in creating image and pushing it to docker hub. All folders have its Dockerfile.prod dockerfile which helps in building images.

## Prod Workflow - 
![Prod-Workflow](https://github.com/nirdeshkumar02/docker-advanaced-app-multi-container/blob/master/prod.png)

