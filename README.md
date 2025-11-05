# Intelligent-pest-detection-using-Vision-Transformer
“My final year project is titled ‘Intelligent Pest Detection in Agriculture using Vision Transformer’. The goal of this project is to help farmers detect diseases in paddy leaves early and accurately using a deep learning-based multi-task system.

We used a Vision Transformer (ViT) model, which is more effective than traditional CNNs in capturing global patterns across leaf images. Our model performs three tasks simultaneously:

Classifies the type of disease, Predicts the paddy variety, Estimates the age of the leaf

We trained our model on a dataset of over 10,000 images collected from Kaggle, which includes labels for disease, variety, and age. To improve performance and generalization, we applied data augmentation, label smoothing, and class balancing techniques like weighted sampling.

Our training pipeline uses AdamW optimizer, with a ReduceLROnPlateau scheduler to dynamically adjust the learning rate. The model achieved an impressive 97% validation accuracy and showed balanced precision, recall, and specificity across classes.

To make the model explainable, we integrated LIME (a model-agnostic explanation technique), and for usability, we built a Streamlit-based user interface where users can upload a leaf image and receive predictions instantly. We also integrated Twilio API to send predictions via SMS.

Overall, the project demonstrates how modern deep learning models like ViT can be used to build robust, explainable, and user-friendly tools for precision agriculture, which can help farmers make timely decisions and reduce crop loss.
