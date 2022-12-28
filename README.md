- ## Here is the Architecture overview of our ETL flow

<img src="architecture.png" width="500px"/>

- ## Nifi Impletetion of this architecture


<img src="nifiFlow.png" width="500px"/>

## Deployment

* First you have to import the XML flow file into nifi. 
* Update the file location and name in GETFile node of nifi.
* Then you have to create Kafka topic "affectli" and "topic_druid" in your kafka broker.
* Run all nodes 
