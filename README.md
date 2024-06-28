# Implementation of Retrieval Techniques in Sentiment Analysis for Software Engineering

# Description
Nowadays, the use of text-based communication is very popular in software engineering. It involves
various stakeholders to frequently express their opinions and emotions. Hence, the recognition of the
sentiments expressed in these communications are important for the effective development, ongoing
maintenance of software systems and can provide valuable insights for project managers. Sentiment
analysis in software engineering texts presents unique challenges due to the presence of technical jargon,
code snippets, and domain-specific language. Over the years, many tools have been proposed to aid in
sentiment analysis, but accurately identifying the sentiments expressed in software engineering datasets
remains challenging.

This research aims to enhance the predictions of sentiment analysis in software engineering texts
by using retrieval-based techniques to improve the performance of Large Language Models (LLMs) in
few-shot prompting scenarios. In this work, the benchmark is the LLM performance on a gold-standard
sentiment analysis dataset based on GitHub using few-shot scenarios. Four different retrieval based
techniques have been used to assess the performance change in the LLM in few-shot scenarios. First, it
was examined by taking 1-, 3- and 5-shots from retrieval techniques that were closest to the test sentence.
Then, it was examined filtering the output of retrieval techniques according to sentiment types for 3-
and 5-shots.

The experimental findings demonstrate that using retrieval techniques in sentiment analysis for soft-
ware engineering may increase the performance of the LLM slightly. Unfortunately the discrepancy of the
benchmark and the best performing retrieval technique is very small. Therefore, no definitive conclusion
can be drawn that using retrieval techniques on few-shot LLMs increase the performance of sentiment
analysis.

# How to Install the Database
The database can be accessed and downloaded from https://doi.org/10.6084/m9.figshare.11604597

# How To Obtain the Source Code
Downloading the code directly from the github will be enough to obtain the source code. 

# The Layout of the Directory Structure
- sent_anal.ipynb: Benchmark (random few-shot given to Llama 2-Chat) and implementation of retrieval techniques
- selective_sent_anal.ipynb: Implementation of filtered retrieval techniques

# How to Run the Code
Before you run the code, you should get an access token for Llama 2-Chat from https://huggingface.co/meta-llama/Llama-2-7b-chat-hf and download the database.
Then you need to write your access token to 'access_token' in both files
