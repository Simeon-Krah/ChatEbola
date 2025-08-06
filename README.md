### ChatEbola

ChatEbola aims to be a go-to resource for answers about Ebola-related queries — something that’s still very relevant in communities with limited access to healthcare professionals and facilities.

### Project Goal

The aim was simple but meaningful: **create an intelligent assistant that delivers timely, accurate, and trusted responses to questions about Ebola**. Misinformation during disease outbreaks can be just as dangerous as the disease itself, and I wanted to address that through AI.

### From Fine-Tuning to RAG

At first, I fine-tuned Google’s Gemini model on a custom Ebola dataset. However, the lack of structured/tabular data meant that fine-tuning alone wasn’t cutting it. 

That led me to **Retrieval-Augmented Generation (RAG)**. I built a RAG-based chatbot using **Python** and the **LangChain** framework. The beauty of this approach is that it doesn’t rely solely on what the model “remembers”; it actively retrieves relevant, up-to-date information from trusted documents.

### Tech Stack

- **Language:** Python  
- **Framework:** [LangChain](https://www.langchain.com/)  
- **Model:** Google Gemini (initially fine-tuned)  
- **Retrieval:** RAG (document-based querying)  
- **Evaluation:** [RAGAS](https://github.com/explodinggradients/ragas)  
