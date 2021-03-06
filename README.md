# KE-from-Indian-Languages
This repository contains the documents and stopword lists for English language and three Indian languages - Bengali, Hindi, and Marathi.

The data can be used to extract keywords in the four langauges. Articles with id '2142' and '2148' are from Hulth2003 dataset, which are originally written in English. Both articles are translated to the three Indian languages using Google Translate. Articles on topics 'animation' and 'covid19' are Wikipedia articles written in the four languages.

Stopword list for English language is the SMART stopword list curated by Gerard Salton and Chris Buckley for the experimental SMART information retrieval system at Cornell University. Download link for the list is http://www.lextek.com/manuals/onix/stopwords2.html. Stopword lists for the three Indian languages are downloaded from Stopwords ISO (Link: https://github.com/stopwords-iso/stopwords-iso) and later updated to include more stopwords in the three Indian languages.

Implementations of keyword extraction algorithms that can be applied on these documents are included in the following repositories.
* LAKE: https://github.com/SDuari/sCAKE-and-LAKE 
* CnAKE: https://github.com/SDuari/Supervised-Keyword-Extraction.
