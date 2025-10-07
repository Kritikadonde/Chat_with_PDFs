*Overview*
------------

The MultiPDF Chat App is an interactive Python web application powered by LangChain that lets you converse with multiple PDF files at once. Instead of manually searching through long reports, case studies, or textbooks, you can simply ask questions in plain English — and the app will retrieve relevant information directly from your documents.

*How It Works*
------------
![F657D32A-9E55-42B5-9029-783AC92E5720](https://github.com/user-attachments/assets/be06e763-7791-455b-b122-c25562d854cf)


The app processes your questions through the following workflow:

1.⁠ ⁠PDF Ingestion: Multiple PDF files are uploaded, and their textual content is extracted.

2.⁠ ⁠Segmentation: The extracted text is split into smaller, manageable sections for easier handling.

3.⁠ ⁠Embedding Creation: A language model converts these text sections into vector embeddings that capture their meaning.

4.⁠ ⁠Relevance Search: When you ask a question, it is also converted into an embedding and compared against the stored text sections to find the closest matches.

5.⁠ ⁠Answer Construction: The most relevant sections are fed back into the language model, which generates an answer tailored to the information contained in your PDFs.  

*Application Preview* 
------------
Here’s how the MultiPDF Chat App looks when running:

<img width="1463" height="821" alt="Screenshot 2025-09-02 at 8 31 32 AM" src="https://github.com/user-attachments/assets/b74919e2-5efa-47c6-bf0c-73db559829be" />



