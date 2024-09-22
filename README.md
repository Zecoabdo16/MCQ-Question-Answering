
### 🌟 Pipeline Overview for Kaggle LLM Science Exam 🚀

This repository features a comprehensive, **custom-designed pipeline** built to tackle the **Kaggle LLM Science Exam** competition, where large language models (LLMs) are used to answer challenging science questions. Here’s an overview of the key notebooks and their roles in the pipeline:

1. **📂 000_0_Data_preparation_STEM_WIKI.ipynb**
   - **Purpose**: Prepares and cleans a **custom dataset** sourced from STEM-related Wikipedia articles.
   - **Key Steps**: Data extraction, cleaning, and preprocessing to ensure high-quality input for model training.

2. **🧠 000_Data_Generation_for_Science_MCQ.ipynb**
   - **Purpose**: Generates multiple-choice questions (MCQs) from the **custom dataset**.
   - **Key Steps**: Utilizes NLP techniques to create plausible distractors and correct answers.

3. **🔬 00_Training_longformer_notebook.ipynb**
   - **Purpose**: Trains the Longformer model on the generated MCQs.
   - **Key Steps**: Custom training, evaluation, and optimization for handling long-context science questions.

4. **📈 01_Deberta_large_MCQ_training.ipynb**
   - **Purpose**: Trains the DeBERTa-large model specifically for MCQ answering.
   - **Key Steps**: Fine-tuning the model using **custom metrics** to improve accuracy and robustness.

5. **⚙️ 02_Ensemble_inference_for_best_combinations.ipynb**
   - **Purpose**: Implements **custom ensemble methods** to combine predictions from multiple models.
   - **Key Steps**: Aggregating model outputs using advanced custom techniques to maximize prediction accuracy.

6. **📊 03_Improved_Rag_8_models_submission.ipynb**
   - **Purpose**: Refines the **Retrieval-Augmented Generation (RAG)** model using **eight different configurations**.
   - **Key Steps**: Fine-tuning and optimizing RAG models for improved performance in generating and answering MCQs.

7. **🏆 04_Submission_inference_for_MCQ_RAG.ipynb**
   - **Purpose**: Final inference and **submission preparation** using the best-performing RAG model.
   - **Key Steps**: Generates final predictions, applying **custom metrics** and formatting them for competition submission.

---

This pipeline is built on a foundation of **custom datasets**, **custom metrics**, and **ensemble techniques**, ensuring a structured approach to achieving top-tier results in the competition! 🎯💡

---
