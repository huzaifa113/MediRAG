# MediRAG - Clinical RAG Assistant using MIMIC-IV-Ext-DiReCT

This is a **Retrieval-Augmented Generation (RAG)** system built on the [MIMIC-IV-Ext-DiReCT](https://physionet.org/content/mimic-iv-ext-direct/1.0.0/ ) dataset.

## Features

- 📄 Retrieves clinical notes using **FAISS + all-MiniLM-L6-v2**
- 🤖 Generates answers using **google/flan-t5-base**
- 🧠 Supports diagnostic reasoning queries
- 🧩 Built with **Gradio** for easy interaction

## Usage

Ask clinical questions like:
- "What are the symptoms of ACS?"
- "What supports a diagnosis of heart failure?"

  Try it out Here: https://huggingface.co/spaces/huzaifa113/MediRAG

<img width="1348" height="599" alt="image" src="https://github.com/user-attachments/assets/80032aee-916d-4ec4-bf7d-8b390201f8e2" />
