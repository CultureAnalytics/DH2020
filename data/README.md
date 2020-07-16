This folder contains two data sets:

- A dance with dragons: relations between the characters of the novel *A dance with dragons* by G. R. R. Martin. 
- Steam games: games on the online platform *Steam*

## A dance with dragons

The data come from Harvard's culture analytics repository:
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/NFPJAQ

The data used consists of two lists, one of edges and one of nodes. To import those in Gephi, it is necessary to open them as a text file (e.g. in Notepad++) and rename the columns, so that the node id column is "Id", and the edge table contains the columns "source" and "target". The modified files can be imported in Gephi as a table of nodes and table of edges. You do not have to do it yourself, as the resulting files are included.

The folder contains three subfolders:
- *02 - Dataverse raw data* contains the original files from the Harvard repository. Note: it contains the files for many more novels than *A dance with dragons*!
- *03 - A Dance With Dragons CSV renamed columns* contains the files with renamed column names.
- *04 - A Dance With Dragons network* contains the Gephi network:
	1. as the raw GEXF
	2. with colors and a layout algorithm applied
	3. as a PDF export

Note 1: the step 01 was the raw zipped data from Harvard's dataverse. It is not replicated here.

Note 2: the paper where the data is from, *Social Characters: The Hierarchy of Gender
in Contemporary English-Language Fiction* by Eve Kraicer and Andrew Piper is also included as a PDF.

## Steam games

The data set comes from this repository:
https://www.kaggle.com/trolukovich/steam-games-complete-dataset

The original data consists of a table of the games published on Steam, with a number of metadata beyond their name: tags, developer, publisher, ratings...

This data can be transformed into a Gephi-compatible network by the online tool [Table 2 Net](https://medialab.github.io/table2net/). There are different kinds of networks that can be extracted (see below).

The folder contains the following subfolders:
- *01 raw file* is the original CSV table, uploadable in Table 2 Net
- *02 games and tags* contains an extraction of the bipartite network of games and their tags:
	- as a raw network
	- with colors and layout applied
- *03 developers and publishers* contains an extraction of the bipartite network of developers and publishers who collaborated on the same games:
	- as a raw network
	- with colors and layout applied

