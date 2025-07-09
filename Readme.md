
**Malaria Detection using Transformer-Based Approaches**  
This project explores multiple transformer-based deep learning architectures for detecting malaria-infected cells from microscopic images. The goal is to benchmark different transformer variants for classification tasks, incorporating sequential and spatio-temporal modeling.

---

**Overview of Implemented Models**  
The notebook contains implementations of four transformer-based models:

1. **Transformer + LSTM + GRU**
   - Vision Transformer-style input patching  
   - LSTM and GRU layers for temporal dependency modeling  
   - Designed to explore sequence learning on image patches  

2. **PatchTST with Spatio-Temporal Features**
   - PatchTST (Patch Time Series Transformer) adapted for images  
   - Integrates spatial and temporal embeddings  
   - Designed for stronger locality modeling within image patches  

3. **PatchTST with Uncertainty Estimation**
   - Extends PatchTST with dropout-based uncertainty quantification  
   - Useful for medical imaging scenarios where model confidence matters  
   - Uses multiple stochastic forward passes during inference  

4. **Transformer with Spatio-Temporal Encoding**
   - A pure transformer model enhanced with spatial and temporal encoding  
   - Optimized for capturing feature dependencies across different locations and time steps  

---

**How to Run**

- Download the Jupyter Notebook:  
  `ea-malaria-transformer-based-approch-project-codes.ipynb`

- Open it in any environment that supports Jupyter Notebooks:
  - Google Colab  
  - Jupyter Notebook  
  - VS Code with Python extensions

- Run all cells sequentially. The notebook is self-contained and will guide you through:
  - Dataset loading  
  - Model training  
  - Evaluation  
  - Visualization  

---

**Acknowledgment**  
This GitHub repository has been contributed by **Vikalp Srivastava** as a part of the **Engineering Analytics project** under the guidance of **Prof. Manoj Kumar**.
