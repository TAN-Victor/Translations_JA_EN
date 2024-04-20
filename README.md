# NLP Project] Enhancing Machine Translation of News: Japanese to English Translation

We used JParacrawl dataset. Due to its size (9 GB for 22M sentences), we utilized a subset of 150,000 sentences and applied preprocessing and postprocessing techniques. This dataset has been converted to .csv format.

- [Helsinki_single.ipynb](Helsinki_single.ipynb) : PostProcessing techniques applied for some examples. You can also try your own translation. For more simplicity and ease, there are only BLEU, Chrf, and SacreBLEU as scoring metrics,

- [results.ipynb](results.ipynb) : Final notebook to compute the scores, you will need some old packages, so it is not really recommended to run it. You can (or should) comment out the part related to COMET as it may conflict with many other packages,

- [experiments.ipynb](experiments.ipynb) : All steps to get [results.ipynb](results.ipynb). Not meant to be run, as it will take you several hours to have 1 result. See [Helsinki_single.ipynb](Helsinki_single.ipynb) instead for single sentences translation,

- [data.csv](data.csv) : All sentences with translations with differents techniques,

- [results.txt](results.txt) : All scores and techniques used. But Tan_Report.pdf should be better.

- [Tan_Report.pdf](Tan_Report.pdf) : Report.

The Attempts folder contains the previous experiments, with Mistral, mBART and BERT. No results.

