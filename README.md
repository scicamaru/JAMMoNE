# JAMMoNE
Master Degree Project for Laboratory of Advanced Programming

***************************
GUIDA GALATTICA PER DOCKER
***************************
COME SCARICARE IL CONTAINER:
il container si trova nel file jammone-app.tar
eseguire nel terminale DAL ROOT DEL PROGETTO:
docker load -i jammone-app.tar

runnare:
docker run -p 8080:8080 jammone-app
(oppure guarda i comandi dopo)
nessun codice sorgente o altro, voi e il vostro container 
//se cambiate qualcosa offro la vostra anima al diavolo - scicamaru 20250422

AVVIO DOCKER - si chiude da solo
docker run --rm -p 8080:8080 jammone-app

persistent container
docker run -d -p 8080:8080 --name jammone jammone-app

comandi
docker stop jammone

docker start jammone

docker rm jammone //se lo rimuovete vi vengo a cercare - scicamaru 20250422
