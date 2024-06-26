# Knowledge-Graph [Automatic Extraction and Analysis of Sustainability Report]
Extracting entities, relations and attributes from sustainability reports and present in the form of knowledge graph using Neo4j.

## Project Overview

This project involves creating an Information Extraction (IE) pipeline to transform complex textual data into an intelligible and interconnected knowledge graph. The pipeline processes an annual sustainability report issued by the Dubai Electricity and Water Authority (DEWA), extracting and visualizing the information as a knowledge graph using Neo4j.

### Key Steps in the Pipeline:
1. **Text Extraction**: Extracts text from the input PDF.
   
2. **Coreference Resolution**: Replaces words referring to the same entities to eliminate replication and confusion.
   ![image](https://github.com/Laya-Shree/Knowledge-Graph/assets/113045112/e7f7ac44-d279-437f-bd61-01ed1b381ee2)
   The below image explains the input and output of the coreference Resolution step
   ![image](https://github.com/Laya-Shree/Knowledge-Graph/assets/113045112/d62befaf-f197-4384-86c5-d9bddfd4bef0)

   
3. **Rule-Based Extraction**: Identifies entities and their relationships within the text.
   The below image displays the entities that are identified from the sentence.
   ![image](https://github.com/Laya-Shree/Knowledge-Graph/assets/113045112/03aed43f-8dbf-405f-a613-4462ad153677)

4. **Attribute Identification**: Extracts attributes associated with each identified entity.
   
5. **Lemmatization**: Reduces duplication of entities by standardizing different forms of the same word.
![image](https://github.com/Laya-Shree/Knowledge-Graph/assets/113045112/76fcdb01-abfd-48c0-97e7-f615dc27fbdb)

6. **Knowledge Graph Construction**: Stores and visualizes the extracted information as a knowledge graph using Neo4j.
   ![KnowledgeGraphOutput](https://github.com/Laya-Shree/Knowledge-Graph/assets/113045112/fb3ada27-f8cf-4ee4-b385-090bc50df7aa)

