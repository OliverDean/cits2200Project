The WikiPageGraph.java is our teams implementaion of the interface and should be called by the test suite for marking.

We have also included our own testing suite.

In CITS2200ProjectTester.java, you will need to configure the following parameters:

pathToGraphFile: This string variable should be set to the path of the graph file that you want to use for your tests. If you're using the provided wikiTestData.txt file, you should set pathToGraphFile to its location. For example, if wikiTestData.txt is in the same directory as CITS2200ProjectTester.java, you would set pathToGraphFile to "./wikiTestData.txt".

testDataFlag: This integer variable determines the amount and nature of the test data that will be used for your tests. Incrementing testDataFlag will typically increase the size and complexity of the test data. You should adjust testDataFlag based on your specific testing requirements.

Ensure that the testDataFlag integer value corresponds exactly to the wikiTestData filename (e.g., if testDataFlag is set to 3, the pathToGraphFile should be set to ./wikiTestData3.txt) before running the test.