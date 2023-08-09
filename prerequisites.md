# Installation Prerequisites
===========================

This document describes the installation prerequisites for the GenAI project. The following sections describe the installation steps for the following components:

## 1. Python Installation

Download and install Python from the official website: [Python Downloads](https://www.python.org/downloads/)

## 2. pip Installation

Pip, a package installer, is typically included with Python. If you encounter any pip-related errors, resolve them using the following commands:
```bash
python -m ensurepip
python -m pip install --upgrade pip
```

## 3. Jupyter Extension Installation

Integrate the Jupyter extension for effective notebook interaction.

## 4. Create a folder “GenAI” in your local system and follow the below steps

* Create a virtual environment using the following command:
```bash
python -m venv env
```
* Activate the virtual environment:
```bash
.\env\Scripts\activate
```

## 5. Install the spaCy, OpenAI  and NLTK library using the below command:

```bash
pip install -U spacy openai nltk
```

## 6. Install spacy model required for NER

```bash
python -m spacy download en_core_web_md
```
