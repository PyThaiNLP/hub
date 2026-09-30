# Hub

New hub of corpus and models for PyThaiNLP and other projects

Since Nvidia has acquired Hugging Face, We think the corpus and models should not use huggingface-hub libery because it can case vendor Lock-In problems and some ToS can change in the future.

We was use [https://github.com/PyThaiNLP/pythainlp-corpus](https://github.com/PyThaiNLP/pythainlp-corpus) for downloading files in pythainlp to use there corpus and models that can not attachment to pypi. It can chnage URL for downloading file but it support just one file and one file per name, so I think we should replaced with the new hunb for PyThaiNLP v6.0+.
