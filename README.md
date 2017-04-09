# Docker Registry on Elastic Beanstalk

## deploy

1. create deployment

```
zip some_zipname.zip -r * .[^.]* -i Dockerrun.aws.json .ebextensions/*
```

2. create environment on Elastic Beanstalk, and upload & deploy deployment
