# OCR with Mistral Model in Google Colab — Complete Guide

## Overview
This project demonstrates how to perform Optical Character Recognition (OCR) on documents and images using the **Mistral AI OCR model** within a Google Colab notebook. It covers:

- Installing the required Python SDK (`mistralai`)
- Uploading and processing both PDF and image files
- Extracting OCR text, including embedded images, from documents
- Converting OCR markdown output into structured JSON data using Mistral’s chat model
- Displaying the final OCR results with images inline in the notebook

Colab Notebook link - https://colab.research.google.com/drive/1a7J86amiy-UF2ph-2saWfDqBQacHVVV-?usp=sharing 

---

## Why OCR?

OCR (Optical Character Recognition) converts text in images or scanned documents into machine-readable text. This enables automated processing of:

- Receipts
- Invoices
- PDFs
- Scanned forms  
and many other document types.

---

## Prerequisites

- Google Colab or any Python 3.8+ environment  
- A valid **Mistral API key** (sign up at [Mistral AI](https://mistral.ai) to get your free key)  
- Basic Python knowledge is helpful but not required

---

## Setup Instructions

### 1. Install the Mistral SDK
```python
!pip install mistralai
