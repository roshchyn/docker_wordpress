# docker_wordpress

# How to use it:
This is ready to use latest Wordpress, Apache, MySQL, PHP, Debian, PHPMyAdmin stack. 
!important: All changes made to files and database will not be erased if you destroy the docker container or volume. So your work is safe and will not be lost!
Deploy it using one single command: (run this command from the folder with docker-compose.yml file)

``` docker-compose up ```

# PRE requisites (before running the command):
- make sure you have docker installed on your environment (more info here : https://docs.docker.com/docker-for-mac/)
- edit docker-compose.yml section: environment to change credentials

# After installation
 - Wordpress is accessible on http://localhost:8000 and files are in ./src/ folder
 - PHPMyAdmin is accessible on http://localhost:8080
 - MySQL data is mounted in ./db_data/ folder
-  you can change ports by editing docker-compose.yml 'ports section' and re build the image by running: ``` docker-compose up --build```
 - to stop docker containers use this command from the same folder (this will stop and destroy running containers, but will NOT erase your database or files) :
 ``` docker-compose down ```

---------
PS. Brought to you by http://Roshchyn.com -> full stack web developer/architect

