### Elastic Beanstalk
Back end API is deployed into EB node js
url: `Fullstack-env.eba-hjwuq2yx.us-east-1.elasticbeanstalk.com`

### RDS
For database we use postgers DB
Endpoint
`database-1.cw0ikyljghll.us-east-1.rds.amazonaws.com`
Port
`5432`

### S3
Front end app is deployed into S3 bucket
url: `http://full-stack-bucket.s3-website-us-east-1.amazonaws.com`

### CircleCi
CircleCi pipline, when developer pushes to the repo, CircleCi will trigger CI\CD based on config.yml