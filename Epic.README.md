# Huly platform POC for epic 
## Running platform inside docker compose

The platform code is running on this vm: https://console.cloud.google.com/compute/instancesDetail/zones/us-central1-a/instances/huly-v2?project=task-manager-424822.  

## Running the docker code

```
cd /root/platform/dev;
sh build.sh; 

```

## NGIX containers 

Right now the client app uses different urls for different micro services.  Each one is proxy passed using nginx.  


The dns: 

```
https://account-tasks.getepic.com
https://rokoni-tasks.getepic.com
wss://transactor-tasks.getepic.com
wss://collaborator-tasks.getepic.com 
https://collaborator-tasks.getepic.com

```


```
 cat /etc/nginx/sites-enabled/nginx.conf
```


## Reddit conversation: 

https://www.reddit.com/r/selfhosted/comments/1ayz8ty/huly_allinone_project_management_platform/


## Site URL 

http://tasks.getepic.com/


## SSL ISSUE


https://docs.google.com/document/d/1DVvnd2BBBL97iof9zh0Y_JVQpQBGVFI1wbr3eTrvV7g/edit?usp=sharing

