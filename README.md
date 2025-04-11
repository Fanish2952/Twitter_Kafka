# Twitter_Kafka


STEP BY STEP GUIDE TO RUN THE PROJECT: 
1. Paste the code of PRODUCER and CONSUMER into eclipse IDE. 
2. Open the PowerShell terminal in administrator mode.
   
3. Run zookeeper
 .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

4. Again open the  second PowerShell terminal in administrator mode and run server.
 .\bin\windows\kafka-server-start.bat .\config\server.properties

5. Again open the PowerShell terminal in administrator mode and create the topic
.\bin\windows\kafka-topics.bat --bootstrap-server 127.0.0.1:9092 --create --replication-factor 1 --partitions 1 --topic hashtags_topic

6.then press enter 
7. Now run the consumer code in eciplse and run producer code after consumer  
8. Output is ready.
