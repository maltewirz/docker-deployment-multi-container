```shell

#build image
docker build -t goals-node ./backend

docker tag goals-node maltewirz/goals-node

docker push maltewirz/goals-node

```