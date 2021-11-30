# Redis containerized

In-memory key-value data structure store, ideal for distributed caching.

## deployments

From within the directory where the Dockerfile is, you can run the following commands:

```shell
sudo docker build --tag redis_image .
sudo docker run -d --name redis_container -p 6379:6379 redis_image
sudo docker ps --all
sudo docker stop container_id
sudo docker start container_id
```
