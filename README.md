# imprecisecommands.v1
Imprecise Commands (NLP classifier, CMPUT 495 Honours Seminar, 2017-2018)

## Setup Instructions
1. Create a virtualenv

    ~~~
    $ virtualenv venv
    ~~~

2. Activate the virtualenv

    ~~~
    source venv/bin/activate
    ~~~
    
3. Install the required packages
    
    ~~~
    $ pip install -r requirements.txt
    ~~~

4. Install NLTK corpus
    ~~~
    $ python
    >>> import nltk
    >>> nltk.download('punkt')
