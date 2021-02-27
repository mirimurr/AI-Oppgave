# AI-Oppgave


## About
An MVP/PoC Named Entity Reconizer with political parties in Norway added to the list of entities. the political parties are the ones mentioned in the talk-of-norway corpus found here: https://github.com/ltgoslo/talk-of-norway.
A random selection of a 1000 text where one of the political parties is mentioned under the tag party name.
Based on Spacys model for Norwegian bokmål
Code written in Python in Jupyter Notebook and is not to be used for other purposes then an PoC/MVP. 
The model trained on a local machine witout the use of GPU or similar.


To install the Norwegian language model run python -m spacy download nb_core_news_sm after installing reqiurements.

## Noteboks
* *Arkivverket_notebook_create_training_data.ipynb* creates training data based on the ton.csv files from the talk-of-norway corpus.
* *train_ner.ipynb* trains a new model for Named Entity Recognition based on the Norwegian language model provided by Spacy. The model is saved to xxx.
* *Test_custom_ner_model.ipynb* loads the model and displays the result.

