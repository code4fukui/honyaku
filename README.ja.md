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

Honyaku (翻訳) は、日本語のテキストを英語に翻訳するための、シンプルで強力なPythonライブラリです。

## 機能

- **高品質な翻訳**: 正確で文脈を考慮した翻訳を提供します。
- **フォーマット認識**: プレーンテキスト、HTML、Markdownをインテリジェントに処理し、構造を保持します。
- **シンプルなAPI**: 迅速な組み込みを可能にする、クリーンでわかりやすいインターフェース。

## はじめに

### 前提条件

- Python 3.7 以上

### インストール

pipを使用してPyPIから `honyaku` をインストールします:

```sh
pip install honyaku
```

## 使用方法

`translate` 関数をインポートし、日本語のテキストを渡します。

```python
from honyaku import translate

# Translate a simple sentence
japanese_text = "日本語の文章です。"
english_text = translate(japanese_text)

print(f"'{japanese_text}' -> '{english_text}'")
# Expected output:
# '日本語の文章です。' -> 'This is a Japanese sentence.'
```

このライブラリは、HTMLやMarkdownなどのさまざまな入力フォーマットを自動的に処理し、タグや構文を保持したままコンテンツを翻訳します。

## ライセンス

このプロジェクトは MIT License のもとで公開されています。詳細は [LICENSE](LICENSE) ファイルをご覧ください。
