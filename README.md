# Insightful-Review-A-PyMuPDF-and-PyPDFLLM-Exploration
This project aims to automate the extraction, categorization, summarization, and analysis of key information from documents to assist investors in their evaluations. 
This project is designed to extract key information from company-related PDF documents, providing investors with essential insights to evaluate future growth prospects, business changes, key triggers, and material financial impacts. The application utilizes Natural Language Processing (NLP) to summarize and analyze the extracted data effectively.
 ## Features
- Extracts text from PDF documents using `PyMuPDF`.
- Categorizes text into key areas of interest for investors.
- Summarizes extracted text and performs sentiment analysis.
- Outputs structured insights that are easy to understand.
## Technologies Used
- Python
- PyMuPDF (fitz)
- Hugging Face Transformers for NLP
- Regular Expressions for text categorization
## Installation
To run this project, you'll need to have Python installed. You can install the required packages using pip:

```bash
pip install PyMuPDF transformers
 ## Usage
To extract insights from a PDF, place your PDF file in the designated directory and run the main script:

```python
pdf_path = "/path/to/your/document.pdf"
main(pdf_path)


## Example Output

Category: Future Growth Prospects
Summary: The company is expected to expand into new markets, showing a positive growth trajectory.
Sentiment: POSITIVE (Score: 0.95)
