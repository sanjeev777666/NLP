# NLP Project - Natural Language Processing with Disaster Tweets
## Group Members
Ce Zhou (zhouce@msu.edu), Hongzhi Wen (wenhongz@msu.edu),
Sanjeev Thenkarai Lakshmi Narasimhan (thenkara@msu.edu)

## Abstract
Twitter data is very useful for a variety of purposes when it comes to the latter use case, mainly because there are more than 6000 new tweets every second. With the advancement of technology and Natural Language Processing methodologies, the process of distinguishing a text based on semantic analysis has risen over the span of years. <br/> <br/> 
It has also proved to be an effective medium for gaining situational awareness and performing urgent needs assessment of the affected population during sudden onset disasters. <br/> <br/> 
Consider an instance wherein, an individual tweets about an emergency or an impending disaster that can be immediately recognized by our NLP models, that would enable us to quickly react to the scenario that would help save lives. It makes our topic meaningful and important. <br/> <br/> 
__The main aim of our project is to distinguish the authenticity of emergency tweets received over the platform about occurrence of real disaster.__

## Data Description
### Dataset Size
Our training dataset is composed of 7613 pieces of data, testing data is composed of 3263 pieces of data. 

### Features and Label
We have 3 ***features*** and 1 ***label*** for each piece of data. Features are ***keyword***, ***location*** and ***text*** (a sequence of tokens). ***Label*** is a binary value indicating whether the tweet text is about occurance of a real disaster or not.<br/> <br/> 
In the training dataset, we have 3271 true samples and 4342 false samples.

### Feature Statistics
***Location*** feature contains 3341 different locations of different granularities (the most frequent location is ‘USA’ with 104 counts, but there are also many city level location such as London) <br/> <br/> 
There are 221 different ***keywords*** in total, most frequent ***keyword*** is ‘fatalities’ with 45 counts. <br/> <br/> 
The maximum length of ***text*** is 53 tokens, minimum length is 1, average text length is 16.8 tokens. <br/> <br/> 
