![image](https://github.com/user-attachments/assets/235ddc4c-4c1b-4d5e-a5ff-f174b306044b)

Also, I added variable semantic compression with variable chunk sizes, and a variable consideration of the document's description (second line). For example, {context,2,7,5} will semantically compress the document to approximately 30% of its original length with sentence-sized chunks, weighting similarity to the description equally to similarity to the entire document body.
