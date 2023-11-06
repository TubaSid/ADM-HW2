# ADM-HW2
Members of the group:

Raffaele Cannarsa, cannarsa.1923456@studenti.uniroma1.it, id 1923456;<br/><br/>
Sai Swaroop Chittoor, chittoor.1916247@studenti.uniroma1.it id 1916247;<br/><br/>
Selin Topaloglu, selintopaloglu96@gmail.com id 2113300;<br/><br/>
Tuba Sidiqqui, sidiqqui.2047057@studenti.uniroma1.it id 2047057.<br/><br/>

The script produced for this homework allowed us to answer the requests for an exploratory data analysis, some essential information, a historical view of the dataset, some questions about consistency, the influence of an author based on their fanbase, estimating probabilities and using charts, statistical tests and other analysis methods to check whether a hypothesis is correct.

### Data Collection and Analysis
We begin by processing the two .json files (lighter authors and lighter books). Then we proceed with a univariate analysis to get a better understanding of the types of data present as well as clean the unnecessary parts. 
Later we dig deeper into the structure embedded in the dataframe to answer the question proposed.
The first question after the Exploratory Data Analysis is related to the books dataset and provides specific tasks that we needed to accomplish to get a view on the best and worst books for the number of reviews and average score respectively.<br/><br/>
In RQ3 we were required to build up a function able to give back: the number of books published, the total number of pages written, the most prolific month and the longest book written in a specific year.
In addition to that, we asked ChatGPT to provide us with a function for this task and then compared it to ours.<br/><br/>
RQ4 was about the consistency of the dataset so we needed to study the occurrences to improve our knowledge regarding possible risks in analysing the data.<br/><br/>
In RQ5 and RQ6 we analyzed to identify influential authors based on fan count and the number of books they've published. We examined the presence of book series among these authors and analyzed the distribution of different publication formats. Additionally, we investigated reader responses, including gender-based comparisons, and traced the publication history of these authors to identify trends in their production rates.<br/><br/>
In RQ7 the study involves estimating probabilities.<br/><br/>
RQ8 required us to apply a linear regression to find out whether or not readers usually read the longest books the worst and this question made us implement some statistical tests to accept or reject some hypotheses.<br/><br/>
In Bonus part we compared the performance of an alternative library to Pandas for filtering. We also conducted text-mining to group books or authors into genres and assessed the correspondence between these two procedures. For this part, clustering method was employed for text-mining.<br/><br/>
