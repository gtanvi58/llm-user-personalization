# llm-user-personalization
This project focuses on user Personalized Tweets Paraphrasing and Personalised Product Rating (more info can be found - https://lamp-benchmark.github.io/) in LLMs using the data from similar users.

Data from similar users is retrieved using the Contriever retrieval model - https://github.com/facebookresearch/contriever. 
This data is then summarised and used as an input prompt into our fine tuned Flan-T5-base model - https://huggingface.co/google/flan-t5-base which is fine tuned on the data from https://lamp-benchmark.github.io/


