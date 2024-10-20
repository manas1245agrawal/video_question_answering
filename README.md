# INTRODUCTION:

This repo contains a VQA model for GIFs which is trained on TumblrGIFs and works by combining the vector embeddings of the
frame-based GIFs and text-based questions in the latent space using cross-attention and
concatenated embeddings to gather context from the image and enable open-vocabulary answering
capabilities. The approach was derived from [Language Grounded QFormer for Efficient Vision
Language Understanding]([url](https://arxiv.org/abs/2311.07449)).


### Please refer to the following doc, explaining the specifics of our approach : [Doc]([url](https://docs.google.com/document/d/1RxgUW35KJQMzxtZ6Lz23PAbrw2bQ0urFREZJ1bNo36U/edit#heading=h.r0bqbf534ck6))


### Checkpoints : 
Checkpoint for our simplified approach - [.pth file]([url](https://drive.google.com/drive/folders/1B98OhtwihrwgGPwS3sZEcqywHfuuUbp-?usp=sharing))

### Cleaned Subset of the data used for training our models : 
You can find the files here - [Drive]([url](https://drive.google.com/drive/folders/1IxC5W9J7_zfRUnd6E8vjWj-Ge6EpOfis?usp=drive_link))


