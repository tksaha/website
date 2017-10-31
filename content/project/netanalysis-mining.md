+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Network Analysis and Mining"

# Project summary to display on homepage.
summary = "Mining information from a set of networks (graph Mining), finding important subnetwork from a single large network (motif finding)."

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["network-analysis", "bio-informatics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

The main objective of Frequent Subgraph Mining (FSM) is finding subgraph patterns that are frequent across a collection of graphs.  Another important task is to find subgraphs which are candidate for motif in a given network. For this, we need to count each topology's frequency in the input network as well as in many randomized networks. Counting a topology's frequency in a single network is a challenging task as it requires solving subgraph isomorphism, a known $NP$-complete problem. In both the cases, I propose a sampling based solution which is efficient and works better than state-of-art methods. In [1], I propose a method for frequent subgraph mining, called $FS^{\large 3}$,
that is based on sampling of subgraphs of a fixed size (The name $FS^{\large 3}$
should be read as $F-S-Cube$, which is a compressed representation of the
4-gram composed of the bold letters in $\bf F$ixed $\bf S$ize $\bf S$ubgraph
$\bf S$ampler. In [2], I
propose method on finding concentration of prospective motifs using a novel sampling
based method. In subsequent works, I show that the algorithm ($FS^{\large 3}$) I developed for graph mining can be applied to find essential structures when applied to the interfacial region of a set of oligomeric proteins [3] and the algorithm for motif finding [2] can be used to classify apps from google app store as malignant or benign [4]. 



# Publications

[1] **Tanay Kumar Saha** and Mohammad Al Hasan. "$FS^{\large 3}$: A sampling based method for top‐k frequent subgraph mining." Statistical Analysis and Data Mining: The ASA Data Science Journal 8.4 (2015): 245-261. [[PDF]](http://onlinelibrary.wiley.com/doi/10.1002/sam.11277/full) 

[2] **Tanay Kumar Saha** and Mohammad Al Hasan. "Finding Network Motifs Using MCMC Sampling." In CompleNet (pp. 13-24). [[PDF]](https://link.springer.com/chapter/10.1007/978-3-319-16112-9_2)

[3] **Tanay Kumar Saha**, Ataur Katebi, Wajdi Dhifli and  Mohammad Al Hasan. "Discovery of Functional Motifs from the Interface Region of Oligomeric Proteins using Frequent Subgraph Mining." IEEE/ACM Transactions on Computational Biology and Bioinformatics. [[PDF]](http://ieeexplore.ieee.org/document/8051102/)

[4] Wei Peng, Tianchong Gao, Devkishen Sisodia, **Tanay Kumar Saha**, Feng Li, and Mohammad Al Hasan. "ACTS: Extracting android App topological signature through graphlet sampling." In 2016 IEEE Conference on Communications and Network Security (CNS),  (pp. 37-45). [[PDF]](http://ieeexplore.ieee.org/abstract/document/7860468/)
