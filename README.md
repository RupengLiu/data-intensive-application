# data-intensive-application

## Part one:

### Think about data systems
• Store data so that they, or another application, can find it again later (databases)  
• Remember the result of an expensive operation, to speed up reads (caches)  
• Allow users to search data by keyword or filter it in various ways (search indexes)  
• Send a message to another process, to be handled asynchronously (stream pro‐ cessing)  
• Periodically crunch a large amount of accumulated data (batch processing)  

1. For example, there are datastores that are also used as mes‐ sage queues (Redis), and there 
are message queues with database-like durability guar‐ antees (Apache Kafka).  

