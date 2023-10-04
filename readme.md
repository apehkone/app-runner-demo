
# AWS App Runner demo 

This repository holds a simple demo project to show AWS App Runner capabilities in the AWS User Group meeting held in Oulu at 4.10.2023


## Local environment 


```bash
cd src
docker build -t aws-nginx-demo .
docker run -d -p 8080:80 aws-nginx-demo
```

Then open browser at http://localhost:8080