+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Name Disambiguation"

# Project summary to display on homepage.
summary = "The task of solving name entity disambiguation using only graph topological information."

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["network-analysis"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

Entity disambiguation is
not a new problem. In fact, named entity disambiguation has been a long
standing problem in the field of bibliometrics and library science. The key
reason for this is that many distinct authors share the same name, specifically
considering the fact that the first name of an author is typically written in
abbreviated form in the citation of many scientific journals. Thus,
bibliographic servers that maintain such data may mistakenly aggregate the
records from different persons into a single entity. In [1,2], I design the task of solving name entity disambiguation using only graph topological information. We propose a simple solution that is robust and it takes only a few seconds to disambiguate a given node in real-life academic collaboration networks. The proposed method returns a real-valued score to rank the vertices of a network based on
their likelihood for being an ambiguous node. So the score can be used as a pre-filter for identifying a small set of ambiguous references for subsequent analysis with a full set of features. Besides, the
score can also be used independently as a feature for classification based solutions for entity disambiguation. This work is motivated by the growing need of data analysis without violating the privacy of the actors in a social network. 


# Publications

[1] **Tanay Kumar Saha**, Baichuan Zhang, and Mohammad Al Hasan. "Name disambiguation from link data in a collaboration graph." 2014 IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining (ASONAM), (pp. 81-84). [[PDF]](http://ieeexplore.ieee.org/abstract/document/6921563/)

[2] **Tanay Kumar Saha**, Baichuan Zhang, and Mohammad Al Hasan. "Name disambiguation from link data in a collaboration graph using temporal and topological features." Social Network Analysis and Mining, 5(1), 11. [[PDF]](https://link.springer.com/article/10.1007/s13278-015-0249-1)

