# Distributed-AWS-Training-Moderation

Welcome to my end-to-end `non-distributed` and `distributed` multilabel text-classifier example. In this demo, we will use the Hugging Face `transformers` and `datasets` library together with a custom Amazon sagemaker-sdk extension to fine-tune a pre-trained transformer for multilabel text-classification on a single or multiple-gpus. In particular, the pre-trained model will be fine-tuned using the `tweet_eval: emotion` dataset. The demo will use the new `smdistributed` library to run training on multiple gpus. 
