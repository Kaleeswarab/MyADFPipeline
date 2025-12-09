# MyADFPipeline

A Git-backed Azure Data Factory (ADF) project — containing pipelines, linked services, datasets, and triggers — designed to define, version-control, and deploy ADF artifacts in a structured and maintainable way.

---

## 📁 What’s in this repo

- `factory/` — configuration defining the ADF factory (if applicable)  
- `linkedService/` — linked service definitions (e.g. connections to storage, databases, etc.)  
- `dataset/` — dataset definitions (input / output datasets for your pipelines)  
- `pipeline/` — pipeline definitions (JSON) for data workflows / orchestrations  
- `trigger/` — trigger definitions (schedules, event-based triggers) for running pipelines automatically  
- `publish_config.json` — (optional) configuration for publishing/deployment  
- This `README.md` — project documentation  

---

## 🎯 Purpose & Use Cases

This repo is useful if you want to:

- Maintain version-control for your ADF pipelines and related artifacts (linked services, datasets, triggers).  
- Use GitHub (or other Git hosts) to collaborate on ADF development: track changes, peer review, rollback, etc. :contentReference[oaicite:1]{index=1}  
- Deploy ADF artifacts reproducibly: enabling a CI/CD workf
