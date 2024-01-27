# Gender and Whistleblowing Online
## Comparative Analysis of the Twitter Discourse around Peiter Zatko and Frances Haugen’s Revelations – A look into gender-based elements

This research project started in the context of Prof. Jen Schradie's course "Digital Inequality: Participation, Production and Pluralism in the Internet Era" offered in the Spring 2023 at Sciences Po Paris. It was then continued and refined for publication by the author. 

Publication [here](https://studi-internazionali.org/wp-content/uploads/2023/07/Numero-7-CSI-Review.pdf).

## The project in a nutshel

In late September 2021, whistle-blower Frances Haugen disclosed private documents from Meta showing that the company was aware of the harmful effects its services were having on society. She was invited for a congressional testimony on October 5th 2021.
In late August 2022, whistle-blower Peiter Zatko raised allegations against his former company Twitter, regarding the latter’s deficiency in handling users’ information and violation of US legislation. He was invited to testify before congress on September 13th 2022.

The research idea is to investigate the differences in the discourses developed around the two whistle-blowers – one male and one female – to detect the presence of targeted gender-based harassment and digital sexism. 

## Repositories
The *data* repository contains the dictionary used to detect sexual-harrassment (based on Rezvan et al. 2018), some elaborations of the Twitter data, and the training data for the sexism algorithm.

The *code* repository includes the code used during the project: (i) data analysis; (ii) sexism detection algorithm training (trained on the Samory 2021 dataset).

Here below you can find the links to the documentation of the main python libraries used in this exploratory analysis:
1. Minet (data gathering): https://github.com/medialab/minet
2. Twitterexplorer (Social Network Analysis): https://github.com/pournaki/twitter-explorer/blob/master/doc/DOCUMENTATION.md
3. SpaCy (Sentiment Analysis): https://spacy.io/universe/project/spacy-textblob
4. BERTopic (Topic Modelling): https://maartengr.github.io/BERTopic/index.html

