# Exploring Joe Biden's Presidential Speeches: Uncovering Themes and Trends in Political Discourse
Political speech plays a vital role in comprehending political discourse, as it provides valuable insights into power dynamics and conflicts within a society. The language utilized by politicians, known as political discourse, serves as a potent tool for constructing a favorable and widely accepted self-representation or public perception (Neshkovska, 2019). By examining the main topics in presidential speeches and how presidents adapt their speeches and rhetoric to address these topics, researchers can gain insights into the shifts in public opinion, power dynamics, and conflicts within society.

In this project, we delve into the speeches of Joe Biden, the current President of the United States, to gain a deeper understanding of the prominent topics discussed and their evolution from 2021 to 2023. This allows us to capture the recent developments and changes in political discourse. 

Our goal is to collect and analyze 21 speeches delivered by Joe Biden to uncover the underlying themes and trends in his speeches. We will use two methods: Miller Center API and web scraping to collect the speech transcripts from the [Miller Center website](https://millercenter.org/the-presidency/presidential-speeches). We will employ computational techniques like the natural language processing and machine learning algorithms. Through topic modeling, we will uncover the latent themes within Biden's speeches, providing a comprehensive overview of the issues he has addressed. By analyzing the parts of speech and named entities, we will gain a deeper understanding of the linguistic patterns and the entities that Biden frequently references. By doing so, we aim to shed light on the key issues that have captured Biden's attention and how they have potentially shifted over time.

## Notebook
>Collecting_Data_GroupA.ipynb

This notebook is divided into three sections: introduction, tutorial, and active learning exercises.

In the introduction section, you will find background information about our project, including the research questions and motivation behind it. We also provide details about the data source we used and evaluate its credibility.

The tutorial section takes you through every step of the data collection and analysis process. It provides a comprehensive guide on how to collect and analyze data.

Lastly, the active learning exercise encourages users to apply what they have learned from the tutorial. We encourage you to create your own dataset, develop your own research questions, and analyze the data using the techniques taught in the tutorial.

## Data Management Plan
>Data_Management_Plan.pdf
## Folders & Files
Collecting data
>Biden_presidential_speeches1.csv: unprocessed data, collected by using Miller Center API.

>Biden_presidentia2_speeches1.csv: unprocessed data, collected by using web scraping.

Preprocess data
>Joe_Biden_speech_clean.csv: cleaned and standardized data.
>
>Joe_Biden_speech_lemmas.csv: lemmatized and cleaned data.

Topic modelling
>english.txt: English stopwords.
>
>TM_file.txt: file formatted for topic modelling. 

>topicmodel.bin: topic model.

Annotated file
>Joe_Biden_speech_topic_annotated.csv: data annotated with topics. 
>
>Joe_Biden_speech_spacy_annotated.csv: data anotated with POS and NER.
## Reference
>Miller Center of Public Affairs, University of Virginia. "Presidential Speeches: Downloadable Data." Accessed January 13, 2024. data.millercenter.org.

>Neshkovska, S. (2019). Language in political speeches. In International Scientific Conference “Towards a Better Future: Democracy, EU Integration and Criminal Justice” Conference Proceedings, Volume II (Vol. 2, pp. 115-124). Faculty of Law-Kicevo, University “St. Kliment Ohridski”-Bitola.
