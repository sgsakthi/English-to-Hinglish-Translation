# English text to Hinglish Translation

This code extracts text from a PDF using `pdfminer` and then translates the extracted English text into Hinglish using the OpenAI API. The translated text is saved to a new text file.

Note: While there isn't a robust library available for converting English text into Hinglish, there are a few APIs that show potential and have achieved a considerable level of acceptance, one of which is used in this repository.

## Overview

1. **Text Extraction**: The `pdfminer` library is used to extract text from a provided PDF.
2. **Translation**: The extracted English text is translated into Hinglish using the OpenAI API.
3. **Output**: The translated Hinglish text is saved to a new text file.

## Prerequisites

- Python 3.x
- Libraries: `pdfminer.six`, `openai`, `python-dotenv`
- An OpenAI API key

