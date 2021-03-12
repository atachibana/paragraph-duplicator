# paragraph-duplicator

Paragraph Duplicator duplicates paragraph as HTML comment. It aids pre-process of translation of markdown contents.

Paragraph Duplicaator は段落ごとにコピーしたものをコメントとして挿入します。Markdown コンテンツを翻訳する際の前処理として使用することを想定しています。

## Syntax
paragraph-duplicator input-file [output-file]

## Sample
Input file:

```text
# Sample Handbook
## Overview

This Sample Handbook explains how to use these samples.
```

Output file:

```text
<!--
# Sample Handbook
-->
# Sample Handbook
<!--
## Overview
-->
## Overview

<!--
This Sample Handbook explains how to use these samples.
-->
This Sample Handbook explains how to use these samples.
```
