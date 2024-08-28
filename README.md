# NLP-research
Research using Sentiment Analysis (NLTK and BERT) to understand public opinions towards Open Streets program in New York

**About** 
This repository is used as part of an UCL Bartlett School of Planning Research project using mixed methods. The research angles from the perspective of urban planning practitioners and seeks to investigate how planners can harness social media data and sentiment analysis (SA) tools to enhance the planning process and encourage participatory planning by the general populace. The investigation uses the Open Streets program in New York City (NYC) as a case study to experiment and evaluate the best practices for planners to harness the potential of SA on social media data. 

**Result** 
Both VADER and BERT was able to achieve an accuracy of 70+%, but BERT's transformer architecture enables it to have much better potential at further increasing the accuracy of sentiment detection and analysis. Using BERT and  the SA of tweets about Open Streets in NYC between 2020 and 2022 showed no statistical changes annually.

**Application** 
The method can be, in theory, applied to any other public opinion analysis involving the use of social media data. The data cleaning part will need to be changed according to the specific dataset.

For further finetuning, the roBERTa model could be finetuned using tweets specifically targetted at expressing opinions towards urban planning initiatives. It was observed that a large part of the wrongly classified tweets are neutral comments discussing about the initiative, which existing roBERTa models may not be familiar with.

The Twitter (X) data obtained strictly follows Twitter's Developer Agreement and Policy.
