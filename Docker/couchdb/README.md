# CouchDB containerized

Document-oriented NoSQL database.

## deployments

From within the directory where the Dockerfile is, you can run the following commands:

```shell
sudo docker build --tag couchdb_image .
sudo docker run -d --name couchdb_container -e COUCHDB_USER=admin -e COUCHDB_PASSWORD=password -p 5984:5984 couchdb_image
sudo docker ps --all
sudo docker stop container_id
sudo docker start container_id
```
