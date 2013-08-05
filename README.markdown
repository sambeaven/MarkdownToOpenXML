# MarkdownToOpenXML

Converts Markdown to a DocX file, allowing you to output Word files from your C# application via Markdown.

Very rough beginnings, currently only supports header1 & normal styles & bold, italics and underline inline styles. Will eventually include support for customizing styles (normal, header 1 etc) aswell as inline fonts etc. There was nothing like this already online so this could be a potential, very rough starting point.

## Usage:

```c#
using MarkdownToOpenXML;

string markdown = @"# This is a header";
MD2OXML.CreateDocX(markdown, @"C:\MyMarkdown.docx");
```

More to come.