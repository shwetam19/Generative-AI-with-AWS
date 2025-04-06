# Domain Expert Model Project Overview💹

This project demonstrates how to build a domain expert generative model using AWS SageMaker by leveraging a pre-trained model (Llama2) and fine-tuning it on a domain-specific dataset.

## **Two-Phase Approach:**
  - **Model Evaluation:**  
    - Load and preprocess the pre-trained model.
    - Calculate evaluation metrics (e.g., perplexity) to measure model performance.
    - Generate sample outputs for qualitative assessment.
    - Integrate with AWS services (SageMaker) for scalable evaluation.
  
  - **Model Fine-Tuning:**  
    - Prepare a domain-specific dataset (consistent tokenization using the pre-trained tokenizer).
    - Fine-tune the model using a reduced learning rate (using optimizers like AdamW).
    - Utilize AWS GPU-accelerated instances for efficient training.
    - Regular checkpointing and validation to monitor performance and avoid overfitting.

- **Key AWS Integration:**
  - Leverages scalable compute (EC2/SageMaker) and reliable storage (S3).
  - Facilitates efficient training, model management, and eventual deployment in production.

- **Core Objectives:**
  - Adapt a pre-trained model into a domain expert through fine-tuning.
  - Ensure performance through rigorous evaluation and continuous monitoring.
  - Demonstrate an end-to-end pipeline from model evaluation to deployment using AWS infrastructure.

Check out my [Udacity certificate](https://confirm.udacity.com/e/c01fcd46-39f0-11ef-9cd2-4f3510158e32)🌟

