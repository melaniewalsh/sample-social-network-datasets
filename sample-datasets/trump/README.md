## Source

This folder contains network data for relationships between President Donald Trump and other people, which was originally compiled by John Templon, Anthony Cormier, Alex Campbell, and Jeremy Singer-Vine as part of a larger project of [mapping "TrumpWorld" for BuzzFeed News](https://www.buzzfeed.com/johntemplon/help-us-map-trumpworld?utm_term=.wloL0RAvM#.ru1M6Y21D).

The full dataset, which you can access as [a Google Sheet](https://docs.google.com/spreadsheets/d/1Z5Vo5pbvxKJ5XpfALZXvCzW26Cl4we3OaN73K9Ae5Ss/edit#gid=1996904412) or [on GitHub](https://github.com/BuzzFeedNews/trumpworld) also includes information about organizations and agencies. The data was compiled by culling from "public records, news reports, and other sources on the Trump family, his Cabinet picks, and top advisers," as well as via crowdsourced tips and information from the public ([if you have any more, you can contribute them here)](https://tips.buzzfeed.com/).

## Data & Methodology

Nodes: 303; unimodal

Edges: 366; unweighted; undirected

The nodes csv contains 303 different people, and the edges csv contains 366 unweighted relationships between those people, such as friendship, business partner, donor, parent/child, cabinet member, spouse, and more. This information about the relationships, along with the sources from which they were identified, is included as a column (and potential attribute) in the edges csv.

As stated above, the data was compiled by culling from "public records, news reports, and other sources on the Trump family, his Cabinet picks, and top advisers," as well as via crowdsourced tips.

*In order to make this data more accessible for basic social network analysis, I have condensed the network to only the top 303 most connected people in TrumpWorld.

## Background & Significance

The relationships between President Donald Trump and other people lend themselves well to basic social network analysis because, as Templon, Cormier, Campbell, and Singer-Vine suggest, "No American president has taken office with a giant network of businesses, investments, and corporate connections like that amassed by Donald J. Trump."

Further, the social network analysis of some of the most powerful people in the nation and the world might help contribute to what Lauren Klein called for at the end of her [2018 MLA talk "Distant Reading After Moretti"](http://lklein.com/2018/01/distant-reading-after-moretti/)--that is, computational analysis "trained on power." 