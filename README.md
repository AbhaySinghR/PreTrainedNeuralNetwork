Neural Network Evaluation and Analysis

This project focuses on leveraging pretrained neural networks for tasks in computer vision (CV) and natural language processing (NLP). The goal is to evaluate a pretrained model on a specific dataset, analyze its performance, and visualize its embeddings.

Steps to Follow

1. Model Selection and Description
Choose a pretrained CLIP model from Huggingface.
Download the model using a suitable environment (e.g., local machine, Colab, Kaggle).
Analyze and describe the selected model:
Model architecture (e.g., CNN, ViT).
Number of layers and parameters per layer.
Breakdown and explanation of the parameters (e.g., roles of K, Q, V matrices, biases, feature maps, dense layers).
2. Dataset Evaluation
Use the ModelvsBaby dataset: Dataset Link.
Categories: Airplane, Car, Chair, Cup, Dog, Donkey, Duck, Hat.
Image Conditions: Realistic, Geons, Silhouettes, Blurred, Features.
Process:
Feed each image into the model along with text labels for all categories.
Identify the label with the highest correlation for each image.
Determine accuracy by calculating the proportion of correct classifications for each condition.
3. Comparison with Human Performance
Compare the model's performance with human (baby) results as reported in Fig. 3A of this paper.
Highlight conditions where the model performs better, worse, or similarly.
4. Embedding Visualization
Extract embeddings from the final layer of the vision encoder (before projection into the shared embedding space).
Apply t-SNE to reduce the dimensionality of embeddings to 2D.
Create a 2D scatter plot with small images of objects placed according to their embeddings (refer to Fig. 4 in the same paper).
Deliverables

A Jupyter Notebook (.ipynb) with code and results.
A PDF version of the notebook for detailed review.
Ensure results are visible in the submitted files.
Cite all resources used (e.g., websites, books, research papers, collaborators).
Tools and Recommendations

Programming Languages: Python (or R if preferred).
Libraries: Scikit-Learn, Tensorflow, PyTorch, Huggingface.
Visualization Tools: Matplotlib, Seaborn, t-SNE.
Model Familiarization: Review details about CLIP.
