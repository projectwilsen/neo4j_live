Materials:
- PPT: https://www.canva.com/design/DAGJUA8xX5E/xbujyvP1q7GpvEhD6fkxeg/edit?utm_content=DAGJUA8xX5E&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
- Colab notebook: https://colab.research.google.com/drive/1GjQnRo1uci0KEaJZc-0uEsX8rpGVTQlg?usp=sharing

Dataset:
- dataset.csv: prepro dataset that originally sourced from Kaggle (https://www.kaggle.com/datasets/manishkumar7432698/linkedinuserprofiles?select=LinkedIn+people+profiles+datasets.csv), thanks to Manish Kumar
- text2cypher_questions.csv: generated question using Nemotron based on the graph schema
- raw_text2cypher.csv: generated cypher query language based on the graph schema answering each query from previous step
- text2cypher_questions.csv: a final table with additional 3 columns (syntax_error,	timeout, returns_results) used to filter out correct cypher query generated from the LLM
