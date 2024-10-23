# Knowledge-Graph---Text-

# Objective : "Develop a knowledge graph from textual data to facilitate efficient knowledge retrieval and reasoning."

## Knowledge Graph :

A knowledge graph is a structured representation of information that connects entities and their relationships. It's essentially a semantic network where nodes represent entities (like people, places, things, or concepts) and edges represent the relationships between them (like "is_a", "has_part", "located_at").

Key characteristics of a knowledge graph:

Entities: The basic building blocks of a knowledge graph. They can be concrete objects (e.g., people, places, things) or abstract concepts (e.g., ideas, theories).
Relationships: The connections between entities. They describe how entities are related to each other (e.g., "is_a", "has_part", "located_at").
Properties: Additional information associated with entities or relationships (e.g., attributes, values).
How knowledge graphs are used:

Question Answering: Knowledge graphs can be used to answer complex questions by following the relationships between entities.
Recommendation Systems: By analyzing the relationships between entities, knowledge graphs can recommend relevant items to users.
Semantic Search: Knowledge graphs can improve search results by understanding the semantic meaning of queries and returning more relevant results.
Data Integration: Knowledge graphs can be used to integrate data from multiple sources and provide a unified view of information.
Examples of knowledge graphs:

Google Knowledge Graph: Used by Google Search to provide more informative and relevant search results.
DBpedia: A knowledge graph extracted from Wikipedia data.
Freebase: A large-scale knowledge graph developed by Google.

## Steps of Implementation : 

**1. Import necessary libraries
  2. Load the data ( As a source we considered Wikipedia page of New York
  3. Preprocess the data ( convert to lowercase and use regular expression to remove unnecessary patterns)
  4. Recognize Named Entities (Named entities are specific real-world objects or concepts mentioned in text, such as people, places, organizations, and dates.)
  5. Compute coreference clusters( Coreference clusters are groups of words or phrases that refer to the same real-world entity within a text. They are essential for understanding the underlying semantic structure of a 
  text and resolving ambiguities that may arise due to the use of pronouns, synonyms, or other forms of anaphora.For example, in the sentence "John went to the store. He bought some milk.", "John" and "he" refer to the 
  same person and form a coreference cluster.)
  6. Resolve Coreference ( Coreference resolution is essential for understanding the underlying semantic structure of a text and resolving ambiguities that may arise due to the use of pronouns, synonyms, or other forms of 
  anaphora.For example, consider the sentence "John went to the store. He bought some milk." Without coreference resolution, it might be difficult to understand that "he" refers to "John." By identifying this coreference 
  relationship, we can better understand the meaning of the sentence and the actions of the individual involved.)
  7. Extract relationship
  8. Create a Graph
  9. List the related entities**


