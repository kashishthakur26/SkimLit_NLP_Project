
# SkimLit_NLP_project 

The purpose of this notebook is to build an NLP model to make reading medical abstracts easier. An NLP model to classify abstract sentences into the role they play (e.g. objective ,menthods,results , background , conclusion.) to enable researchers to skim through the literature and dice deeper when necessary.


## Data used

 - [PubMed_20k_RCT_numbers_replaced_with_at_sign](https://github.com/Franck-Dernoncourt/pubmed-rct/tree/master/PubMed_20k_RCT_numbers_replaced_with_at_sign)



## Documentation

[PubMed 200k RCT:
a Dataset for Sequential Sentence Classification in Medical Abstract](https://arxiv.org/pdf/1710.06071.pdf)


Short-text classification is an important task in many areas of natural language processing, such as sentiment analysis, question answering, or dialog management. For example, in a dialog management system, one might want to classify each utterance into dialog acts.We focus on classifying sentences in
medical abstracts, and particularly in randomized
controlled trials (RCTs), as they are commonly
considered to be the best source of medical evidence (Tianjing Li, 2015). Since sentences in an
abstract appear in a sequence, we call this task the
sequential sentence classification task, in order to
distinguish it from general text or sentence classification that does not have any contex.


## Models used:

| Model_name             | Accuracy                                                             |
| ----------------- | ------------------------------------------------------------------ |
| model_0_baseline | 72.183238 |
| model_1_custom_token_embedding | 78.614458 |
| model_2_pretrained_token_embedding| 71.355753 |
| model_3_custom_char_embedding | 65.775189 |
| model_4_hybrid_char_token_embedding | 73.394678 |
| model_5_pos_char_token_embedding | 83.185489	 |
## Results of All Six Models

![output_of_all_6_models](https://github.com/kashishthakur26/SkimLit_NLP_Project/assets/120331369/c344be2c-387d-41e2-a82c-8e6a147ac438)


![results_of_all_models](https://github.com/kashishthakur26/SkimLit_NLP_Project/assets/120331369/5b81c65c-a186-4b44-ae88-e7936574ef87)


## References

* [@mrdbourke](https://github.com/mrdbourke/tensorflow-deep-learning)
* [arxiv](https://arxiv.org/abs/1710.06071)

