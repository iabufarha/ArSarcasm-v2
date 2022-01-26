# ArSarcasm-v2 Dataset

**ArSarcasm-v2** is an extension of the original ArSarcasm dataset published along with the paper [From Arabic Sentiment Analysis to Sarcasm Detection: The ArSarcasm Dataset](https://www.aclweb.org/anthology/2020.osact-1.5/). ArSarcasm-v2 conisists of ArSarcasm along with portions of [DAICT corpus](https://www.aclweb.org/anthology/2020.lrec-1.768/) and some new tweets. Each tweet was annotated for sarcasm, sentiment and dialect. The final dataset consists of 15,548 tweets divided into 12,548 training tweets and 3,000 testing tweets. ArSarcasm-v2 was used and released as a part of the [shared task on sarcasm detection and sentiment analysis in Arabic](https://sites.google.com/view/ar-sarcasm-sentiment-detection/). You can find more details in the [Overview of the WANLP 2021 Shared Task on Sarcasm and Sentiment Detection in Arabic](https://aclanthology.org/2021.wanlp-1.36/)

## Dataset details:
**ArSarcasm-v2** is provided in a CSV format, we provide the same split that was used for the shared task. The training set contains 12,548 tweets, while the test set contains 3,000 tweets.

The dataset contains the following fields:
* `tweet`: the original tweet text.
* `sarcasm`: boolean that indicates whether a tweet is sarcastic or not.
* `sentiment`: the sentiment of the tweet (positive, negative, neutral).
* `dialect`: the dialect used in the tweet, we used the 5 main regions in the Arab world, follows the labels and their meanings:
  * `msa`: modern standard Arabic.
  * `egypt`: the dialect of Egypt and Sudan.
  * `levant`: the Levantine dialect including Palestine, Jordan, Syria and Lebanon.
  * `gulf`: the Gulf countries including Saudi Arabia, UAE, Qatar, Bahrain, Yemen, Oman, Iraq and Kuwait.
  * `magreb`: the North African Arab countries including Algeria, Libya, Tunisia and Morocco.


## Citation
Please use the following citation if you use ArSarcasm-v2:
```
@inproceedings{abufarha-etal-2021-arsarcasm-v2,
title = "Overview of the WANLP 2021 Shared Task on Sarcasm and Sentiment Detection in Arabic",
    author = "Abu Farha, Ibrahim  and
    Zaghouani, Wajdi  and
    Magdy, Walid",
    booktitle = "Proceedings of the Sixth Arabic Natural Language Processing Workshop",
    month = april,
    year = "2021",
    }

```

## Other resources
If you are interested in other Arabic NLP resources check:
* [Mazajak Sentiment Analyser](http://mazajak.inf.ed.ac.uk:8000)
* [Mazajak Word Embeddings](http://mazajak.inf.ed.ac.uk:8000/#embedding-page)
