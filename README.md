# ChatGPT-for-Bias-Detection
Repository of the paper "Assessing ChatGPT's Ability to Detect Ethnic and Gender Bias in Italian News Articles."

## Context
Nowadays, we are witnessing a tremendous proliferation of real-time news articles on various sources. However, many times these articles are polarized, showing prejudices and discriminations towards specific individuals or social groups.

Following the advancements in generative AI, the aim of this paper is to use **Large Language Models (LLM)** to detect biases and hate speech in texts, specifically in articles coming from non-trustable sources. 

In particular, we have used ChatGPT in identifying ethnic and gender biases related to news and political articles.


## Methodology
![image info](./Assets/workflow.png)

- **Sources:** we have used as sources articles from ByoBlu and VoxNews. This data are open and public;
- **Data extraxtion phase:** article titles and bodies were extracted and incorporated into four types of prompts, both in Italian and English;
- **OpenAI:** prompts were used as inputs to the OPEN AI API, obtaining a **JSON** file that shows the presence or absence of biases within the text, highlighting the text portions where the bias is found.

## Repository Structure
In this repository you can access both **Prompts** (two in English and two in Italian) and the **Dataset** with the selected articles for the tests.