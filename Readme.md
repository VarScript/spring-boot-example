
1. Delete the word **template** from the files
```
  docker-compose.yml.template
  application.yml.template
```
2. Change the user and password from the above files
3. Execute the docker container
4. Open your therminal and execute the following commands
```
docker exec -it postgres bash
->  psql -U you_user_name
--> CREATE DATABASE customer;
--> \l **this is to list your databases** 
```

5. Run the application