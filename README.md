# BitWeb-test-main
This is the repository that contains all other repositories and code for the BitWeb test

### Notice!  
**After you start up the containers, wait around 15 seconds (depends on the PC and  
 the resources you allocated to Docker) for the backend servers to fully start!**

### To start the project run the following command in terminal:
`docker-compose up` or use `docker-compose up -d` to run the command in detached mode

#### Check that the following ports are available:
- 8080 - `REST API`
- 5672 - `RabbitMQ`
- 15672 - `RabbitMQ-management`
- 8081 - `Websocket API`
- 5432 - `Postgres`
- 51234 - `Worker`
- 3000 - `Frontend`


