# NiFi
Follow the instructions from the documentation and .jpg for NiFi flows.

Repo includes following flows:
1.	NiFi and IBM MQ	
	Integrate NiFi with IBM MQ
	Put sampe text string in the message queue
	Extract the text from queue to a file and store it in local directory

2.	GetFile-PutFile	(This flow is to check nifi re-startability feature)
	Generate flow files in local directory ‘A’ using nifi’s GenerateFlowFile processor
	Transfer the files directory ‘A’ to ‘B’ and observe the re-startability feature

3.	Data Extract	
	Extract the data from database into NiFi flow file(NiFi Avro format)
	Convert NiFi flow file’s data into Json format
	Store the Json file into local directory

4.	Data Ingest	
	Read the content from Json file(Created using flow 3)
	Ingest it into the database

