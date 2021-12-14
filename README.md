# Triplet-extraction-from-sentences-NLP-

Download Stanford Core NLP 
  https://nlp.stanford.edu/software/stanford-corenlp-latest.zip
  
Extract the zip file and cd into it

Run the CoreNLP server using java 

java -mx4g -cp "*" edu.stanford.nlp.pipeline.StanfordCoreNLPServer -annotators "tokenize,ssplit,pos,lemma,parse,sentiment" -port 9000 -timeout 30000
