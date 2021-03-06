# Building a Language Model
Unigram, bigram and trigram language models are generated from a language dataset in order to create text of their own. Simple models are further compared with their Laplace and UNK token equivalents, to determine the difference in text generation between the three methods.
> Please refer to the project's report for further details

</br>
</br>

## Project Artefacts
### Source Code - Python Programming Language

#### _main.py_
Main script run by the user. The script is responsible for calling the 
necessary class functions to generate models, for displaying menus and accepting
user input.

#### _necessities.py_
Script used by the main script. The script is responsible for generating
the initial counts for the unigram, bigram and trigram models. It is also
reponsible for storing the enumerator classes defining each model and for
returning the number of unique words in the lexicon.

#### _vanilla.py_
Script used by the main script. The script is responsible for storing the classes
of each vanilla model. Each class is responsible for generating the model and for
performing text generation or probability calculation operations, when required.

#### _laplace.py_
Script used by the main script. The script is responsible for storing the classes
of each laplace model. Each class is responsible for generating the model and for
performing text generation or probability calculation operations, when required.

#### _unk.py_
Script used by the main script. The script is responsible for storing the classes
of each UNK model. Each class is responsible for generating the model and for
performing text generation or probability calculation operations, when required.
interpolation.py

#### _parser.py_
Script run by the user. This script isn't run by the main script and is only used
when a new lexicon needs to be generated from the folders in the corpus directory.
The script is also responsible for splitting the newly generated corpus into a training
set and a test set using an 80:20 split.


### Data Folders
#### _corpus_
This folder contains the 2 directories used storing the xml files used
to build the lexicon. Other folders containing xml files may be added to 
this directory should the user wish to train the models using more data.
 

#### _lexicon_
This folder contains the lexicon generated when running the parser.py script
and the training and test sets generated by splitting the lexicon.
