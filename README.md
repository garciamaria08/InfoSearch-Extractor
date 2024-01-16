# InfoSearch-Extractor
A system that can search a given topic within a collection of PDFs and extract relevant information from the documents. This project involves AI and natural language processing aspects and provides practical utility by creating a tool for efficient document search and information extraction.

### Overview
Picture this: 891 e-books, a treasure trove of Data Science and Machine Learning wonders. Why? Because book lovers are on a quest for knowledge! 

### The Challenge
1. It's like finding a needle in a haystack when searching through all these gems. 
2. Each book has a wealth of information, but finding specific topics can be time-consuming.


It's time to craft a solution that transforms this exploration into an effortless search!


### Seamless Exploration
Embark on a seamless exploration of your chosen topic within a curated folder of PDFs. This AI aims to sift through the complexities, presenting you with a refined selection of documents that genuinely matter.

### Extraction with Purpose
Gone are the days of information overload. This system does not just search; it extracts meaningful information, distilling the essence of each document and focusing only on the most relevant and impactful details. 

This system is more than a tool; it's your key to unlocking the vast power of knowledge. Focusing on specific topics and information within curated PDF files brings you precisely the information you seek—focused intelligence is at your fingertips.


### Technologies and Tools Used:

- Programming Language: Python
- PDF Parsing Libraries: PyPDF2, pdfplumber
- Topic Modeling: Gensim - Latent Dirichlet Allocation (LDA)
- Search Mechanism: TF-IDF
- Named Entity Recognition: spaCy 




### Summary:
Imagine you have 891 e-books or more, each holding the secrets of Data Science and Machine Learning.
As a passionate book lover and knowledge seeker, navigating this treasure trove is a bit overwhelming.

The Challenge:
1. It's like finding a needle in a haystack when searching through all these gems.
2. Each book has a wealth of information, but finding specific topics can be time-consuming.

Introducing the Solution:
- Enter Gensim's Latent Dirichlet Allocation (LDA) model, a tool for extracting hidden topics from a collection of documents.
- But here's the twist: before unleashing the power of LDA, we combine all these e-books into a single string.

Why the Merge?
- LDA works with a "corpus," treating each piece of text as a document.
- Our definition of a "document" isn't each e-book but a continuous text block. So, we merge them into a single string.
- This helps LDA capture relationships and patterns that might span across different parts of the documents.

Path taken:
- The combined text undergoes tokenization and preprocessing, transforming into a clean, structured format.
- Think of it as preparing the ingredients before cooking, ensuring everything is in order.

Simplifying the Plot:
- Merging simplifies the initial implementation. It's a quick way to test the LDA model on the entire corpus without worrying about document boundaries.
- A pragmatic approach for experimentation, but not a one-size-fits-all solution.

Keep in Mind:
- This strategy might only suit some scenarios. If preserving the uniqueness of each document is crucial or if your documents are lengthy and contain different fields, this method might lose meaningful distinctions.
- Combining or separating documents depends on what you want to achieve.


**With the stage set, topics discovered, and information extracted, the search through the e-books becomes not just manageable but easier.**
