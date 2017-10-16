+++
date = "2017-10-16T11:00:00"
draft = false
title = "Paper Resources"
math = true
+++



# Resources for "Study of Methods for Abstract Screening in a Systematic Review Platform"
____________________________________________________________
## {{% staticref "files/sysrev_graphical.jpg" %}} Download Graphical Abstract. {{% /staticref %}}
## {{% staticref "files/sysrevslide.pdf" %}} Download Slide. {{% /staticref %}}
## {{% staticref "files/sysrev.zip" %}} Download Results. {{% /staticref %}}

## Some interesting query results from our trained word2vec model.

| Query           | Result                    |
| ------------------------------| ------------------------------ |
| model.similarity (\`liver', \`cirrhosis')           | 0.63             |
| model.similarity (\`breast',\`cancer')  | 0.46           |
| model.most\_similar(positive=[\`liver'], top-k with k=10) | hepatic (0.67), cirrhosis (0.63), cholestatic (0.51), spleen (0.51), steatosis (0.5), kidney (0.50), steatohepatitis (0.50), extrahepatic (0.46), pancreas (0.45), cirrhotic (0.45)|
| model.most\_similar(positive=[\`cancer',\`cirrhosis'], negative=[\`breast'], top-k with k=5) | cirrhotic (0.46), hcc (0.46), liver (0.45), heptocellular (0.43), metavir (0.43)           |
| |  |

## Compiled Results for RelRank (3-star), RelRank (4-star) and RelRank (5-star)

### RelRank (3-star)
| Metric  | Low Preval. | Mid Preval.| High Preval.
| --------| -------|---------|-------|
| Prec| 3.78|11.78|22.98|
| Recall |96.11|97.65|98.43|
| AUC| 86.38| 86.70| 86.84|
| AUCPR| 36.27| 49.87| 63.81|
| Burden|90.06|91.10|93.03|
| Utility|93.64|94.32|94.60|
| Yield|98.04|98.82|99.21|
| AM Error|0.417|0.414|0.424|
| QM Error| 0.517| 0.573| 0.591|

### RelRank (4-star)

| Metric  | Low Preval. | Mid Preval.| High Preval.
| --------| -------|---------|-------|
|Prec|4.63|15.56|31.43|
|Recall|92.4|94.16|93.82|
| AUC| 86.38| 86.70| 86.84|
| AUCPR| 36.27| 49.87| 63.81|
|Burden|78.29|78.80|78.89|
|Utility|92.38|93.28|93.12|
|Yield|96.10|97.08|96.91|
|AM Error|0.316|0.298|0.276|
|QM Error|0.407|0.385|0.353|

### RelRank (5-star)

| Metric  | Low Preval. | Mid Preval.| High Preval.
| --------| -------|---------|-------|
|Prec|6.22|21.77|41.62|
|Recall|85.37|86.50|84.108|
| AUC| 86.38| 86.70| 86.84|
| AUCPR| 36.27| 49.87| 63.81|
|Burden|68.24|68.66|69.15|
|Utility|89.63|90.15|88.99|
|Yield|92.67|93.25|92.05|
|AM Error|0.248|0.228|0.216|
|QM Error|0.286|0.283|0.230|

