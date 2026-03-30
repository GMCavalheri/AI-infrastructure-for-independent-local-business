# AI infrastructure for independent local business


This project aims to build a complete infrastructure for small/medium business, using automation tools such as n8n, Ollama AI models and docker. Providing all the necessary services locally, without extra costs and cloud support. 


## The Docker

The first step is download the application **[Docker Desktop](https://www.docker.com/products/docker-desktop/)** for the current OS. This application will run all the process from the infrastructure, that can be easily scaled and managed in multiple computers. 

![Docker img1](/imgs/docker_1.png)

After the download, we install the Docker Desktop and starts working in the n8n.


## The n8n

The first step is to go to the **[n8n Docker Documentation](https://docs.n8n.io/hosting/installation/docker/#prerequisites)**, following the section "Starting n8n" and making the configurations for the n8n container, such as finding your **[time zone](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones#List)**. We must create a volume named 'n8n_data' for persistent data and download (pull) a n8n image named 'n8nio/n8n', using the docker desktop. After this, we need to run the n8n image to config the optional settings. For my purposes the container will have the following config and than, its ready for use.


![Docker img2](/imgs/docker_2.png)


## The Ollama Models



## Libraries Used



## Conclusion

This Dashboard and the analyze made have insights of whose professionals are more indicate for each case, depending of the city.