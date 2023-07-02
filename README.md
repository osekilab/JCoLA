# JCoLA: Japanese Corpus of Linguistic Acceptability
JCoLA (Japanese Corpus of Linguistic Accept010 ability) is a novel dataset for targeted syntactic evaluations of language models in Japanese, which consists of 10,020 sentences with acceptability judgments by linguists. The sentences are manually extracted from linguistics journals, handbooks and textbooks. JCoLA is included in [JGLUE benchmark](https://github.com/yahoojapan/JGLUE)  (Kurihara et al., 2022).

## Repository contents
- jcola-v1.0
   - `in_domain_train-v1.0.{json, csv}`
   - `in_domain_valid-v1.0.{json, csv}`
   - `out_of_domain_valid-v1.0.json`
   - `out_of_domain_valid_annotated-v1.0.{json, csv}`
     - The development split of out-of-domain data with annotation of the linguistic phenomenon. Note that a sentence can be categorized into multiple phenomena (more than one column can be `True`).

## Data description
|Name|Description|
|----|-----|
|uid|The unique id of the sentence.|
|soruce|The author and the year of publication of the source article.|
|label|The acceptability judgement label (0 for unacceptable, 1 for acceptable)|
|diacritic|The acceptability judgement as originally notated in the source article.|
|sentence|The sentence (modified by the author if needed).|
|original|The original sentence as presented in the source article.|
|translation|The English translation of the sentence as presentend in the source article (if any).|
|gloss|The gloss of the sentence as presented in the source article (if any).|
|{linguistic phenomenon}| The flag to indicate if the sentence' category. (`True` if the sentence is categorized into this linguistic phenomenon, `False` otherwise)|

## Refernece

```
arxiv
```

## License
Most of the example sentences are extracted from linguistic journals without any modification. Hence, in most cases, the copyright of the example sentences remains with the original authors or publishers.

## Updates
