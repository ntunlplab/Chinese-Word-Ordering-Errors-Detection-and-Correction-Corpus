# Chinese-Word-Ordering-Errors-Detection-and-Correction-Corpus


# 1. Dataset content
This dataset is composed of 3 text files.

- sent-original.txt
- sent-annotator1.txt
- sent-annotator2.txt

Each text file contains 1,150 simplified Chinese sentences.

### Download
Please go to [resources page](http://nlg.csie.ntu.edu.tw/nlpresource/woe_corpus/) to access resources.

# 2. Data source
In this dataset, sentences are retrieved from HSK dynamic composition corpus (HSK 動態作文語料庫), which is built by Beijing Language and Culture University. This corpus contains the Chinese composition articles in HSK examination written by non-native Chinese learners.

# 3. Pre-processing
There are total 8,515 sentences annotated with "word ordering errors" in HSK corpus. Duplicate sentences and special format sentences are removed. Word ordering errors are corrected. The tags provided by HSK such as "{CJX}" are also removed from all the sentences. There are 1,150 unique sentences without any tags in sent-original.txt.

# 4. Annotations
Two Chinese native researchers annotate correction for each original sentence without the hints of error tags provided by HSK. While all word ordering errors are corrected in the pre-processes, no any words are inserted, removed or substituted during the annotating process. Corrections are annotated with exactly the same words within original sentences with correct word ordering. Annotated corrections are kept in sent-annotator1.txt and sent-annotator2.txt respectively.

# 5. Data format
In sent-original.txt, each line contains one original sentence written by non-native Chinese learners. The annotated corrections to each original sentence are listed in the corresponding line in sent-annotator1.txt and sent-annotator2.txt.

# 6. Dataset language
All text is in simplified Chinese as HSK provided.

# 7. Character Encoding
All text is encoded to UTF8.

# 8. How to Cite the Corpus
Please cite the following paper when referring to the Word Ordering Error Detection and Correction Corpus in academic publications and papers.

Shuk-Man Cheng, Chi-Hsin Yu and Hsin-Hsi Chen (2014). “Chinese Word Ordering Errors Detection and Correction for Non-Native Chinese Language Learners.” Proceedings of the 25th International Conference on Computational Linguistics (COLING 2014), 23-29 August 2014, Dublin, Ireland.
