# Multimodal Machine Translation - Tamil Dataset
Multilingual Multimodal Machine Translation for Dravidian Languages utilizing Phonetic Transcription

Multimodal machine translation is the task of  translating  from  a  source  text  into  the target  language  using  information  from other  modalities. Existing  multimodal datasets have been restricted to only highly resourced  languages.   In  addition  to  that, these  datasets  were  collected  by  manual translation  of  English  descriptions  from the  Flickr30K  dataset.   In  this  work,  we introduce MMDravi, a Multilingual Multi-modal dataset for under-resourced Dravidian languages. It comprises of 30,000 sentences which were created utilizing several machine  translation  outputs.   Using  datafrom  MMDravi  and  a  phonetic  transcription of the corpus, we build an Multilingual Multimodal  Neural  Machine  Translation system (MMNMT) for closely related Dravidian languages to take advantage of multilingual corpus and other modalities.  We evaluate our translations generated by the proposed approach with human-annotated evaluation dataset in terms of BLEU, METEOR,  and  TER  metrics. Relying  onmultilingual  corpora,  phonetic  transcription, and image features, our approach improves the translation quality for the under-resourced languages.

If you are using the dataset please cite the paper

```
@inproceedings{chakravarthi-etal-2019-multilingual,
    title = "Multilingual Multimodal Machine Translation for {D}ravidian Languages utilizing Phonetic Transcription",
    author = "Chakravarthi, Bharathi Raja  and
      Priyadharshini, Ruba  and
      Stearns, Bernardo  and
      Jayapal, Arun  and
      S, Sridevy  and
      Arcan, Mihael  and
      Zarrouk, Manel  and
      McCrae, John P",
    booktitle = "Proceedings of the 2nd Workshop on Technologies for MT of Low Resource Languages",
    month = aug,
    year = "2019",
    address = "Dublin, Ireland",
    publisher = "European Association for Machine Translation",
    url = "https://www.aclweb.org/anthology/W19-6809",
    pages = "56--63",
}
```

The dataset can be downloaded from https://zenodo.org/record/4765597#.YKEB-yYo_0M
