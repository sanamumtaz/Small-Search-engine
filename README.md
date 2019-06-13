# Dhundoo A Small-Search-engine
DSA Project
This is a small search engine on Wikipedia Simple articles. Most search engines go in four stages: Crawling, Forward Indexing, Reverse Indexing, Searching.
### Dataset:
The forward indexing, reverse indexing and search are implemented on Wikipedia Simple corpus, so crawling is not required. Wikipedia Simple is a smaller version of Wikipedia designed for children which contains articles in simple english.
### XML Parsing
The dataset is in the form of an XML file. The XML parsing is done using SAX parser. It filters, is fast, and uses less memory.
### Forward Indexing and Page Rank
- Works page to page by counting the words
- Page Rank and its formula : (countBody*25)+(countTitle*975)
- Priority according to count
- Hashtables used
### Reverse Indexing
- Word count in the entire document
- Hashtables used
### Searching
- Single word searching: files made according to the word.
- Multi-word searching : Loop created because searching is done for more than one word. Page with intersection of all the words in the sentence is the best result.

![second](https://user-images.githubusercontent.com/35191030/59456122-1648fd00-8e2f-11e9-8358-780fab8edd42.gif)
