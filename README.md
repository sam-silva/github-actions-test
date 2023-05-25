# Getting started 

## install
for installation run this on the root project 
```bash
docker run -it --rm -v ${PWD}:/app -w /app node:18.16-alpine sh
# then you can 
npm install 
# wait for the process and then 
exit
```
## start development
```bash
# first
cp ./env.example ./env
# then 
docker compose up 
# this process would start on the variable PORT set in .env 
```
