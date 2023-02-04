
# Conspiracy Detection and Correlation to Hate Speech

This project main purpose is to detect conspiracies in online "Parler" posts using a fine tunned model and examine the correlation between hate speech and conspiracies.






## Description
The main pipleline containes several steps:
* Fine tunning two NLP models (BERT and  GPT2) for conspiracy detection in Parler posts.
* Comparing the results of the two models.
* Fine tunning a hate detection model (HateBert) and detcting hate speech in Parler posts.
* Analyzing the relation between hate speech and conspiracies.

The focus was on four main conspiracy topics: Climate change, COVID-19 origin, COVID-
19 vaccine, and Epstein-Maxwell trial. 

Zero-shot learning was used to filter out relevant posts that contain these topics and text augmentation wasd used to increase conspiracy dataset size for training in both models.





 
## Data
See Data NLP in repository. 

Twitter conspiracy tagged data from [(Phillips et al.,2022)](https://github.com/samanthph/twitter-consp-theory-data) was used. 
Parler hate speech annotated data from[ (Israeli and Tsur,2022)](https://github.com/naslabbgu/parler-hate-speech) was used.

In addition, Parler posts were self-annotated for conspiracies by us.

## Authors

[Stav Marzuk](https://github.com/stavMarz), [Orit Rabani](https://github.com/oritRabani), [Mark Oulitin](https://github.com/MarkOulitin), [Dan Peled](https://github.com/DPeled)

