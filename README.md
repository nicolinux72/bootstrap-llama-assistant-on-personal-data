# Bootstrap a LLaMa assistant on personal data
How to expand an LLM's ability to also answer questions about confidential data such as company knowledge.


![Kindly created by stable diffusion XL](LLaMa.png)

In this second article (the first here), still aimed at beginners, we will enrich our AI chatbot with personal documents, such as PDFs on our laptop, so that it can respond even to topics for which it has not been pretrained like business knowledge. The procedure works like this: along with the user's request, we pass additional information to the LLM context so that it can use it to respond; information that will be ingested from personal documents, persisted to a vector database and retrieved based on an algebraic criterion of proximity with the user prompt.

Al that will be easier to do than to explain. 😊

We will insist on using a local running LLM (Large Language Model), that is without any calls to external APIs or licensing fees.

We will get familiar with LangChain, a well-maintained library that implements an abstraction on some functionalities common to all Natural Language Processing (NLP) applications such as, for example, using an LLM through different runtimes or enriching its knowledge base through spreadsheets, word processor documents or databases.

Please, read the full article on [medium.com](https://medium.com/@nicolasanti_43152/bootstrap-a-llama-assistant-on-personal-data-2-2-16062fa5aa6d)
