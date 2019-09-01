# docker-react

## Steps
 - Create ElasticBeanStalk application and give it a name **docker-react**
 - Make sure you are using aws region ap-south-1. If not then change region in .travis.yml
 - Create IAM user having full access of ElastcicBeanStalk and Make Env variable of access key and secret key

> Now with your every `git push` it will trigger a build in travis CI and with every green build in CI it will deploy on AWS ElasticBeanStalk
