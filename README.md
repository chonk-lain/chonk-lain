<div align="center">
	<h1>Chonkie 🦛</h1>
	<p><b>A lightweight, fast chunking library for text and data processing</b></p>
	<a href="https://chonkie.ai/">Website</a> | <a href="https://not-lain.github.io/">Maintainer</a>
</div>

---

## Overview

Chonkie is a blazing-fast, lightweight library designed to efficiently chunk text and data for downstream processing, search, and machine learning applications. Built for speed and simplicity, Chonkie helps you break down large datasets or documents into manageable pieces.

## Features

- 🚀 **Fast and lightweight**
- 🧩 **Flexible chunking strategies**
- � **Easy integration**
- 🛠️ **Minimal dependencies**

## Installation

```bash
pip install chonkie[all]
```

## Usage

```python
# First import the chunker you want from Chonkie 
from chonkie import TokenChunker

# Initialize the chunker
chunker = TokenChunker() # defaults to using GPT2 tokenizer

# Here's some text to chunk
text = """Woah! Chonkie, the chunking library is so cool!"""

# Chunk some text
chunks = chunker(text)

# Access chunks
for chunk in chunks:
    print(f"Chunk: {chunk.text}")
    print(f"Tokens: {chunk.token_count}")

```

## Contributing

Contributions are welcome! Please open issues or pull requests to help improve Chonkie.

## Maintainer

This is the work account for [not-lain](https://github.com/not-lain) and is intended for maintaining and contributing to [Chonkie 🦛](https://chonkie.ai/).

---

<div align="center">
	<sub>Made with ❤️ for the open-source community</sub>
</div>