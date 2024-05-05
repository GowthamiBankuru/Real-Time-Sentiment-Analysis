# Twitter-sentimental-Analysis
1. Deploy Neo4J graph database and set up the tweets default graph database that comes with it. Can be found here.
2. Get acquainted with the underlying data model.
3. Query this database to extract the list of users and hashtags and Select users and hashtags to use in your demo and prepare a test dataset of tweets by a selected users. The tweets should contain some of selected hash tags and other users
4. Write the graph insertion, recommendation, and sentiment update queries in cipher and validate them before using them in the driver (Bolt if you are using Python).
5. Design your MangoDb schema for storing user profile and tweets
6. For sentiment analysis, use an NLP library that works well with the stream processing engine you select (either Kafka Streams or Spark streaming) to classify raw tweets SENG 691 Data Intensive application Project – Real time Sentiment Analysis 3 that are streamed using Kafka Message broker. If you opt for spark streaming engine use Structured streaming API.
7. The results of sentiment analysis are written into the SENTIMENT Kafka topic. A Neo4J Kafka connector need to be configured with Neo4J as a sink to update the appropriate nodeS. 
