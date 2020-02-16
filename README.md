# Description
Wordpress, Mysql, Phpmyadmin docker image

# Download latest wordpress
Follow the link https://wordpress.org/download/

# Extract the wp-content folder 
It contains themes and plugins and should be extracted in the path where docker-compose.yml file exists

# Docker compose-up
docker-compose up -d

# Docker compose-down
docker-compose down

# Docker compose-down (delete database)
docker-compose down --volumes 

# Launch Wordpress
Enter localhost in web browser

# Launch phpmyadmin
Enter localhost:8080 in web browser
