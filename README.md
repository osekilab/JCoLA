# JCoLA: Japanese Corpus of Linguistic Acceptability

JCoLA is a novel dataset for targeted syntactic evaluations of language models in Japanese. JCoLA consists of 2,323 sentences with acceptability judgements extracted from journal articles in theoretical linguistics. 

These minimal pairs are grouped into 11 categories, each covering a different linguistic phenomenon. JBLiMP is unique in that it successfully combines two important features independently observed in existing datasets: (i) coverage of complex linguistic phenomena (cf.~CoLA;~\citealp{Warstadt2019-ru}) and (ii) presentation of sentences as minimal pairs (cf.~BLiMP;~\citealp{Warstadt2020-qe}). We evaluate the syntactic knowledge of several language models on JBLiMP: GPT-2 \citep{Radford_2019}, LSTM \citep{Hochreiter1997-is} and \textit{n}-gram language models. The results demonstrated that all the architectures achieved comparable overall accuracies around 75\%. Error analyses by linguistic phenomenon further revealed that these language models successfully captured local dependencies such as morphological constraints and nominal structures, but not long-distance dependencies such as verbal agreement and anaphor/binding.


## Contents

## Data Description


|Name|Description|
|----|-----|
|title|title of a Wikipedia article|
|paragraphs|a set of paragraphs|
|qas|a set of pairs of a question and its answer|
|question|question|
|id|id of a question|
|answers|a set of answers|
|text|answer text|
|answer_start|start position (character index)|
|is_impossible|all the values are `false`|
|context|a concatenation of the title and paragraph|

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
*Coming soon* We are planning to increase the size of JCoLA.
