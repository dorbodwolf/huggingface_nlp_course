# huggingface_nlp_course
huggingface上的nlp课程的notebook

## TRANSFORMER MODELS
   
| **model**       | **examlpes**                               | **task**                                                                         |
|-----------------|--------------------------------------------|----------------------------------------------------------------------------------|
| encoder         | ALBERT, BERT, DistilBERT, ELECTRA, RoBERTa | Sentence classification, named entity recognition, extractive question answering |
| decoder         | CTRL, GPT, GPT-2, Transformer XL           | Text generation                                                                  |
| encoder-decoder | BART, T5, Marian, mBART                    | Summarization, translation, generative question answering                        |

## TOKENIZERS 
https://huggingface.co/learn/nlp-course/chapter2/4?fw=pt

| **tokenizer**       | **examlpes**                               | **tokenization method**                                                                         |
|-----------------|--------------------------------------------|----------------------------------------------------------------------------------|
| Byte-level BPE         | as used in GPT-2 | Subword tokenization |
| WordPiece         | as used in BERT           | Subword tokenization                                                                  |
| SentencePiece or Unigram | as used in several multilingual models    | Subword tokenization                        |
