Give feedback on this submission
## Visualizing Email Content: Portraying Relationships from Conversational Histories
### 1) a two sentence summary (do *not* simply summarize the work in your write-up)
This paper describes the a way of visualizing email conversation between 2 individuals. It uses the words present in the content as part of the visualization and offers a big picture view and a detail view.

### 2) what you feel are the positives of the work, i.e. what is exceptional
I think the paper does a good job of presenting a basic framework for analyzing email content. It uses the timeline and the word parsing from the content. It uses a keyword based approach across a timeline which can help in identifying a relationship between 2 individuals across time.  The visualization uses a temporal method stacked with word frequency (TF-IDF) and word search feature which make the visualization highly interactive and useful for mining the email archive. It did a great job of showing the evolution of relationships of individuals across time. Using TF-IDF over word frequency is something which Themail does right compared to general methods and gives a better overview of salient words. 

### 3) what you think could use improvement
I think one of the easy improvement in word count based approaches is the use of word disambiguation techniques like stemming, coreference resolution which will give a more accurate count of the words. 

### 4) how you might continue the work or what you might pursue next
The paper inspires to use the social communication as means to visualize relationships. In this new age of social networks I think it would be interesting to study not just email data but email data clubbed with other social platforms and then try to get a unified view of relationships between individuals across the platform. I believe it can tell a lot about the current usage of email these days which maybe for official purposes while chat forums are more prominent platforms for closer social interaction. 

## MUSE: Reviving Memories Using Email Archives
### 1) a two sentence summary (do *not* simply summarize the work in your write-up)
MUSE is another platform for visualizing email conversations by identifying sentiment, named entities and image attachments. It also presents the user with a memory cues for having a more personal connect with their email data.  

### 2) what you feel are the positives of the work, i.e. what is exceptional
Using named entities for extracting useful information from email content is something good which the paper does as opposed to just looking at email as bag of words. It also tries to use a network approach to identify social groups in the archive and visualize data in the social groups which is very useful in identifying the themes of our group of contacts. One of the interesting things which MUSE takes into account is sentiment in email messages. Although it is a hard problem to identify the sentiment with accuracy but using it as a method for visualizing temporal email data is useful for looking at relationship structure over time.     
The memory cues presentation techniques will be useful for people trying to dig email for some old memories and social groups.

### 3) what you think could use improvement
One of the improvement can be to categorize email content also across various categories using a mix of social groups and word usage in the content.     Coreference resolution will greatly help in more accurate named entity statistics.

### 4) how you might continue the work or what you might pursue next
The paper can be improved with the use of coreference resolution and topic modelling to identify themes in the content. 

## Social translucence: an approach to designing systems that support social processes
### 1) a two sentence summary (do *not* simply summarize the work in your write-up)
The paper describes systems which enable participants and their activities on computing networks visible to each other. It also presents a knowledge community framework called Babble.         

### 2) what you feel are the positives of the work, i.e. what is exceptional
This paper focuses on   improving communication and collaboration between people on computing networks. It uses the concept of decision making by people based on those around us. The framework uses the conversation based knowledge communities as its basis. It also relies on using social proxies like presence of action or individuals in conversation for the actual content of the conversations. This is useful as it to some extent tries to deal with the privacy issues of analyzing digital communication systems. 
Their framework does a good job of abstracting the actual private conversation between people to dots on a visualization with a detail on demand feature. Identities of people are abstracted using dots on their visualization which helps the user in getting an overview without affecting the privacy of the participants.

### 3) what you think could use improvement
Their system to me looks very basic when it comes to knowledge communities. Many techniques like topic modelling and text summarization came after this paper which can be used in improving the concept of knowledge communities.        

### 4) how you might continue the work or what you might pursue next
I would also like to implement their babble system approach to 2 different communities. 1. IRC chat forums and 2. Stack overflow forum. And see how static forum and dynamic chat forums differ.          
