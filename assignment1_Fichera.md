Scope of the Journal
-
The Journal of Finance is the most read and most prestigious publication in the scholarly field of finance. In fact, it is rated as the most cited academic journal in the Business/Finance category. The journal accepts articles from all areas of study within finance. Many articles posted in the Journal of Finance have come to change how we think about finance and how we build better models to evaluate finance. I picked this journal for this assignment because it was an area of study I am very interested in as I will be graduating with a concentration in finance in May.


Questions to Answer
-
The purpose of this topic model is to answer questions about finance itself. Before the analysis, I sat down with the following questions I wanted to answer:
1. What words have been used most since the journals publication?
2. How have economic booms and recessions impacted the topics finance scholars write and research about?
3. Are there any past trends to support what will be written about in the future?
4. What is being written about right now?


Data Selected for Corpus
-
The data selected was the entire publication of the journal of finance, which began publication in 1946. I selected the entire publication because it was necessary to get as much historical data as possible to answer the questions I had set forth at the beginning of the assignment. There were over 9,000 articles analyzed, which is a good sample size for the scope of this assignment. It will also ensure that many niche topics within finance will be covered in the scope of this analysis.


Number of Topics
-
When it came to topic modeling this academic journal, it was appropriate to use 20 topics. The model was first created using 25 topics. However, I felt this number to be too high, as there were many topics with common words overlapping in multiple topics. With so many common words amongst many of the topics, I could not draw any conclusions through analysis.

After I had realized 25 topics was too specific a model, I cut the number of topics to 15, but again ran into problems. This time, the topic model became too broad. With only 15 topics, there were certain topics, such as banking, that did not have their own separate topic.

Finally, I settled on 20 topics. I found 20 topics to be appropriate for this journal because it gave the most diverse set of topics without any overlapping or common words. 20 topics allowed for specific topics such as Abnormal Firms and Markets to be included in this analysis, a topic not relatively discussed too often in finance.


Initial Findings and Arguments
-
The topic with the highest weight is the international finance topic, encompassing 11.9% of the corpus. It does not surprise me that these are the most discussed topics in finance. As technology continues to shock industries and globalization becomes more apparent with each passing day, international finance will become more and more important. Different currencies will become easier to obtain, as will foreign bonds and securities. The data suggests this trend will continue in the future. When the journal first started publication back in 1946, the world was still recovering from the aftermath of the Second World War. Back then, many national economies chose to exclude themselves from the global market. Today, the opposite is true, making international finance a top priority.

Following international finance is banking and undergraduate finance, both with 9.1%. Banking is the bloodline of finance, so like international finance, it does not surprise me to see it have such a heavy weighting in the journal of finance. As the data suggests, thanks to the same technology and globalization themes previously mentioned, banking has been an industry that has dominated finance for decades, and will continue to dominate finance for decades to come.

While I was neither surprised by international finance nor banking, I was extremely surprised to see undergraduate finance to be such a highly discussed topic in the corpus. Some of the notable unique words used in this topic include: university, school and research. This means a large chunk of scholarly finance research is dedicated to universities and other institutions I would have thought I would have found more articles in this topic to be found in the Journal of Financial Education, and not the Journal of Finance.

The final notable topic was risk, which made up 6.7% of the corpus. I expected this topic to have a higher weight than it did. Risk is one of the fundamental concepts of finance. Without risk, there is no financial reward. This topic included many variations of risk, including portfolio risk, exchange rate risk, regulatory risks, and more. This topic is a broader range of words than the market risk topic, which was more specific.

There was no topic that deeply studied individual consumers, but this is to be expected in a finance journal. That type of research would be more suited to an economics journal.


Possible Limitations
-
One limitation of the topic modeling completed was outlined in a paper by Ted Underwood, where he explains the susceptibility to confirmation bias when examining a large amount of documents. He writes, “If you’re working in a domain where you could potentially cite 100,000 different novels as evidence, confirmation bias will make all generalizations equally true until you invent some procedure to limit your own freedom of selection.” (Underwood, DHQ, 2017). Using a corpus consisting of the entire publication of the Journal of Finance and not a selected sample of articles, my topic analysis could become susceptible to the confirmation bias Underwood describes.

However, later in the paper, he provides a solution to this issue, by “minimiz[ing] misleading confirmations, for instance, by framing testable hypotheses about a sample of texts that are selected before the researcher settles on a conclusion.” (Underwood, DHQ, 2017). In my assignment, I set out with a set of questions that I wanted to answer in my analysis. But when I looked at the data, I too fell to some confirmation biases, and thus, did not draw as many insights or conclusions as I would have liked. I should have more clearly defined a hypothesis using the questions I set forth to make a more thoughtful analysis of the data.

With a topic like finance, the LDA algorithm could have some shortcomings. According to Goldstone and Underwood, a topic model is, “a model of how likely given words are to co-occur in a document.” (Goldstone and Underwood, JDH, 2012). There are some financial terms that are used interchangeably but in different capacities. For example, the term “market risk” can be used to describe both the overall economy and individual industries. This would lead to these phrases being classified in the same topic, despite being inherently different. This topic modeling analysis only included ngrams up to a factor of four, or four word phrases. Ideally, with terms like “market risk,” perhaps it would be more beneficial to analyze larger ngrams in the algorithm.

An area of improvement to this model is the Yearly Information topic. This topic picked up individual years as words. In finance, it is impossible to study any historical trends without naming years. Still, the model picks up words like 2002, 2003, 2004, etc. and groups them into a single topic. This caused articles of many different areas, from global economic crisis to networking, in the same topic. If I were to complete the assignment again, I would have added some code to not count specific years as words. Still, this topic overall only accounted for 2.2% of the corpus, so it does not throw off the analysis by a material amount.
