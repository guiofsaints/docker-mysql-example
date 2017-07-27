# Database users docker

Container for development with database users.

### Requirements
- [Docker](https://docs.docker.com/engine/installation/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Get started
Run command for create containers:

    $ docker-compose up
    
You can manage the database with PhpMyAdmin in [http://localhost:8090]().

- Server: mysql
- Database: users
- User: root
- Password: [t3st@2017.](.env)

 
    
### Structure

 - MySQL: version 5.7
 - PhpMyAdmin: version latest
 - File dump.sql: Create tables and insert data into users
 - File .env: MySQL environment variables