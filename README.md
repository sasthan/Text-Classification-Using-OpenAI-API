Here's a simple README for the Jupyter notebook:

---

# Text Classification Using OpenAI API

This Jupyter notebook demonstrates how to use OpenAI's API for text classification. It categorizes input text into predefined labels using a prompt-based approach with the OpenAI model `gpt-3.5-turbo`.

## Requirements

1. **Python 3.7+**
2. **OpenAI Python SDK**  
   Install via pip:
   ```bash
   pip install openai
   ```

## Setup

1. Obtain an API key from [OpenAI](https://platform.openai.com/signup).
2. Replace `"your-api-key"` in the notebook with your actual OpenAI API key.

## Usage

- **Classification Labels**: Customize the categories to suit your specific classification needs.
- **Input Text**: Modify the `texts` list to include the texts you want to classify.

### Running the Notebook

1. Load the notebook in Jupyter.
2. Run the code cells to see how each input text is categorized by the model.

## Example Output

Each text entry will be classified into one of the specified categories. Example output:

```plaintext
Text: The stock market is experiencing significant growth today.
Predicted Category: Finance

Text: This is a wonderful place for a family vacation!
Predicted Category: Travel
```

## Customization

- **Modify Categories**: Update the `categories` list with custom classification labels.
- **Change Model**: The code currently uses `gpt-3.5-turbo`. You can specify a different model by updating the `model` parameter in the `classify_text` function.

---

This notebook provides a quick and customizable method for text classification using OpenAI’s language models.
