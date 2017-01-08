# git-server
A git server configured by docker

#Instructions

 - Run the file run.sh
 - Access http://localhost in your browser
 - In the database configuration section, choose MySQL and change the host to gogs-db:3306. The username and password should be 'root' (you can change it docker-compose.yml file)
 - In the gogs configuration section, change the app url to http://localhost/
 - Configure your administration account
 - Click install gogs
 - Your git server is running
 
