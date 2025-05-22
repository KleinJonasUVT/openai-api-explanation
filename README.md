# OpenAI API Examples – "Waiter, Ask the AI Chef!"

Welcome to a hands-on introduction to using the **OpenAI API**, explained through a simple metaphor:

- 🧑 **Customer** = You (the user or your app)
- 🧾 **Waiter** = The API (OpenAI's messenger)
- 👨‍🍳 **Chef** = The AI model (like GPT-4)

![API Metaphor: Customer - Waiter - Chef](images/api-metaphor-diagram.png)

> _You (the customer) make a request (order). The API (waiter) delivers it to the model (chef), who prepares the response and sends it back._

---

## What's in This Repo?

This repository contains Jupyter notebooks and example code to help you:

- Understand what an API is, in plain terms.
- Make simple OpenAI API calls in Python.
- Structure prompts to get great responses from the model.
- Experiment with the OpenAI ChatCompletion endpoint.

---

## Quickstart

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/openai-api-examples.git
cd openai-api-examples
````

### 2. Install Dependencies

```bash
pip install openai
```

> You’ll also need [Jupyter](https://jupyter.org/) or [VS Code with Python extension](https://code.visualstudio.com/) to run notebooks.

### 3. Set Your API Key

Edit the Python file or notebook and replace:

```python
openai.api_key = "your-api-key-here"
```

> Best practice: Use environment variables or a `.env` file instead of hardcoding.

---

## Secure Your API Key

Never share your API key publicly! Use `.env` files and the `python-dotenv` package or GitHub secrets in production apps.

---

## Who Is This For?

* Educators wanting to use the API in their work
* Students exploring AI

---

