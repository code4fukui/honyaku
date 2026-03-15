# honyaku

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A Japanese-to-English translation tool.

## Features
- Translates Japanese text to English
- Supports a variety of input formats, including plain text, HTML, and Markdown
- Provides context-aware translations to improve accuracy

## Requirements
- Python 3.7 or higher

## Usage
1. Install the required dependencies:
   ```
   pip install honyaku
   ```
2. Import the `translate` function and use it to translate Japanese text to English:
   ```python
   from honyaku import translate
   
   japanese_text = "日本語の文章です。"
   english_text = translate(japanese_text)
   print(english_text)
   ```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.