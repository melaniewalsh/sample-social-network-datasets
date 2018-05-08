## Source

This folder contains network data for relationships between seventeenth-century Quakers, which was originally compiled by John Ladd, Jessica Otis, Christopher N. Warren, and Scott Weingart for their [Programming Historian tutorial about NetworkX](https://programminghistorian.org/lessons/exploring-and-analyzing-network-data-with-python) (a Python package for working with network data). 

This Quaker data was excerpted from a larger dataset and project with which the authors are all associated, the very wonderful [Six Degrees of Francis Bacon](http://sixdegreesoffrancisbacon.com/?ids=10000473&min_confidence=60&type=network), a reconstruction of the early modern social network of Britain (1500-1700).

## Data & Methodology

Nodes: 96; unimodal*

Edges: 162; unweighted; undirected

The nodes csv contains 96 different Quakers, and the edges csv contains 162 unweighted relationships between those Quakers, which were computationally inferred through the *Oxford Dictionary of National Biography* and confirmed and expanded through the crowdsourced contributions of scholars and students. For more on their methodology, see ["Six Degrees of Francis Bacon: A Statistical Method for Reconstructing Large Historical Social Networks."](http://www.digitalhumanities.org/dhq/vol/10/3/000244/000244.html)

The nodes csv also contains attribute information such as "historical significance," "gender," "birthdate," and "deathdate."

*I have slightly condensed and modified the data from the Programming Historian tutorial. 

## Background & Significance

The relationships between seventeenth-century Quakers lend themselves well to social network analysis because, as the authors of the Programming Historian tutorial suggest, "scholars have long linked Quakers’ growth and endurance to the effectiveness of their networks":

>Before there were Facebook friends, there was the Society of Friends, known as the Quakers. Founded in England in the mid-seventeenth century, the Quakers were Protestant Christians who dissented from the official Church of England and promoted broad religious toleration, preferring Christians’ supposed “inner light” and consciences to state-enforced orthodoxy. Quakers’ numbers grew rapidly in the mid- to late-seventeenth century and their members spread through the British Isles, Europe, and the New World colonies—especially Pennsylvania, founded by Quaker leader William Penn and the home of your four authors.