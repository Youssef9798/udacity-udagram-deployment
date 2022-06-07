## Udagram Infrastructure

Udagram is deployed on AWS "Amazon Web Service" using multiple services to deploy each part in the app, for the UI we are using S3 Services and for database we are using Postgres RDS and for the API we use the EB.

![Infrasturcture](udagram-infastructure.jpg)

### AWS

#### Postgres RDS

Udagram is using Postgres RDS as database service in AWS for stroing and fetching our app's data.

DATABASE: `postgres://postgres:Database_postgres@database-1.cpoccgzntzgw.us-east-1.rds.amazonaws.com:5432/postgres`

#### S3 Bucket

UI application is deployed using AWS S3 Bucket. UI is built by Angular.

BUCKET URL: `http://udagram-client.s3-website-us-east-1.amazonaws.com/`

#### EB - Elastic Beanstalk

The API server is deployed on AWS Elastic Beanstalk service.

EB URL: `http://udagram-api-dev.eba-2hip3nrs.us-east-1.elasticbeanstalk.com/`
