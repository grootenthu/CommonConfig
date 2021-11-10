# CommonConfig
Spring Cloud Server managed repository

# Installing Rabbit MQ Server on Ubuntu 16.04

sudo apt-get install -y rabbitmq-server

# Enabling Rabbit MQ Plugins to use Management Console

sudo rabbitmq-plugins enable rabbitmq_management

# Start Rabbit MQ Server

sudo service rabbitmq-server start

# Stopping Rabbit MQ Server

sudo service rabbitmq-server stop

# Checking status of Rabbit MQ Server

sudo service rabbitmq-server status

# The Rabbit MQ Admin Console can be accessed at

http://localhost:15672

# Installing MySQL Server on Ubuntu 16.04

sudo apt install mysql-server

# Set up MySQL Security

sudo mysql_secure_installation

# The System will Prompt you for MYSQL root password

Please enter 0 = LOW, 1 = MEDIUM and 2 = STRONG: 1 
Enter : 1

Remove anonymous users? (Press y|Y for Yes, any other key for No) : Y

Disallow root login remotely? (Press y|Y for Yes, any other key for No) : Y

Remove test database and access to it? (Press y|Y for Yes, any other key for No) : N

Reload privilege tables now? (Press y|Y for Yes, any other key for No) : Y

All done! 


# Check MYSQL server status

sudo service mysql status

# To Connect into MYSQL

sudo mysql -u root -p

Enter root password!!
<<<<<<< HEAD

# To stop the MYSQL service

sudo service mysql stop

# To start the MYSQL service

sudo service mysql start
