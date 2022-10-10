Ce projet Postman contient 4 collections avec la structure suivante :

Globals : 

- agrosoil

IterationData: 

- pressure

Parameter:

* community : - agro1

* premium: - agro2

Standard:

- rootairpoll_ko

* request_ok : - forecast5d

* request_ko : - history404

* request_subfolder : * ok :
                      - moscow_forecast
 
                      * ko :
                      - history1

                      * suite :
                      - airpollution_ok
                      - airpollution2_ko


Les paramètres de test attendus sont les suivants :

DS_param : 800

DSNAME : Clear

TC_CUF_icon : 01n

CPG_CUF_humidity : 1000

IT_CUF_sealevel : 1031.04

TS_CUF_grndlevel : 1021.39

Les paramètres globaux attendus sont les suivants : 

dt : 1523188800

t10 : 274.51

moisture : 0.161
