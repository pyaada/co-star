# Co-Star

Predictiong the future always sounds fascinating. This model uses the co-starring data of actors to predict the likelihood of actors staring in the same movie in the future. This problem is based on the frequently studied link prediction between co-authors. 

# Tasks
* Parse the triplets from the triplets format used by the [DBpedia mappingbased-objects database](https://downloads.dbpedia.org/repo/dbpedia/mappings/mappingbased-objects/2020.08.01/mappingbased-objects_lang=en.ttl.bz2).
* Filter all the relationships/predicates with value 'http://dbpedia.org/ontology/starring'.
* This will give you a dataset of people who have co-starred in movies.
* Create an ML model for link prediction that can predict the probability of two people co-starring.

## Reference
[A Guide to Link Prediction - Analytics Vidya](https://www.analyticsvidhya.com/blog/2020/01/link-prediction-how-to-predict-your-future-connections-on-facebook/)

*If Github shows an error while loading the notebook please view it on nbviewer by Jupyter [here](https://nbviewer.jupyter.org/github/Erikishiru/co-star/blob/master/notebook.ipynb)*
