an AI-based document interpreter that allows users to upload PDF files and ask questions about their content. It uses natural language processing (NLP) to extract and interpret text from the PDFs, generating relevant responses to user queries.
The idea came in my mind while I was preparing for my semester exams and had to go through multiple PDFs, each over 50 pages long. I wanted a tool to help summarise the content and answer specific queries efficiently.
Since I couldn’t find a suitable free tool and ChatGPT’s feature was paid, I decided to build my own solution. 
I worked in a team of two. My role was primarily focused on the backend, specifically implementing the text extraction, performing embeddings and similarity search on the data.
I have used the pypdf2 library for extracting data , for embeddings I have used OpenAI API for converting text into vector space, and FAISS for similarity search on the document text.
this project aligns with the Retrieval-Augmented Generation (RAG) framework
This project has been a great learning experience and has equipped me with skills in AI, data processing, and search algorithms.
