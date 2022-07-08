# JCoLA: Japanese Corpus of Linguistic Acceptability

JCoLA is a novel dataset for targeted syntactic evaluations of language models in Japanese,
which consists of acceptability judgements extracted from journal articles in theoretical linguistics.
JCoLA is included in [JGLUE benchmark](https://github.com/yahoojapan/JGLUE)  (Kurihara et al., 2022).

All the acceptability judgements were extracted from journal articles on Japanese syntax published in JEAL (Journal of East Asian Linguistics).
The number of acceptability judgements is 2,323 in total.

## Data cleansing
1. deleteQA
2. delete incomplete sents.
3. different labels for the same sentence
4. duplicated sents.

## Repository contents
-
## Data description

|Name|Description|
|----|-----|
|sentence_id|The unique id of the sentence.|
|year|The year of publication of the source article.|
|author|The author of the source article.|
|num|The sentence number in the source article.|
|diacritic|The acceptability judgement as originally notated in the source article.|
|label|The acceptability judgement label (0 for unacceptable, 1 for acceptable)|
|type|The categorization based on the type of acceptability judgements.|
|phenomenon|The categorization based on the linguistic phenomenon.|
|phenomenon-2|The categorization based on the linguistic phenomenon (if the sentence is grouped into 2 categories).|
|paradigm|The subcategorization of the phenomenon column.|
|raw_sentence|The original sentence as presented in the source article.|
|sentence|The sentence (modified by the author if needed).|
|gloss|The gloss of the sentence as presented in the source article (if any).|
|translation|The English translation of the sentence as presentend in the source article (if any).|

## Refernece

```
@InProceedings{Someya_nlp2022,
  author = 	"染谷大河 and 大関洋平",
  title = 	"日本語版CoLAの構築",
  booktitle = 	"言語処理学会第28回年次大会",
  year =	"2022",
  url = "https://www.anlp.jp/proceedings/annual_meeting/2022/pdf_dir/E7-1.pdf"
  note= "in Japanese"
}
```

## License
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />


## Updates
**1 July 2022** 18 acceptability judgements were removed because these were sentences presented for analyses of syntactic structures.
The total number of acceptability judgements has become 2,305.

**1 July 2022** Yoon(2013) was removed from source paper, because this paper doesn't exclusively adress Japanese syntax.
The total number of acceptability judgements has become 2,250.

**Coming soon** We are planning to increase the size of JCoLA.
