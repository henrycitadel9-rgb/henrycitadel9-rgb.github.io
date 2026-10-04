---
title: "Project 2: Building a High-Accuracy Ga ASR System Using the Transformer-Based Whisper Architecture"
excerpt: "Developed and deployed an automatic speech recognition system for Ga, a low-resource Ghanaian language, by fine-tuning Whisper on approximately 90,000 audio-text pairs.<br/><br/><strong>Explore the project →</strong> See what inspired me to work on this project, the project summary and results, a demo of the system, and additional project details."
collection: portfolio
---

## Inspiration

During my third year at the University of Ghana, I became increasingly interested in Human-Computer Interaction and wanted an opportunity to gain research experience in the field. I approached **Prof. Isaac Wiafe** and expressed my interest in working on a project under his supervision in the Human-Computer Interaction Lab. Following our conversation, he challenged me to work on automatic speech recognition for **Ga, a low-resource Ghanaian language**. This became an opportunity for me to apply the computing and machine learning skills I had been developing independently to a real research problem.

See the **Project Summary and Demo** below for details of the system I developed and its performance.

## Project Summary

Automatic speech recognition (ASR) technologies allow computers to convert spoken language into text, but their capabilities are not equally available across languages. Many Ghanaian languages remain underrepresented in speech technologies, limiting the ability of speakers to interact with digital systems using their local languages. Ga, the indigenous language of Ghana's capital, Accra, is one such low-resource language. Developing speech-recognition capabilities for Ga can therefore contribute to more inclusive human-computer interaction while expanding the language's representation in digital technologies.

In this project, I developed a **Ga automatic speech recognition system using the transformer-based Whisper architecture**. I prepared and cleaned approximately **90,000 Ga audio-text pairs**, normalized the data, assessed audio and transcript quality, and divided the dataset into training, development, and test sets. I then fine-tuned a multilingual Whisper model to transcribe spoken Ga into text.

The resulting model achieved a **word error rate (WER) of approximately 24–25% and a character error rate (CER) of approximately 11–12%**. Evaluation across different subsets of the data produced similar performance, including on previously unseen samples. I also developed a working web-based prototype that allows users to record or upload Ga speech and receive a text transcription. The deployed system integrated a FastAPI backend, an HTML/JavaScript interface, Nginx, and Docker-based containerization.

Overall, the project demonstrated the feasibility of adapting a multilingual speech-recognition model to Ga and translating the trained model into a functional system through which users can interact with Ga speech-to-text technology.

## Demo

*Project demo will be added here.*
