---
widget: blank
weight: 100
title: "Urban Dictionary Embeddings"

--- 

This resource contains a set of English-language word embeddings trained on the entirety of Urban Dictionary (urbandictionary.com) as of October 16, 2019. All terms, definitions, examples, and tags were treated as running text and embeddings were learned using the fasttext framework (fasttext.cc) with window size of 5, a negative sampling rate of 10, and a word-level dimensionality of 300. 

{{<spoiler text="Find out more" >}} These embeddings perform competitively on a range on word-level semantics tasks, and were also useful initializations for classifiers trained for sentiment and sarcasm detection. 
If you are working in a domain that uses a high degree of slang or nonstandard English and you want representations that better capture the slang meanings of terms, give them a try!

If you use this resource in your work, please cite:
Wilson, S. R., Magdy, W., McGillivray, B., Garimella, K., & Tyson, G. Urban Dictionary Embeddings for Slang NLP Applications. 
In Proceedings of the Language Resources and Evaluation Conference (LREC). Marseille, France, May 2020 {{</spoiler >}}

You can download the file from <a href=http://smash.inf.ed.ac.uk/ud-embeddings/files/ud_embeddings.zip>here</a>.
