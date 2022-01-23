
# hlpl_english_words
hlpl_english_words is a database for English words lists. The package contains:  

> **Adjective:**  List of all adjectives 
> **Adverb:**  List of all adverbs   
> **Singular Noun:**  List of all Singular Nouns
> **Plural Noun:**  List of all Plural Nouns
> **Article:**  List of all Articles
> **Verb**  List of all Verbs 


## Basic Usage: 

### Installation
This package can be installed from [PyPi](https://pypi.python.org/pypi/hlpl_english_words) by running:
```
pip install hlpl_english_words
```

### Command line: 

To get some info about the sofwtare, on console, execute the command line:
```
hlpl_english_words
```
To get the sofwtare version, on console, execute the command line:
```
hlpl_english_words version
```


### Basic usage: 

To return list of English words list, execute:
```
from hlpl_english_words import english_words
hlpl_list=english_words.get(case)
```
`case` could be any element in the following list:
```
case=['adjective','adverb','noun-singular','noun-plural','verb','article','connection']
```
> **Note:** If `case==connection`, the returned value is the connection to database file

### License
hlpl_english_words is licensed under the [MIT license](https://opensource.org/licenses/MIT).



<p style="font-size:19px;color:green;font-weight:bold;">Contributions are welcome! Please make a pull request.</p>

#### Development pattern for contributors

1. [Create a fork](https://help.github.com/articles/fork-a-repo/) of the [main hlpl_english_words repository](https://github.com/hlpl/english-words) on GitHub.
2. Make your changes in a branch named something different from `master`, e.g. create a new branch `my-pull-request`.
3. [Create a pull request](https://help.github.com/articles/creating-a-pull-request/).

