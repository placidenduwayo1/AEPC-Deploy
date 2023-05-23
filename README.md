# montainerization microservices-base application

this git is containing a **docker-compose.yml** file for deploying in docker images utility services and business services:

* utility docker containers related to services:
	 * a database container : ***ms-apis-db***
	 * a configuration container: ***ms-config-api***
	 * a container of registration of microservices: ***ms-registration-api***
	 * a gateway container between backend and the frontend: ***back-front-gateway-api*** 
 
* containers related to business microservices (each business microservice is implemented in clean architecture pattern):

	* a container microservice of managing addresses: ***bs-ms-address-api***
	* a container microservice of managing employees: ***bs-ms-employee-api***
	* a container microservice of managing projects: ***bs-ms-project-api***
	* a container microservice of managing companies: ***bs-ms-company-api***

the backend(a spring boot microservices-base application) is located [here](https://github.com/placidenduwayo1/AEPC-Back)
the frontend (angular application) is located [here](https://github.com/placidenduwayo1/AEPC-Front.git)

## microservices configuration server
All services (utility services and business services) configiration files for config server are located here[here](https://github.com/placidenduwayo1/AEPC-Config-Service.git)

