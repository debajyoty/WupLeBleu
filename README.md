# WupLeBleu


This is modified repository of LeBLEU, it uses wup similarity score to find similar word and assign edit distance 0 to that pair.
2 classes ModifiedLeBLEU and HindiModifiedLeBLEU has been implemented to incorporate these changes.

Dependencies:
py4j
nltk
nltk wordnet corpus
java 1.7+


Usage is similar to LeBLEU repo.--
LeBLEU - Quick start
===========================


Installation
------------

1) Create virtual environment

virtualenv --system-site-packages lebleu  
cd lebleu  
source bin/activate  

2) Clone repository

git clone https://github.com/Waino/LeBLEU.git lebleu  
cd lebleu  

3) Compile and install python-Levenshtein

git submodule init  
git submodule update  
cd python-Levenshtein  
python setup.py install  

4) Profit

lebleu itself is installed using setuptools library for Python.
To build and install the module and scripts to default paths, type

python setup.py install

For details, see http://docs.python.org/install/




We would be thankful for citing the folowing article on the use of this idea:

# Banik, Debajyoty, Asif Ekbal, and Pushpak Bhattacharyya. "Wuplebleu: The wordnet-based evaluation metric for machine translation." 15th International Conference on Natural Language Processing. 2018. 
