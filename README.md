# Testing Kafka Streams Using TestInputTopic and TestOutputTopic

Testing example related to  [KIP-470](https://cwiki.apache.org/confluence/display/KAFKA/KIP-470%3A+TopologyTestDriver+test+input+and+output+usability+improvements) 

See also  [Kafka Streams - Developer Guide](https://kafka.apache.org/documentation/streams/developer-guide/testing.html).

## kafka-streams-test-topics package

If you want to use these topic classes with older Kafka versions, there is a separate package which can be
used with older versions by modifying only the package import. See more info: https://github.com/jukkakarvanen/kafka-streams-test-topics 

## Testing Examples in Kafka Github:

* [WordCountDemoTest.java](https://github.com/apache/kafka/blob/trunk/streams/examples/src/test/java/org/apache/kafka/streams/examples/wordcount/WordCountDemoTest.java) 
* [TestTopicsTest.java](https://github.com/apache/kafka/blob/trunk/streams/test-utils/src/test/java/org/apache/kafka/streams/TestTopicsTest.java) 


## Author 

Jukka Karvanen / jukka@jukinimi.com

Questions and feedback welcome. 