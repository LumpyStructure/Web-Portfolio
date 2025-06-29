---
title: 'AI RAG Assistant'
description: 'An AI assistant that can use documents provided by the user to answer queries'
image:
    url: '/RAG-Agent/homescreen.png'
    alt: 'Application homescreen'
worksImage1:
    url: '/RAG-Agent/chat.png'
    alt: 'Application chat screen'
worksImage2:
    url: '/RAG-Agent/github-login.png'
    alt: 'Application login screen'
platform: Web
stack: Python, Autogen, Chainlit, Docker, Chroma
website: None
github: https://github.com/LumpyStructure/SpecSearcherAI
---

I created this application during a work experience with RINA in Genoa, Italy. With the help of my colleagues, I learnt the basics of AI agents, in particular the concept of Retrieval-Augmented Generation which allows an agent to use resources such as web pages, pdfs, and other files to generate responses using the content of the files.

On the backend, it can use OpenAI, Gemini, or Ollama models to generate responses. It uses AutoGen to manage the agent, Chroma to manage the RAG memory, and Chainlit for the user interface. The user's chat history is saved and linked to their Github account, which they are prompted to sign in to on startup. The chat histories are stored in a database managed by Docker and Chainlit.