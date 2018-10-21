# ebs-custom-platforms
Custom platforms for AWS Elastic Beanstalk

# AWS-EBS-Amazon-Linux - nginx-php-fpm-google-pagespeed
Custom platform for AWS Elastic Beanstalk - nginx, php 7.1, php-fpm, google pagespeed plugin and php-fpm caching platform on Amazon Linux 
Visit https://hypersense-software.com/2018/03/12/aws-elastic-beanstalk-nginx-php/ for more information.

# AWS-EBS-Ubuntu-16.04 - apache-php
Custom platform for AWS Elastic Beanstalk - Ubuntu 16.04 with apache2 and php 7.0
Visit https://hypersense-software.com/2018/04/03/aws-beanstalk-ubuntu-16-04-php/ for more information.

# Changing the platform image
# login to elastic beanstalk platform, write down the current platform version
# in bash, cd to nginx-php-7.1-fpm directory an execute the command:
eb platform create --profile eb

# shutdown the created eb environment, ensure ec2 is shut down
# 