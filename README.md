# ResuVerse: Intelligent Resume Insights

ResuVerse is an advanced resume parsing and analysis tool designed to extract meaningful insights from resume documents. By leveraging state-of-the-art NLP techniques and machine learning libraries, ResuVerse not only tokenizes and processes text but also employs sophisticated methods for named entity recognition (NER), semantic similarity, and sentiment analysis.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Logging](#logging)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

ResuVerse aims to automate the extraction and analysis of candidate resumes, enabling HR professionals and recruiters to quickly identify key skills, experience, and qualifications. The project integrates various NLP libraries such as NLTK, spaCy, and Sentence Transformers, alongside PDF parsing tools like pdfminer to handle resume documents in PDF format.

## Features

- **Resume Parsing** using pdfminer.
- **Text Processing** with NLTK for tokenization and stopword removal.
- **Enhanced Named Entity Recognition (NER)** using spaCy.
- **Frequency Distribution Analysis** with NLTK.
- **Semantic Analysis** via Sentence Transformers.
- **Detailed Logging** with Python's logging module.
- **Customizable and Extendable Pipeline.**

## Installation

### Prerequisites

- Python 3.7 or higher
- pip

### Clone the Repository

```bash
git clone https://github.com/yourusername/resuverse.git
cd resuverse
