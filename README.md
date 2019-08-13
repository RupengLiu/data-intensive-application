# data-intensive-application

### [Think about data systems](#think-about-data-systems)
### [Rest and Soap](#about-rest-and-soap)
### [Replication Summary](#replication)

## Part one:

### Think about data systems
• Store data so that they, or another application, can find it again later (databases)  
• Remember the result of an expensive operation, to speed up reads (caches)  
• Allow users to search data by keyword or filter it in various ways (search indexes)  
• Send a message to another process, to be handled asynchronously (stream pro‐ cessing)  
• Periodically crunch a large amount of accumulated data (batch processing)  

1. For example, there are datastores that are also used as mes‐ sage queues (Redis), and there 
are message queues with database-like durability guar‐ antees (Apache Kafka).  

### About Rest and Soap
![image](https://user-images.githubusercontent.com/29927264/62964287-889a7700-bdb7-11e9-92cd-eb1c7feeaa23.png)

### Replication
#### Why use replication?
![image](https://user-images.githubusercontent.com/29927264/62964779-8a186f00-bdb8-11e9-9d8e-5ab536e821a2.png)
#### Master-slave model
![image](https://user-images.githubusercontent.com/29927264/62965243-7588a680-bdb9-11e9-8cfd-6421232500f4.png)
![image](https://user-images.githubusercontent.com/29927264/62965306-93560b80-bdb9-11e9-983a-21cdf281f0d9.png)
#### Synchronous & Asynchronous
![image](https://user-images.githubusercontent.com/29927264/62965950-e11f4380-bdba-11e9-8043-f4dfede032f8.png)
![image](https://user-images.githubusercontent.com/29927264/62966099-2f344700-bdbb-11e9-8a8a-46ac2cf2f838.png)
#### Fail
![image](https://user-images.githubusercontent.com/29927264/62967003-01e89880-bdbd-11e9-981e-a5cbd4903356.png)
![image](https://user-images.githubusercontent.com/29927264/62967034-10cf4b00-bdbd-11e9-9900-0bb4f10637b5.png)
![image](https://user-images.githubusercontent.com/29927264/62973735-8b9f6280-bdcb-11e9-8aea-1701f2e825f5.png)


#### Replication logs









