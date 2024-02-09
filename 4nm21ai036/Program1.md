# Tokenization 

There are multiple ways of doing this

### Word Tokenization
- Extracting word by word 
- Exctrating keywords easily which will help the model

### Sentence Tokenization
- For a whole document if you apply tokenization

## Using pythons inbuilt function split() 
- By default it will split by empty space.
- pass it "." and it will split by full stop.

## Using RegEx
- [\w] matches all the characters except the whitespace
- [\w]+ matches the word until the whitespace.
- Dont know whats compile look into it.

## Using NLTK package
- Dont forget to download punkt file.
- String oriented library

## Spacy
- Object oriented library
- Language Class
- You need to download a matching version
- `!python3 -m spacy download en_core_web_sm`
- Text -> NLP Model(en_core_web_sm) -> Object (Document or Vocabulary)
- ![Alt text](NLP-Core.png)
