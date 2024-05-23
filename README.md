# Q/A Bot: Submission of NLP task for PClub

# Approach
I approached the problem by thinking that every question and answer a semantically similar and thus I just need to extract sentences from the data and match it with the queries
Thus I did the following

1. Created a list of sentences found out using spacy
2. Created a list of embeddings(Vectorisation) of sentences that were found out in the last step.
3. Embed the given query
4. Output the answer that has the maximum cosine similarity
5. Additionally, I also added a threshold below which it will give False as the output

# RoadBlock
The major road block I got was the amount of sentences that the paragraphs contain was too much to process thus I had to sample a small subset of the total data to work with.

