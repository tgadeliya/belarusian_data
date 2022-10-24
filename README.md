# [WIP] Data for Belarusian language 
  Collection of resources useful for NLP in Belarusian 

Models
-----
| Name  | Type | Description | Belarus language source  |
|---|---|---|---|
|[XLM-R](https://arxiv.org/abs/1911.02116)| LM | Multilingual RoBERTa model | CC-100 corpus  |
|[mBERT UnCased](https://github.com/google-research/bert/blob/master/multilingual.md#list-of-languages)| LM | BERT-base trained on 104 languages' Wikipedia  | Wikipedia |
|[mBERT Cased](https://github.com/google-research/bert/blob/master/multilingual.md#list-of-languages) |LM | BERT-base trained on 102 languages' Wikipedia. Recommended by authors | Wikipedia  |
|[Distilled mBERT](https://huggingface.co/distilbert-base-multilingual-cased) | LM | Distilled version of mBERT cased | Wikipedia |
|[InfoXLM](https://arxiv.org/abs/2007.07834) | LM | | CCNet corpus |
|[XLM-Align](https://aclanthology.org/2021.acl-long.265/) | LM | | CCNet corpus |
|[mT6](https://aclanthology.org/2021.acl-long.265/) | LM | | CCNet corpus |
|[mT5](https://arxiv.org/abs/2010.11934) | Text-to-text |  | be Belarusian 2.0 1.7 0.59  |
|[XLM-E](https://arxiv.org/abs/2010.11934) | LM | (Weights not available) multilingual ELECTRA model pretrained on mono- and multi- lingual tasks  | CC-100 corpus  |
|[M2M](https://arxiv.org/abs/2010.11125) | Many-to-many translation | MT with focus on translation pairs xx -> yy, where xx and yy not English |  |
|[NLLB](https://arxiv.org/abs/2207.04672) | Many-to-many translation | |  |
|[mGPT](https://arxiv.org/abs/2204.07580)| CLM | Reproduction of GPT-3 for ~60 languages | |
|[Canine_s](https://arxiv.org/abs/2204.07580)| LM |Tokenization-free encoder | |
|[mBERT for passage reranking](https://huggingface.co/amberoad/bert-multilingual-passage-reranking-msmarco) | | | 
|[RemBERT](https://arxiv.org/abs/2010.12821) | | | |
|[byT5](https://arxiv.org/abs/2105.13626)|Byte-to-Text | | mC4|
|[XLM](https://arxiv.org/abs/1901.07291) | | | multiple sources |
|[LaBSE](https://arxiv.org/abs/2007.01852)||||
|[LASER3](https://github.com/facebookresearch/LASER/blob/main/nllb/README.md)|sentence encoder|[repo](https://arxiv.org/abs/2205.12654)|encoder for belarusian|
|[fastText](https://fasttext.cc/)|-|Language identification and word representation models||

Datasets
-----
| Name  | Description |
|---|---|
|[Universal Dependencies for Belarus](https://github.com/UniversalDependencies/UD_Belarusian-HSE) |  | 



Corpuses 
----- 
| Source  | Description | Statistics  |
|---|---|---|
|[OPUS](https://opus.nlpl.eu/)|Huge collection of open parallel corpus. Contains almost all corpuses presented below||
|  CC-100 | Common crawl |   |
| [CCNet](https://arxiv.org/abs/1911.00359)  | Improved pipeline to extract monolingual datasets from Web Crawl | be 176.037 × 103 9.719 × 106 124.716 × 106 476.612 × 106   |
|[OSCAR](https://arxiv.org/abs/2201.06642) | [Corpus](https://oscar-corpus.com/) from Common Crawl|Size=1.8 GB, Documents=180,046, Words=107,227,860|
| [TED](https://github.com/ajinkyakulkarni14/TED-Multilingual-Parallel-Corpus) |   |   |
|[mC4](https://huggingface.co/datasets/mc4)| |
|[mGENRE](https://arxiv.org/abs/2103.12528)|||
| [Tatoeba](https://tatoeba.org/en)|Collection of parallel sentence in many languages|||
|[Wikipedia 2021](https://corpora.uni-leipzig.de/en?corpusId=bel_wikipedia_2021)| Dump prepared by Leipzig university (2018 dump also available) |585,242 sentences and 8,058,542 tokens|
|[News 2020](https://corpora.uni-leipzig.de/en?corpusId=bel_news_2020)| Collection of belarusian news (news from 2019 and newscrawl 2011 is also available) |298,739 sentences and 4,141,950 tokens |
|[YABC](https://github.com/poritski/YABC)|Yet another Belarussian corpus - collection of texts from different magazines and small collections of Belarusian literature| |
|(Bible corpus)[https://biblija.bnkorpus.info/index.html#]|Contains 16 belarusian translations of Bible aligned with other languages for comparison ||


Raw Data in Belarusian
----
| Source | Description | Statistics |
|---| ---|---|
|[Opensubtitles.org](https://www.opensubtitles.org/en/search/sublanguageid-bel)|Collection of subtitle for movie in many languages| Subtitles in Belarusian for 22 languages|


Other
----
| Source | Description |
|---|---|
| | |



Unprocessed links and resources
----- 
- [Cross-lingual Name Tagging and Linking for 282 Languages](https://aclanthology.org/P17-1178/)
- https://arxiv.org/abs/2102.00894
- [NLLB data](https://github.com/facebookresearch/fairseq/blob/nllb/examples/nllb/data/README.md)
- [M2M sources list](https://arxiv.org/pdf/2010.11125.pdf)
- https://ruscorpora.ru/new/search-para-be.html 
- http://biblija.bnkorpus.info/translations.html
- http://grid.bntu.by/corpus/
- http://www.informatika.bf.uni-lj.si/magus-slavic3.html
- https://novychas.by/
- https://corpus.by/
- https://mymemory.translated.net/ 
- https://termcoord.eu/glossarylinks/
- http://tbm-mova.by/
- http://belazar.info/
- https://knihi.com/padrucniki.html
- http://pawet.net/
- http://lab314.brsu.by/kmp-lite/CL/Work/CL-2017/TEI/Corpus-BY.htm
- https://bnkorpus.info/ 
- https://wals.info/languoid/lect/wals_code_blr
- http://www.cs.cmu.edu/~dmortens/uriel.html
- https://nlproc.by/learn
- https://ssrlab.by/en/
