# LLM-Powered-Document-Analysis-and-Generation

# Objective 
Developed a comprehensive system utilizing Large Language Models (LLMs) for document clustering, similarity search, and question answering.

# Technologies Used 
Python, PyTorch, Transformers (gpt2, T5), K-Means clustering, PCA for dimensionality reduction.


# Document Clustering System:

Implementation: Successfully developed a document clustering system by leveraging Large Language Model (LLM) embeddings and the K-Means algorithm. This approach enhanced document organization efficiency by grouping similar documents based on their semantic content.

Technical Details: Utilized Hugging Face embeddings to represent documents as vectors, which were then clustered using K-Means. This method allowed for the identification of underlying topics within the document collection.


# Retrieval QA Chain:

Implementation: Created a retrieval QA chain using the gpt2 model to provide accurate answers based on relevant documents. This involved integrating a vector store with the LLM to fetch and process relevant documents.

Technical Details: Employed a vector store to store document embeddings, enabling efficient similarity searches. The gpt2 model was used to generate answers based on the retrieved documents.


# Paraphrasing Tool:

Implementation: Developed a paraphrasing tool using a T5 model to generate diverse paraphrases of input sentences. This tool utilized text-to-text transfer learning to produce paraphrases that convey the same meaning as the original text.

Technical Details: The T5 model was pre-trained on a large dataset and fine-tuned for paraphrasing tasks. The tool allowed for customizable output, enabling users to generate multiple paraphrased versions of a sentence.



