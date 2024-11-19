# 👨🏻‍💻🤔 Why Federated Learning

This lesson will cover
- How FL is key to unlocking large amounts of data that is currently inaccessible for training.
- Limitations of the traditional training methods.
- FL is used to train models on data that is distributed across different organizations or millions of user devices.

### 📂 On the importance of Training Data


>  To train the best language model, the curation of <b>a large, high-quality training dataset is paramount</b>. In line with our
>  design principles, <b>we invested heavily in pretraining data.</b>
>
>  Llama 3  is pretrained over 15T tokens that were all collected from publicly available sources.
>
>  Our training data is <b>seven times larger</b> than that used for Llama 2, and it includes <b>four times more code.</b>
> 
>  <b>Source: https://ai.meta.com/blog/meta-llama-3/</b>

Training data should be high volume and high quality for training efficient foundational models like LLMs.

### 😪🏃🏻‍♂️ Are LLMs running out of training data?

But are LLMs running out of training data? There's a debate going on the availability of quality training data for LLMs. In this post by [Educating Silicon](https://www.educatingsilicon.com/2024/05/09/how-much-llm-training-data-is-there-in-the-limit/):

>  At 15 trillion tokens, <b>current LLM training sets seem within an order of magnitude of using all high-quality public text.</b>
>
>  For English, you could maybe get to somewhere in the 40 – 90T range using more web crawl and some harder to reach sources.
>
>  Including non-English data might possibly get you to the 100 – 200T range. <b>That seems like the upper limit.</b>

**Part of the table from the blog:**

<p align = "center">
<img src = "https://github.com/user-attachments/assets/9b01c22d-3fa9-4cbd-9fff-f33892020e7e" alt = "Limits to training data for LLMs"/>
</p>

### 🤔🤔 What do LLMs think about LLMs running out of training data?

<p align = "center">
<img src = "https://github.com/user-attachments/assets/cc721565-39f8-4cc0-855d-3489ca24ca13" alt = "LLMs view on running out of training data"/>
</p>

Even LLMs think, LLMs are running out of training data....

### 📢🌟 Public Data vs 🔐🤫Private Data

There are around 15T tokens in FineWeb and 18T tokens in Non-English data, there is an estimated 650T tokens in privately stored instant messages alone, and 1200T tokens in all stored Emails.


<p align = "center">
<img src = "https://github.com/user-attachments/assets/0a52c40c-e799-4449-a903-f19dfe840986" alt = "Plot showing tokens in different modes of data"/>
</p>


The public data might be running out but there is a huge corpus of untouched private data still available. 

### 🌐📊 Data is naturally distributed 

Data is naturally distributed across organizations and user devices.

> <pre> <b>Across organizations</b>                                                                       <b>Across devices</b>
>
> - Healthcare 🏥                                                                           - Phones 📲📱
>   (different hospitals)                                                                     (smart phones) 
> - Government 🏛️                                                                           - Laptops 💻 👨🏻‍💻
>   (different agencies)
> - Finance 🏦💵                                                                            - Automotive 🚗🚘
>   (regulatory regions)                                                                       (vehicles)
> - Manufacturing 👷🏻⚒️                                                                      - Home robotics 🏠🤖
>   (different factories)     
> </pre>


### 1️⃣🟠 Traditional training assumes centralized data

Uses only one dataset for training, and ignores other sets of data. Most of  the world's data is not readily available for model training. 


### 📂🚫 Collecting more data often doesnot work

<pre>
- Data needs to move                                                                        - Sensitive data
- Often not possible                                                                        - Data Volume
- Many reasons                                                                              - Privacy
                                                                                            - Regulations
                                                                                            - Practicality
</pre>

- Since most of the data is not readily available, one way is to go around and collect more data.
- But in many cases collecting data simply doesnot work.
- Data needs to move, but it's not possible for many reasons.
- Data might be sensitive (like healthcare data has PII).
- Volume of the data might be too high.
- User privacy might restrict one to collect more data.
- Regulations might force data to stay in a certain region, locked up in silos.
- Sometimes it's just not practical to collect more data.

**Summary:** We cannot collect data all at one place for many usecases due to various reasons ranging from privacy, regulations and practicality.

And what would happen if we don't have enough data? Or say missing data? Or maybe unevenly distributed data?


### 🧑🏻‍💻⚒️ Let's Build and get our hands dirty 




### Further Readings
