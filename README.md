# CAFA_6_protein_function_kaggle
Repository for CAFA 6 protein function prediction work as part of Stanford CS224W
dataprocessing_model_training_final.ipynb - Main model training code includes DNN, DNN + GraphSAGE and DNN + GAT
eda-cafa-6.ipynb - EDA for the dataset


https://drive.google.com/file/d/1vk8rbwItMlbIZ-onI-wwP4X1flDI17eA/view?usp=sharing download fasta embeddings here

Two code screenshots that are missing in the medium post (we are not sure what went wrong but they were in the original draft, 

Graph sage towers code (forward and message):
<img width="1505" height="406" alt="image" src="https://github.com/user-attachments/assets/1a13f0f8-8b9d-4613-91e5-7a324d436df3" />
GAT towers code (forward and message):
<img width="1742" height="632" alt="image" src="https://github.com/user-attachments/assets/b52a0775-b0c2-4665-8fcc-00525e13b31a" />
GNN stack was modified, self loops are added.  These architectures are used in the Multi-Tower architecture.

