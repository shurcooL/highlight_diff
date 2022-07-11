highlight_diff
==============

[![Go Reference](https://pkg.go.dev/badge/github.com/shurcooL/highlight_diff.svg)](https://pkg.go.dev/github.com/shurcooL/highlight_diff)

Package highlight_diff provides syntaxhighlight.Printer and syntaxhighlight.Annotator implementations
for diff format. It implements intra-block character-level inner diff highlighting.

It uses GitHub Flavored Markdown .css class names "gi", "gd", "gu", "gh" for outer blocks,
"x" for inner emphasis blocks.

Installation
------------

```sh
go get github.com/shurcooL/highlight_diff
```

License
-------

-	[MIT License](LICENSE)
