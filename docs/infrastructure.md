# Udagram infrastructure

## AWS

### RDS
The application server uses AWS RDS Postgres as database for storing and retrieving information.

[Database URL](postgres://postgres:postgress@udagram.cjht7ox14edl.us-east-1.rds.amazonaws.com:5432/postgres)

### Elastic Beanstalk
The application server is deployed on AWS Elastic Beanstalk service.

[EB URL](http://udagram-env.eba-ggng2fxt.us-east-1.elasticbeanstalk.com/)

### S3 Bucket
The frontend application is deployed using AWS S3 Bucket.

[Bucket URL](http://myudagram.s3-website-us-east-1.amazonaws.com/)

Users can access the application from the Bucket URL.