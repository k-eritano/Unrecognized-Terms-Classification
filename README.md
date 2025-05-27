# Unrecognized-Terms-Classification
This codebase was developed in support of research by Emily Zou aimed at analyzing the evolving language environment on 4chan.

## Tools & Downloads
For this notebook I used `Ollama`, an open-source app that allows users to run, create, and share large language models (LLMs) locally, on a local machine. The specific language model used is gemma3. An alternative to gemma3 if local disk space is a concern is gemma3:1b, though it should be noted that the reliability of gemma3:1b is more variable. Because the terms analyzed in this project are situationally specific, meaning there is not a qualitative schema that can be derived to classify these terms, the notebook integrates `Tavily` in order to harness internet searching capabilities to assess term meaning and whether terms are 4chan specific. 
