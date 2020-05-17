## Jigsaw toxic comment
[Jigsaw toxic comment classification](https://www.kaggle.com/c/jigsaw-multilingual-toxic-comment-classification): this is a kaggle NLP project in 2020. The main goal of this project is to apply state of
the art deep learning model to idendity toxic comment in online conversation, where toxicity is defined as rude, disrespectful
or any other form of discussion that may offend people. 

### Data Source
The training dataset comes from civil comments or Wikipedia talk page.

### NLP Model
The pretrained [XLM-RoBERTa](https://arxiv.org/pdf/1911.02116.pdf) model used in this project comes from [huggingface.co](https://huggingface.co/). The support of multi language and extremely large training data ensures XLM-RoBERTa a good performance on multilingual classification tasks. 

### Results
This model gained a 0.9462 AUC score and ranked top 15% in kaggle leaderboard.

The training process is boosted by the kaggle TPU which is available when using [kaggle notebook](https://www.kaggle.com/kernels) and distributed training strategy by [tensorflow](https://www.tensorflow.org/guide/tpu).
