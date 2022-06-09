# API Gateway

Nginx configurtation  

# Run

```
docker run --name api-gateway --restart always -v ${PWD}/conf.d:/etc/nginx/conf.d -p 8080:8080 -d nginx
```


