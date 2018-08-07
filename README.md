# NiFi
Follow the instructions from the documentation and .jpg for NiFi flows.

Repo includes following flows:

#	Flow	Description
1.	NiFi and IBM MQ	
	Integrate NiFi with IBM MQ
	Put some text in message queue
	Extract the text from queue from queue and put it in a file whose path is specified in NiFi processor

2.	GetFile-PutFile	
	This flow is to check nifi re-startability feature
	Generate flow files in local directory ‘A’ using nifi’s GenerateFlowFile processor
	Transfer the files from stored in local directory ‘A’ to ‘B’ and observe re-startability feature

3.	Data Extract	
	Extract the data from database into NiFi flow file(NiFi Avro format)
	Convert NiFi flow file’s data into Json format
	Store the Json file into local directory

4.	Data Ingest	
	Read the content from Json file
	Ingest it into database

