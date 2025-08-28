# DocCleaner

DocCleaner is a lightweight utility I built during my capstone project to preprocess HR and policy documents for use in RAG systems.  
It converts messy PDFs (including those with screenshots, icons, or symbols) into **clean, text-first PDFs** that are easier for downstream agents (e.g. Copilot Studio, LangChain apps) to process.  

✨ Features
- 🧹 Cleans and normalizes raw PDF text  
- 🔄 OCR fallback for scanned or image-heavy files  
- 🔣 Replaces icons/symbols with descriptive text for readability  
- 📄 Outputs simplified PDFs that integrate smoothly into RAG pipelines  

🚀 Use Case
Originally developed to support an HR assistant agent, but applicable to **any knowledge-base project** where documents are not RAG-friendly out of the box.  

📜 License
All content is under CC BY-NC 4.0 — use and adapt with attribution for non-commercial purposes.
