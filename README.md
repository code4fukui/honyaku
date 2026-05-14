# honyaku

[
![PyPI version](https://badge.fury.io/py/honyaku.svg)
](https://badge.fury.io/py/honyaku)
[
![Python Versions](https://img.shields.io/pypi/pyversions/honyaku.svg)
](https://pypi.org/project/honyaku)
[
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
](https://opensource.org/licenses/MIT)

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

Honyaku (翻訳) is a simple and powerful Python library for translating Japanese text to English.

## Features

- **High-Quality Translation**: Provides accurate, context-aware translations.
- **Format-Aware**: Intelligently handles plain text, HTML, and Markdown, preserving structure.
- **Simple API**: A clean and straightforward interface for quick integration.

## Getting Started

### Prerequisites

- Python 3.7 or higher

### Installation

Install `honyaku` from PyPI using pip:

```sh
pip install honyaku
```

## Usage

Import the `translate` function and pass your Japanese text to it.

```python
from honyaku import translate

# Translate a simple sentence
japanese_text = "日本語の文章です。"
english_text = translate(japanese_text)

print(f"'{japanese_text}' -> '{english_text}'")
# Expected output:
# '日本語の文章です。' -> 'This is a Japanese sentence.'
```

The library automatically handles different input formats like HTML and Markdown, translating the content while preserving the tags and syntax.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.