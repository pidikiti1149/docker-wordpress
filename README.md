Docker application to run wordpress 

> Two containers will be created named database and wordpress

> Database container pulls latest mysql image

> Wordpress container pulls latest wordpress image 

> Wordpress container will be linked to Databse container which is mounted with a volume 

> docker-compose up -d  # to run the containers 

> This will run wordpress container on port 8000

> docker-compose down  # to kill teh containers
