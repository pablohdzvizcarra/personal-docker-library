# PostgreSQL Database

## Errors

- Directory Permissions: with Ubuntu I had an error when executing the docker-compose.yml file, the engine creates the `backups` folder without problems, the problem was after the creation the docker engine does not have the permissions to write files in the directory. The solution was give modify the directory permissions with `chmod` and the sudo user to allow all users to write, execute and read.
