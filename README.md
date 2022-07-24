# react-docker-environment
- docker-compose up -d to start app
- docker exec -it react-docker-environment-react-fe-1 /bin/sh to enter the app container
- If you want to execute this app with typescript, commnet out working_dir: /usr/src/app/sample-app-typescript in docker-compose.yml