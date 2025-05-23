# Telugu to English Transliteration (Dakshina Dataset)

This project uses a sequence-to-sequence models(RNN, LSTM, GRU) to transliterate words from Telugu to English trained on Dakshina Dataset.

Link to dataset: https://github.com/google-research-datasets/dakshina
(Telugu dataset can be found in folder dakshina_dataset_v1.0/te/lexicons/)

Running: Run da6401-assignment3-final.ipynb notebook cells sequentially till end to get the wandb outputs. 

Code is flexible to dimension of the input character embeddings, the hidden states of the encoders and decoders, the cell (RNN, LSTM, GRU) and the number of layers in the encoder and decoder. These can be changed in sweep configuration cell as per your needs.

Wandb configs, dataset paths require updates in cells and are marked in notebook clearly at respective cells.