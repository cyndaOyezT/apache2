#pour construire l'image 
docker build -t my-site . 
#pour exécuter 
docker run -it -p 8080:80 my-site 
