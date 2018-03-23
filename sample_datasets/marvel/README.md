## Source

This folder contains network data for character relationships within the Marvel comic book universe (beginning in 1961 and ending around 1999/2000?), which was originally compiled by Cesc Rosselló, Ricardo Alberich, and Joe Miro from Russ Chappell's [Marvel Chronology Project](http://www.chronologyproject.com/)*, a database that catalogues every appearance by every significant character in the Marvel comic book universe. This network data was originally used and analyzed by Rosselló, Alberich, and Miro in ["Marvel Universe looks almost like a real social network."](https://arxiv.org/pdf/cond-mat/0202174.pdf)

*This website is astounding both in its comprehensiveness and its fabulous '90s web aesthetic.

## Data & Methodology

Nodes: 327; unimodal*

Edges: 9,891; weighted; undirected

The nodes csv contains 327 different Marvel characters, and the edges csv contains 9,891 weighted relationships between those characters, which were calculated based on how many times two characters appeared together in the same comic book.

To explore and understand the edges better, you might take a look at [the bimodal edges list](bimodal/marvel_bimodal_edges.csv) and [the comic book key](http://www.chronologyproject.com/key.php) from the Marvel Chronology Project. For more on the methodology, see [Rosselló, Alberich, and Miro's original article.](https://arxiv.org/pdf/cond-mat/0202174.pdf)

*In order to make this data more accessible for basic social network analysis, I have condensed the network from 6,486 characters to only the top 327 most connected characters, who are connected to at least 8 other characters and with whom they appear in at least 5 different comic books.

## Background & Significance

The Marvel Universe data lends itself well to basic social network analysis because there are a lot of characters, a lot of communities or teams of characters, and a lot of crossovers between those characters in individual comic books.

If you've been to the movies in the last 10 years, you might be familiar with the extensive crossover nature of the Marvel Universe. But here's a bit more background info and an explanation from Rosselló, Alberich, and Miro about why these relationships might be particularly well-suited for social network analysis:

>One of the main features of Marvel Comics from the sixties to our days has been the creation and development, under the leading pen of Stan Lee, of the so-called Marvel Universe. Although crossovers (a hero with its own title series appears in an issue of another hero’s series) were not uncommon in the Golden Age period, the nature and span of the crossovers in the books from the Marvel Age led to the perception that all Marvel characters lived their adventures in the same fictional cosmos, called the Marvel Universe, where they interacted like real actors. This concept was helped by the interrelation of all titles that were being created, which made characters and even plots cross over on a regular basis, by the appearance of the same villains and secondary characters in comic books of different titles, and by
continuous references to events that were simultaneously happening, or had happened, in
other books...

>The Marvel Universe network captures the social structure of this Marvel Universe, because most pairs of characters that have jointly appeared in the same comic book have fought shoulder to shoulder or each other, or have had some other strong relationship, like family ties or kidnapping. Thus, it shares, in its artificial way, the true social nature of scientific collaboration networks, while the way it has grown has echoes of the Hollywood network, as writers, directors and producers create their characters and assign them to actors in a way that somewhat resembles the way Marvel writers make characters appear in comic books.

If you still need more information about the Marvel Universe to make sense of this data as a social network, you might take a look at [Marvel's breakdown of heroes, villains, and teams](http://marvel.com/characters).