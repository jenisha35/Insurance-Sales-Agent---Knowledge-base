# 📘 Insurance Sales Agent Knowledge Base

This repository contains the **Knowledge Base (KB)** for the Insurance Sales Agent project.  
It includes policy details, FAQs, tone switching rules, and compliance guidelines.  
Designed for integration with **Inya AI**.

---
## 📂 Repository Structure

insurance-kb/

│

├── Policies.json                 # Mock policy catalog (structured data in JSON)

├── Insurance FAQs - English.txt  # FAQs in English

├── Insurance FAQs - Hindi.txt    # FAQs in Hindi

├── Tone Switching Guide.txt      # Tone switching rules for agent

├── Compliance & Safety Rules.txt # Compliance requirements and safety checks

├── Multilingual Support.txt      # Notes for handling multiple languages

└── README.md                     # This file



## 📑 Contents

### 1. `policies.json`
- Contains **24 mock insurance policies**.  
- Structured in strict JSON format (UTF-8).  
- Includes: policy ID, type, name, coverage, premium, riders, eligibility, exclusions.

### 2. `faqs.md`
- Contains **50 Insurance FAQs**.  
- Categories:  
  - 🏥 Health Insurance  
  - 💡 Life Insurance  
  - 🚗 Motor Insurance  
  - ⚖️ General Insurance Basics  
  - ➕ Riders & Add-ons  
- Includes **Hindi translations** for multilingual support.

### 3. `rules.txt`
- Defines **tone switching** (formal, friendly, persuasive).  
- Contains **compliance & safety rules** for the agent.  

---

## 🌐 Integration with Inya AI

To connect this KB with Inya AI:  
1. Copy the **raw GitHub file URLs** (e.g. `https://raw.githubusercontent.com/yourusername/insurance-kb/main/faqs.md`).  
2. In **Inya AI → Knowledge Base → Add Source → API/Endpoint**, paste the URLs.  
3. Inya AI will fetch and sync the KB automatically.  

---

## ✅ Notes
- All files are **UTF-8 encoded** for multilingual support.  
- `policies.json` is kept strictly valid (no comments, no trailing commas).  
- Updating any file here will automatically update the linked KB in Inya AI.  

---
