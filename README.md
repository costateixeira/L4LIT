# HAPI FHIR JPA Server Starter

This project extends the HAPI FHIR JPA Server Starter and adds additional FHIR operations.



## runing

To start the application, run the following command in your terminal:

```bash
docker-compose up 
```

This will start the application and make it available at `http://localhost:8080`.


## Docker

### Create an image  

Assuming that the organiztaion is "smart" and the name of the image is L4lit and we want to make it latest,
`docker build --tag smart/l4lit:latest --tag smart/l4lit:latest -m 4g .  `

### Upload image to hub
from a local command prompt:

`docker login ghcr.io` (and ado the necessary login)

`docker push smart/l4lit:latest` 

