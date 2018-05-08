## Source

This folder contains network data for books about US politics that were published around the time of the 2004 presidential election and co-purchased by the same buyers. This data was [originally compiled and analyzed by Valdis Krebs](http://www.orgnet.com/divided2.html).

## Data & Methodology

Nodes: 105; unimodal

Edges: 441; unweighted; undirected

The nodes csv contains 105 different political book titles, and the edges csv contains 441 unweighted relationships between those books, which represent being co-purchased by the same buyer.

Krebs selected political books from the *New York Times* bestseller list, searched for those books within Amazon and Barnes&Noble, and then recorded a co-purchasing relationship between the two books if they were connected by a 'customers who bought this book also bought...' link.

The nodes csv also contains attribute information about each book's political ideology--"conservative," "liberal," and "neutral"--though it is not entirely clear how this attribute was defined or identified. 

For more on the methodology, see [Krebs's website](http://www.orgnet.com/divided2.html) or [the New York Times feature](http://www.nytimes.com/2004/03/13/books/study-finds-a-nation-of-polarized-readers.html) on his work.

## Background & Significance

Though this network is not technically, or perhaps not exclusively, a social one, the network reveals and suggets potential patterns about the communities of people buying these books. It also calls into question how forms of media consumption might influence, shape, reinforce, or reflect national political polarization. 
