# This Project is basically used to deploy multi container full stack application through CI on AWS.

## Applicaiton - This is a basic application which used to calculate the fibonnaci series and save the data to postgres server. and redis used to show data quickly.
## Dev - There is Dockerfile.dev which is used to run development server. Use Docker-Compose-dev.yml file to deploy the application for Development Environment by running these commands -
`docker-compose -f docker-compose-dev.yml up`
`docker-compose -f docker-compose-dev.yml up --build`
`docker-compose -f docker-compose-dev.yml down`

## Dev Workflow - 
![Dev-Workflow](https://github.com/nirdeshkumar02/docker-advanaced-app-multi-container/blob/master/Dev.png)

## Prod - For Production Environment, We have a docker-compose.yml file which is used create a production ready environment by downloading the multi-container image from the docker hub. These docker images we are pushing to docker hub through github actions. We will deployed this multi container application to AWS Elastic Beanstalk.

## Prod Workflow - 
![Prod-Workflow](https://github.com/nirdeshkumar02/docker-advanaced-app-multi-container/blob/master/prod.png)

