# Loyalty - Azure

# Deployment

### create infrastructure
```bash
cd terraform
terraform init
terraform apply
```

### setup db
```bash
cd scripts
./setup_db.sh
```

### publish functions
```bash
cd app
./publish_functions.sh
```

projekt musi być zrealizowany w oparciu o architekturę mikroserwisów (min. 3 węzły)
    1. API
    2. Kafka consummer TODO
    3. ?
komunikacja asynchroniczna w przynajmniej jednym miejscu
    Kafka TODO
wykorzystanie usług SaaS w ramach dowolnej chmury (np. Azure Cognitive Services)
    ? TODO
architektura serverless lub w oparciu o kubernetes (lub podobną technologię)
    azure functions
minimalny frontend(np. streamlit)
    static page in storage account
Infrastructure as Code (np. Terraform, ARM)
    terraform
CI/CD (np. GitHub Actions, Azure DevOps)
    github Actions -> on mr to main deploy on cloud TODO
Diagram architektury (np. draw.io)
    TODO