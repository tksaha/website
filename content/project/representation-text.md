+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Representation Learning of Textual Units"

# Project summary to display on homepage.
summary = "Learning to understand the semantics of natural language text (e.g., words, sentences, paragraph) by representing them in lower dimensional space."

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["deep-learning", "nlp", "text-mining"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

In classical machine learning, hand-designed features are used for learning a mapping from the features. However, recently, there is a surge of research in representation learning which aims to learn abstract features given the input. For textual domain, representation learning focuses on learning important semantic information from words, phrases, sentences or any arbitrary unit of texts, such as paragraphs and documents. The learned representation can be used in various data mining tasks, such as classification, clustering, summarization and many others.


Recent studies on learning distributed representations for $words$ have shown that semantic relations between words (e.g., synonymy, hypernymy, hyponymy) encoded in semantic lexicons like WordNet  or Framenet  can improve the quality of word vectors that are trained solely on unlabeled data. My works [1,2] are reminiscent of this line of research with a couple of crucial differences. Firstly, I am interested in the representation of sentences as opposed to words, for the former such resources are not readily available. Secondly, my main goal is to incorporate extra-sentential context in some form of inter-sentence relations as opposed to semantic relations between words. These differences posit many new research challenges: (1) how can we obtain extra-sentential context that can capture semantic relations between sentences? (2) how can we effectively exploit the inter-sentence relations in our representation learning model? We solve these problems either by retrofitting or regularizing using the context network [1] or through a joint model [2] which predicts and regularize based on the context network of sentences. The joint model [2] is generic in terms of context and different modes of data the model can handle. The software is freely available from [github](https://github.com/tksaha/con-s2v/tree/jointlearning).


# Publications

[1] **Tanay Kumar Saha**, Shafiq Joty, and  Mohammad Al Hasan. "Regularized and Retrofitted models for Learning Sentence Representation with Context." **CIKM 2017**. [[PDF]](https://www.researchgate.net/profile/Tanay_Saha/publication/320068899_Regularized_and_Retrofitted_models_for_Learning_Sentence_Representation_with_Context/links/59d4e88eaca2721f436ff788/Regularized-and-Retrofitted-models-for-Learning-Sentence-Representation-with-Context.pdf)

[2] **Tanay Kumar Saha**, Shafiq Joty, and  Mohammad Al Hasan. "CON-S2V: A Generic Framework for Incorporating Extra-Sentential Context into Sen2Vec." **ECML PKDD 2017**. [[PDF]](https://pdfs.semanticscholar.org/0e67/3c6ce330d57a2548415e563cb181fc6644ff.pdf)
