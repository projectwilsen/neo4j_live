# Enhancing Text2Cypher with In-Context Learning and Fine-Tuning

Welcome to the resources for the Neo4j live session titled **"Enhancing Text2Cypher with In-Context Learning and Fine-Tuning."**

You can watch the live session recording here:

[![Neo4j Live](https://img.youtube.com/vi/a16xUTmb1BU/0.jpg)](https://www.youtube.com/live/a16xUTmb1BU?si=Zg8OvQfsFoZhgCdl)


## Introduction

Text2Cypher generation is a crucial step in unlocking the full potential of graph databases. By bridging the gap between natural language and Cypher queries, we're making it easier to retrieve complex, interconnected data with precision. This session will guide you through the process of enhancing Text2Cypher models using in-context learning and fine-tuning techniques, enabling more accurate and efficient data retrieval.

## Materials

- **PPT Presentation:** [Enhancing Text2Cypher Presentation](https://www.canva.com/design/DAGJUA8xX5E/xbujyvP1q7GpvEhD6fkxeg/edit?utm_content=DAGJUA8xX5E&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
- **Colab Notebook:** [Text2Cypher Fine-Tuning Colab](https://colab.research.google.com/drive/1qAwsHGObbde_cTp6JHZ-dKGnNYcO0DmA?usp=sharing)

## Dataset

The following datasets are provided to support the session:

1. **`dataset.csv`**  
   A preprocessed dataset originally sourced from Kaggle. Special thanks to Manish Kumar for the [LinkedIn User Profiles dataset](https://www.kaggle.com/datasets/manishkumar7432698/linkedinuserprofiles?select=LinkedIn+people+profiles+datasets.csv).

2. **`text2cypher_questions.csv`**  
   Generated questions using Nemotron, based on the graph schema.

3. **`raw_text2cypher.csv`**  
   Generated Cypher query language based on the graph schema, providing answers to each query from the previous step.

4. **`detailed_text2cypher.csv`**  
   A table with additional columns (`syntax_error`, `timeout`, `returns_results`) used to verify the correctness of the generated Cypher queries.

5. **`final_text2cypher.csv`**  
   The final dataset used for fine-tuning. This dataset includes the following columns: `question`, `type`, `cypher`, `syntax_error`, `timeout`, `returns_results`.

Last but not least, if you want to use your fine-tuned model locally, you could also push it to Ollama. Make sure to save the quantized version, then follow the instructions in the `command.txt` file.