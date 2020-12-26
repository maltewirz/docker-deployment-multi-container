```shell

#build images
#backend
docker build -t goals-node ./backend
docker tag goals-node maltewirz/goals-node
docker push maltewirz/goals-node

#frontend
docker build -f frontend/Dockerfile.prod -t maltewirz/goals-react ./frontend
docker push maltewirz/goals-react 
```