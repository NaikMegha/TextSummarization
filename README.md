# TextSummarization

In general there are two types of summarization, abstractive and extractive summarization.
![image](https://user-images.githubusercontent.com/22762365/133407511-8e25ede0-ab22-436f-9060-1fbfcbb39ec6.png)


<p>1.Extractive summarization.<p/>
<p>Input document → sentences similarity → weight sentences → select sentences with higher rank.</p>
I will be using an unsupervised learning approach to find the sentences similarity and rank them. 
One benefit of this will be, you don’t need to train and build a model prior start using it for your project.

The TextSummarization.py file reads the news article and provides the appropriate results

<p>2Abstractive Summarization:</p> Abstractive methods select words based on semantic understanding, even those words did not appear in the source documents. It aims at producing important material in a new way. They interpret and examine the text using advanced natural language techniques in order to generate a new shorter text that conveys the most critical information from the original text.
<p>Input document → understand context → semantics → create own summary.</p>

