# Ask This Book: Kafka’s *The Metamorphosis*

This personal project was developed to explore Retrieval-Augmented Generation (RAG) pipelines using LangChain.  
The goal was to build a lightweight, fully offline system that can answer user questions about the book *The Metamorphosis* by Franz Kafka, without relying on external APIs.

---

## Technologies Used

- Python (Google Colab)
- LangChain
- Hugging Face Transformers
- FAISS
- sentence-transformers
- FLAN-T5 (`flan-t5-large`)

---

## Data

The book used in this demo is *The Metamorphosis* by Franz Kafka, sourced from Project Gutenberg and saved in plain `.txt` format.  
Only this local text is used for embedding and retrieval — no online querying or fine-tuning.

---

## How It Works

The notebook:
- Loads and splits the book into overlapping chunks
- Embeds the chunks using `MiniLM`
- Stores the embeddings in a local FAISS index
- Uses a lightweight model (`flan-t5-large`) to answer questions based on retrieved chunks

An interactive loop lets users query the book in a chatbot-like fashion.

---

## How to Adapt to Other Books

1. Replace the `.txt` file with another book (public domain recommended).
2. Update the file path in Step 2 of the notebook.
3. Re-run the notebook from the top.

---

## Asking Questions Effectively

Because the model is small and runs locally, short fact-based questions work best.

**Recommended:**
- What happens to Gregor Samsa?
- What job did Gregor have?
- What food does Gregor like after the transformation?

**Not recommended:**
- Why did he transform?
- What is the symbolic meaning of his transformation?
- List five things Gregor did

Avoid interpretive or compound queries. The model can only process retrieved snippets, not the full book at once.

---

## Limitations

- Performance depends on chunk quality and retrieval
- Symbolic or abstract interpretation is out of scope
- Model is limited to ~512 tokens per generation

---

## Author

**Silvia Garavaglia**  
[GitHub](https://github.com/silviagara) • [LinkedIn](https://www.linkedin.com/in/silviagaravaglia/)