# CompliGen: Enterprise Policy QA Assistant

CompliGen is a Retrieval-Augmented Generation (RAG) assistant that leverages the Perplexity LLM to provide real-time answers to policy-related questions by retrieving relevant context from enterprise documents. This solo project demonstrates end-to-end pipeline orchestration, prompt engineering, and MLOps integration.

---

## Project Deliverables

- End-to-end Colab notebook  
- Embedded policy document retriever  
- Prompt engineering with MCP  
- Visualizations of evaluation metrics  
- GitHub CI/CD scaffold (manual trigger)  
- 20-minute video presentation  
- Screenshot archive and documentation  

---

## Technology Stack

| Layer              | Tools Used                       |
|--------------------|----------------------------------|
| LLM Inference      | Perplexity API                   |
| Retrieval          | LangChain + FAISS                |
| UX                 | Gradio                           |
| Notebook Execution | Google Colab                     |
| CI/CD Scaffold     | GitHub Actions (manual trigger)  |
| Visualization      | Matplotlib, Pandas               |
| Versioning         | Git, GitHub                      |

---

## Key Metrics and Evaluation

- Latency (ms): Average Perplexity API response time  
- Retrieval Accuracy: Manual check on context overlap  
- BLEU / Jaccard: Token overlap between retrieved context and output  
- User Feedback (Optional): Interface for rating answer quality  

---

## Colab Notebook

Link: [Open the Colab Notebook](<insert-colab-link>)  
The notebook includes retriever setup, prompt construction, Perplexity integration, evaluation metrics, and design rationale.

---

## Gradio Demo

Link: [Launch Gradio App](<insert-gradio-link>)  
This demo provides a simple QA interface over embedded enterprise policy documents.

---

## Screenshots

- Gradio UI: `docs/screenshots/gradio_ui.png`  
- Evaluation Chart: `docs/screenshots/eval_metrics.png`

---

## Author Contributions

This is a solo project developed by Sai Kiran Uppu, who contributed to:
- Full-stack development (retriever, prompt logic, API integration)  
- Colab notebook and end-to-end documentation  
- Gradio UX design and integration  
- Metric evaluation and visualization  
- GitHub CI/CD configuration  
- Final video presentation and project delivery  

---

## Future Work

- Replace Perplexity with open-source LLMs (e.g., LLaMA-2, Mistral)  
- Add dynamic document upload and auto-indexing  
- Implement retraining triggers using GitHub Actions  
- Deploy on HuggingFace Spaces or Vertex AI for production-grade hosting  

---
