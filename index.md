## Welcome to my Machine Learning Page
My first blog topic is about teaching machine how to read a table in a document.

### Table Understanding or TUML
Table Undestanding can be a complex machine learning problem.  Unlike Natural Language Processing (NLP) which crawls over unstructured text and extracts information out of a sentance, a paragraph, or even an article, Table Understanding is about extracting information arranged in a variety of structural representations, often arranged in **rows and columns**.


Useful Links:
https://cs.uwaterloo.ca/research/tr/1996/09/CS-96-09.pdf


- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

and ![image](https://github.com/jcbnose/JohnChanML.github.io/blob/master/img_terminologyOfTable.png)

### Let's define the problem:
**Basic**
- Table Structure Recongition (TSR): turn a table from a scanned document (or programetic document) into cell documents that no structural and content information are lost.
- Table Attribute Extraction (TAE): ability to retrieve table cell content 

**Advanced**
- TSR to include embedded content which is not text, e.g. embedded chart or picture in a table
- Recognize tables span across multiple pages of a document

**Very Advanced**
- Reason over table content:
  including table meta data, references from and to its document

**Typology**
- Simple Typoloy:
- The Wang's Typology:
- The Chan's Typoloy:
  Using feature vectors to represent table type - As shown in the diagram above, table features, such as Stub Head, Boxhead Separator...etc. are considered as Table features.  To order to represent and classify table type effective, given the variability of data representation in table, the Chan's Typology proposed to use a vector (with 1xN dimension, where N = number of features) to represent the table type.


```

More details to come...
