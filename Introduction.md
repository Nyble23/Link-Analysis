# Link-Analysis

The analysis of hyperlinks and the graph structure of the Web is a crucial part of web development. One way to rank web search result is to use hyperlinks. **Link Analysis** is one of the many factors that are used by search engines  to compute a score of a web page for any given query.
Link analysis treats hyperlinks of a web page as a conferral of authority. But simply measuring the number of in-links is not a robust procedure.

**Link Spam**:  One might try to setup multiple web pages pointing to a target webpage, so that the number of in-links of the target web-page gets boosted up artificially. This is known as Link Spam.

In order to combat spammers who do such manipulations, it becomes necessary to exploit the structure of the web.

***The first web search engine known to apply link analysis on a large scale was Google.***

To perform link analysis, a real-world network dataset was picked up from [here](https://snap.stanford.edu/data/index.html). I chose a simple Wikipedia network, [Wikipedia vote network](https://snap.stanford.edu/data/wiki-Vote.html).
Some functions from the famous *networkx* python library have also been used.
