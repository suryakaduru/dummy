📌 How It Works
1️⃣ User Input: The user asks a question.
2️⃣ Website Scraping: The chatbot extracts text from a given website.
3️⃣ Embedding Generation: The text is converted into numerical representations using Sentence Transformers.
4️⃣ FAISS Indexing & Retrieval: The most relevant information is retrieved from the website’s content.
5️⃣ Context Injection: The retrieved content is inserted into the prompt.
6️⃣ LLM Response Generation: Mistral-7B processes the question + retrieved content to generate an accurate response.
7️⃣ User Interaction: The chatbot remembers conversation history for better follow-up questions.
