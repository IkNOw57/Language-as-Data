Code contains:
- Dutch_to_English_Corpus compiles a dataframe based on the Dutch Parallel Corpus as developed by the Instituut voor de Nederlandse Taal. 
Additionally, 78 sentence pairs created with the use of Llama 3.1 8B are added as a way to enrich the corpus.

- Generate_translations compiles translations for the Dutch Source sentences in the dataset, this way done by using CTranslate2 NLLB-200 600M model. In the same notebook BLEU score is calculated for these translations.

- Generate_Llama_Annotations complements the already existing dataframes with Quality Estimation done by Llama 3.1 8B. Both dataframes were saved as a pickle as it is a fast and compact way of saving these dataframes. 

Data contains:
- All dataframes generated through out the previous notebooks

Images contains:
- Sentence Length comparison
- Diminutives counts
- Modal particles counts

Propmts contains:
- Data Augmentation prompts
- Quality Estimation prompts