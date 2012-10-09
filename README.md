# Sentry Cloudformation Template

This is a Cloudformation template for [Sentry](https://github.com/getsentry/sentry). 

[![Launch Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=ap-northeast-1#cstack=sn~Sentry|turl~https://s3-ap-northeast-1.amazonaws.com/teamltbl/sentry-aws.template)

## Included

 * Latest sentry
 * Supervisord
 * Nginx
 * PostgreSQL

## Parameters
  * SentryUserName 
  * SentryPassword
  * SentryEmail
  * DBUsername
  * DBName
  * DBPassword
  * KeyName
  * InstanceType
  * `SENTRY_KEY` was rendom genearted.
  
## Configurations
 
   * /home/ubuntu/.sentry/sentry.conf.py 
   
