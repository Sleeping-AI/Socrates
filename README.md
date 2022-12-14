We have created a cipher named "Socrates" that uses Large Language Models and custom human languages to create unbreakable ciphers that can be used by Military and hackers for communication

Initially, to prove our proof of concept, we have taken, a fictional language from **Game of Thrones** i.e. High Valyrian. With this language we've created our own dataset of (English-High Valyrian) language with 157 examples. For this dataset, we have used ANKI [https://www.manythings.org/anki/] referennce examples and translated them into High Valyrian. 

Followed that, we used Keras seq-seq transformer based translation module to create a custom language translator **(Colangs)**. 

**Introduction**
Large Language Models (LLMs) are widely being used for variety of tasks. From creating knowledge corupus to human similar chatbots. In our small project, we looked into the possibility of creating an unbreakable cipher that can be used by Military and Intelligence and Hackers. That can allow a secure channel of communication thorugh colangs and LLMs. Since no-third party has access to the colangs core structure, we assume it makes Socrates unbreakable. Because there's no upper limit on how difficult one colang can be, which allows extreme complexity. 

**Why LLMS?**
- Transformers and Large Language Models in general has shown the capability of writing near human level textual content that being more robust and advanced than being a plain translator. In our initial project, we have explored LLMs possibility in a smaller context through training a seq-seq model with a limited amount of examples. In our iniial test run, we were quite successful and have deployed an interference on Huggingface. 

**Limitations**
At the moment, we have limitations to Socrates. It was trained on a very small dataset and examples. That's why, it can't meaningfully translate everything to High Valyrian. Though it can still translate by nature of transformers characterstics of understanding patterns from a parallel corpus but not really that accurate. But, if you use any example from the dataset, it tends to be really really accurate. 

**Code Policy**
The model and training code were taken from **Keras NLP** since it was proof of concpet. But, we made some changes to the code as we had to add an interference that can be accessible via gradio. **Keras NLP** similar to other NLP libraries are a wide spread pain, haha! That's why, we are looking forward to publish another bundle of notebooks that will contain the code implementation in a more human sense and easily deployable. Meanwhile, we're working on having a 24/7 public interference with Socrates available within few days on our Huggingface Hub for **Sleeping AI** [https://huggingface.co/sleepin4ai]

**Upcoming work**
At the moment, with this proof-of-concept we established large language models have the viabiity of acting as ciphers. Currently, we are better understanding the linguistics behind creating a robust Colang, ethical impilcations and tackling them. We have plans to get feedback from Professor Noam Chomsky and have a publication next year.
<ul>
       <li>arXiv paper</li>
       <li>More technically creative</li>
       <li>Roberta and Large Models being used</li>
       <li>a Custom Colang</li>
       <li>More more more</li>
</ul>

**Note:** This code is taken from Keras as they have awesome documentation, haha! There wasn't much reason to write custom code for the proof-of-concept. The dataset is our original work but we have made it open source. 

### Disclaimer: The idea behind Socrates is original to GitHub: @sleepingcat4. He and his team reserves all the rights to publish papers and conduct further research. Anything else will be a violation of copyright law. 

**Contributors:**
1. TAWSIF AHMED, (Main Author) **Discord:** sleeping_cat4#8182
2. Harsh, (Co-author/programmer) **Discord:** harsh1729#5323
3. Kaapo Kontinen (Co-author/Linguist) **Discord:** kvk#9152
