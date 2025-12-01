# mlops-portfolio
Portfolio of end-to-end MLOps and Generative AI projects on AWS.
mlops-portfolio/
│
├── README.md
│
├── 01-data-engineering/
│   ├── README.md
│   ├── aws-glue-etl/
│   │   ├── scripts/
│   │   ├── job-config/
│   │   └── README.md
│   ├── airflow-pipelines/
│   │   ├── dags/
│   │   ├── plugins/
│   │   └── README.md
│   └── data-quality-great-expectations/
│       ├── expectations/
│       ├── checkpoints/
│       └── README.md
│
├── 02-feature-store/
│   ├── aws-feature-store-sagemaker/
│   │   ├── ingestion/
│   │   ├── transformation/
│   │   ├── serving/
│   │   └── README.md
│
├── 03-model-development/
│   ├── classical-ml/
│   ├── deep-learning/
│   ├── notebooks/
│   └── README.md
│
├── 04-model-training/
│   ├── sagemaker-training-jobs/
│   │   ├── train.py
│   │   ├── inference.py
│   │   ├── requirements.txt
│   │   └── README.md
│   ├── distributed-training/
│   └── hyperparameter-tuning/
│
├── 05-mlops/
│   ├── cicd-github-actions/
│   │   ├── train-model.yml
│   │   ├── test-model.yml
│   │   └── deploy.yml
│   ├── sagemaker-pipelines/
│   │   ├── pipeline.py
│   │   ├── pipeline-definition.json
│   │   └── README.md
│   ├── model-registry/
│   └── monitoring/
│
├── 06-genai/
│   ├── LLM-finetuning/
│   │   ├── sagemaker/
│   │   ├── train_llm.py
│   │   └── README.md
│   ├── RAG-pipelines/
│   │   ├── vector-store/
│   │   ├── data-prep/
│   │   ├── retrieval/
│   │   └── README.md
│   ├── bedrock-applications/
│   │   ├── agent/
│   │   ├── prompt-engineering/
│   │   └── README.md
│
├── 07-aws-infra/
│   ├── terraform/
│   │   ├── s3/
│   │   ├── iam/
│   │   ├── eks/
│   │   ├── sagemaker/
│   │   └── README.md
│   ├── cloudformation/
│   └── CDK/
│
├── 08-end-to-end-projects/
│   ├── churn-prediction-mlops/
│   ├── genai-chatbot-bedrock/
│   ├── time-series-forecasting-aws/
│   └── README.md
│
└── assets/
    ├── architecture-diagrams/
    ├── screenshots/
    └── datasets/ (ignored in .gitignore)
