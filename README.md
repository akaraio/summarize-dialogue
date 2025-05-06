# summarize-dialogue

The code reads in a dataset and splits it into training, validation, and test sets, then tokenizes the data using the Hugging Face AutoTokenizer. It trains a sequence-to-sequence model on the tokenized data using the Trainer class from the Transformers library, with hyperparameters such as learning rate, batch size, and number of epochs. Finally, it saves the trained model and uses it to summarize a custom dialogue through the pipeline function from the Transformers library.
