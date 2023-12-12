# CS236Project

Repo w/ code for our CS 236 Project! The main code to generate images is in the Image_Generator.ipynb file. 
Notably, however, this ipynb downloads pix2pix-zero as a new install and as such relevent files in that install must be replaced, specifically the base_pipeline.py and edit_pipeline.py in the new install of 
pix2pix-zero must be replaced with the base_pipeline.py and edit_pipeline.py files contained in this repo. These files live in pix2pix-zero/src/utils. The credit for writing the base code in those code files goes to the authors of [pix2pix-zero] (https://github.com/pix2pixzero/pix2pix-zero)
The small edits we made are marked very clearly with comments, any code not surrounded by clear comments that it was written for a CS 236 project comes from the pix2pix-zero repo and was not written by us.

The 4 .pt files contain the embeddings for the scentences using the word blonde, brunette, old, and young respectively. If one is trying to run any of these tasks, these .pt files must be placed in pix2pix-zero/assets/embeddings_sd_1.4.
