# Annotated dataset with documents from the Prado database

<https://www.consilium.europa.eu/prado/en/search-by-document-country.html>

## Format
This dataset is prepared to be used within the Huggingface ecosystem. The file layout and annotations conform to the <https://huggingface.co/docs/datasets/image_load#imagefolder> specification.  There is one metadata_extract.jsonl for extraction, and one metadata_classfiction.jsonl for classification. Copy the one you want to train for (i.e. if you are training a classification or an extraction model) to metadata.jsonl in all three subdirs (train, test, validation). 
