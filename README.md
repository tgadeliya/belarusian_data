# Data for Belarusian language 
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
|[Canine_s](https://arxiv.org/abs/2204.07580]| LM |Tokenization-free encoder | |
|[mBERT for passage reranking](https://huggingface.co/amberoad/bert-multilingual-passage-reranking-msmarco) | | | 
|[RemBERT](https://arxiv.org/abs/2010.12821) | | | |
|[byT5](https://arxiv.org/abs/2105.13626)|Byte-to-Text | | mC4|
|[XLM](https://arxiv.org/abs/1901.07291) | | | multiple sources |
|[LaBSE](https://arxiv.org/abs/2007.01852)||||

Datasets
-----
| Name  | Description |
|---|---|
|  [Universal Dependencies for Belarus](https://github.com/UniversalDependencies/UD_Belarusian-HSE) |  |



Corpuses 
----- 
| Source  | Description | Statistics  |
|---|---|---|
|  CC-100 | Common crawl |   |
| [CCNet](https://arxiv.org/abs/1911.00359)  | Improved pipeline to extract monolingual datasets from Web Crawl | be 176.037 × 103 9.719 × 106 124.716 × 106 476.612 × 106   |
| [TED](https://github.com/ajinkyakulkarni14/TED-Multilingual-Parallel-Corpus) |   |   |
|[mC4](https://huggingface.co/datasets/mc4)| |
|[mGENRE](https://arxiv.org/abs/2103.12528)|||


Unprocessed links and resources
----- 
- Tatoeba
- https://opus.nlpl.eu/
- [NLLB data](https://github.com/facebookresearch/fairseq/blob/nllb/examples/nllb/data/README.md)
- [M2M sources list](https://arxiv.org/pdf/2010.11125.pdf)
- https://fasttext.cc/
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
- https://oscar-corpus.com/
- https://bnkorpus.info/ 
- https://wals.info/languoid/lect/wals_code_blr
- http://www.cs.cmu.edu/~dmortens/uriel.html
- https://nlproc.by/learn
- https://ssrlab.by/en/
- http://sigslav.cs.helsinki.fi/resources.html
- https://wortschatz.uni-leipzig.de/en/download/belarusian
- https://huggingface.co/datasets?filter=languages:be
- https://www.opensubtitles.org/en/search/subs
