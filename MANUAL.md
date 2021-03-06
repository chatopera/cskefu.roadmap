# markdown2word-doc-template

Markdown to Word Document Template

## Deps

* Python 3
* Pandoc 2.11
* Git && Git Bash for Windows

```bash
pip install -r requirements.txt
```

## Add a Cover

Get cover samples in [assets/covers](./assets/covers/).

Save cover in [Office Word](https://www.thewindowsclub.com/insert-cover-page-to-a-document-word).

## Sample Markdown File

[default.m.md](./styles/default.m.md)

## Tune Styles in Two Ways

1. Modify `styles/default.m.md`

Then, run `scripts/style.sh`

2. Modify `styles/default.docx` directly

```
Paragraph styles:

Normal
Body Text
First Paragraph
Compact
Title
Subtitle
Author
Date
Abstract
Bibliography
Heading 1
Heading 2
Heading 3
Heading 4
Heading 5
Heading 6
Heading 7
Heading 8
Heading 9
Block Text
Footnote Text
Definition Term
Definition
Caption
Table Caption
Image Caption
Figure
Captioned Figure
TOC Heading
Character styles:

Default Paragraph Font
Body Text Char
Verbatim Char
Footnote Reference
Hyperlink
Section Number
Table style:

Table
```
