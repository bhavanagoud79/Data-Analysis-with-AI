# Slovakia IMF Financial Analysis Using LLM
 
**Country:** Slovakia (2022–2023)  
**Dataset:** IMF Country Report No. 22/202

## Project Description
This project analyses Slovakia's 2022 IMF Article IV Consultation report using a locally running Large Language Model (LLM). The system extracts financial indicators, summarises report sections, identifies economic risks and produces a financial stability dashboard.

## Models Used
- **Qwen2.5-1.5B-Instruct:** Text summarisation, financial extraction, RAG question answering and LLM-as-a-Judge evaluation.
- **all-MiniLM-L6-v2:** Generates text embeddings for semantic retrieval.
- **FAISS:** Stores embeddings and retrieves relevant report information.

## Tools and Libraries
Python, Google Colab, PyMuPDF, Transformers, Sentence-Transformers, FAISS, Pandas, Matplotlib and JSON.

## How to Run
1. Open the notebook in Google Colab.
2. Select T4 GPU as the runtime.
3. Run the cells sequentially.
4. Upload the Slovakia IMF PDF when prompted.
5. The notebook generates summaries, financial JSON files, evaluation results and a four-panel dashboard.

No API keys are required.

## Project Outputs
- Seven section summaries and an executive summary
- Six financial indicators with missing-value handling
- Seven financial themes
- Six economic strengths and six vulnerabilities
- Four economic trend series
- FAISS-based RAG responses
- LLM evaluation results
- High-resolution financial dashboard

## Data Source
International Monetary Fund (2022). *Slovak Republic: 2022 Article IV Consultation—Press Release; and Staff Report*. IMF Country Report No. 22/202.
