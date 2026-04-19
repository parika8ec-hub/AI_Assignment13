## Text Generation using GPT-2 (Fine-Tuning Project)

This project demonstrates a simple text generation system using a fine-tuned transformer-based language model. The model is trained on a custom text dataset (Project Gutenberg book) and can generate coherent text based on a given prompt.

It is built using Python, PyTorch, and Hugging Face Transformers.

**Project Overview**

The goal of this project is to:

- Understand generative AI models
- Fine-tune a pre-trained language model
- Generate text from a seed prompt
- Explore real-world applications of NLP

The model used is GPT-2, fine-tuned using a dataset from Project Gutenberg.

**Features**
- Text generation from custom prompts
- Fine-tuning on domain-specific dataset
- Control over creativity using temperature,top-k sampling, top-p sampling and Repetition control for better output

**Technologies Used:**
Python
PyTorch
Hugging Face Transformers
NLP (Natural Language Processing)

**Project Structure**
- dataset/gutenberg_book.txt
- model/fine_tuned_model/
- Assignment13.py
- README.md

**Installation**
1. Clone the repository
git clone https://github.com/parika8ec-hub/AI_Assignment13.git
cd AI_Assignment13

3. Install dependencies
pip install torch transformers datasets

4. Run jupyter notebook and Assignment13.ipynb file

Example:
prompt = "Write a short story about a student learning AI"
print(generate_text(prompt))

Output:
A student named Alex began learning artificial intelligence at school. He built a small model that could understand simple sentences...

**Notes:**
The model may generate repetitive or unrelated text due to limitations of transformer-based language models.
Better results can be achieved by improving dataset quality and training time.

**Limitations:**
- Requires careful prompt design
- May produce hallucinated or inconsistent text
- Limited by dataset size and training duration

**Future Improvements**
- Use larger datasets
- Fine-tune longer epochs
- Apply advanced models (GPT-2 medium/large)
- Add web-based UI for text generation
