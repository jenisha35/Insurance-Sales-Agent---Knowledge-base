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

### 1. `Policies.json`
- Contains **24 mock insurance policies**.  
- Structured in strict JSON format (UTF-8).  
- Includes: policy ID, type, name, coverage, premium, riders, eligibility, exclusions.

### 2. `Insurance FAQs - English.txt`
- Contains **50 Insurance FAQs in English**.  
- Categories:  
  - 🏥 Health Insurance  
  - 💡 Life Insurance  
  - 🚗 Motor Insurance  
  - ⚖️ General Insurance Basics  
  - ➕ Riders & Add-ons  

### 3. `Insurance FAQs - Hindi.txt`
- Contains **50 Insurance FAQs in Hindi**.  
- Covers the same categories as English version.  
- Provides **multilingual support** for agents.

### 4. `Tone Switching Guide.txt`
- Defines **tone switching rules** (formal, friendly, persuasive).  
- Guides the AI agent in adapting tone to user context.  

### 5. `Compliance & Safety Rules.txt`
- Contains **compliance requirements and safety checks**.  
- Ensures legal, ethical, and safe responses.  

### 6. `Multilingual Support.txt`
- Notes and instructions for handling **multiple languages**.  
- Guidelines on mixing Hindi + English responses where needed.  

---

## 🌐 Integration with Inya AI

To connect this KB with Inya AI:  
1. Copy the **raw GitHub file URLs** (e.g. `https://raw.githubusercontent.com/yourusername/insurance-kb/main/Policies.json`).  
2. In **Inya AI → Knowledge Base → Add Source → API/Endpoint**, paste the URLs.  
3. Inya AI will fetch and sync the KB automatically.  

---

## ✅ Notes
- All files are **UTF-8 encoded** for multilingual support.  
- `Policies.json` is kept strictly valid (no comments, no trailing commas).  
- Updating any file here will automatically update the linked KB in Inya AI.  
