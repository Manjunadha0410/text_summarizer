### Text Summarization System (Production-Ready NLP Pipeline)

```markdown
A **production-ready NLP system** for abstractive text summarization using **Hugging Face Transformers (Pegasus model)**.  
The project follows a modular pipeline architecture for **data ingestion, transformation, model training, evaluation, and deployment**.  
It is exposed via a **FastAPI service** for easy integration with downstream applications.  

---

## 🚀 Features
- **Data Ingestion**: Automatic download and extraction of datasets  
- **Data Transformation**: Tokenization, feature preparation using Hugging Face tokenizers  
- **Model Training**: Fine-tuning Pegasus model with Hugging Face Trainer API  
- **Evaluation**: Automatic evaluation using ROUGE metrics  
- **FastAPI Inference Service**: REST API endpoints for training (`/train`) and prediction (`/predict`)  
- **Production-Ready Pipeline**: Modular and reusable pipeline components with logging & exception handling  
---

## 🛠️ Tech Stack
- **Language**: Python 3.8+  
- **Frameworks**: FastAPI, Hugging Face Transformers, Datasets  
- **ML Models**: Pegasus (Seq2Seq)  
- **Pipeline**: Custom modular ingestion → transformation → training → evaluation  

---

## 📂 Project Structure

textSummarizer/
├── src/textSummarizer/
│   ├── components/        # Data ingestion & transformation components
│   ├── pipeline/          # Training and prediction pipelines
│   ├── entity/            # Config/entity definitions
│   ├── config/            # Configuration management
│   ├── utils/             # Utility functions
│   ├── logging/           # Custom logging
│   └── constants/         # Constants
├── app.py                 # FastAPI application
├── main.py                # Training entrypoint
├── Dockerfile             
├── requirements.txt       # Dependencies

```
