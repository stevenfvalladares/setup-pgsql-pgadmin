Setup instructions
==================

1.- Login postgres as superuser

`$ sudo su - postgres`

2.- Start the postgresql command line to create username and password

`$ psql`  
`$ create user username with password 'your_password';`

3.- Instruction to create a database

`create database my_database with owner username;`

4.- Assign super user privileges to the previously created user

`alter user username with superuser;`
