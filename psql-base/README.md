# PSQL-Base
This is the base image which includes all the data necessary to service a client
for geo-spatial queries on a PSQL database. This image runs Ubuntu and is serviced
on Dockerhub. To push to Dockerhub you must first build and then push.

```bash
docker build -t thre/psql-base -f Dockerfile .
docker push thre/psql-base
```
