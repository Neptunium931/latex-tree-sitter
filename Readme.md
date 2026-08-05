# $\LaTeX$ Tree-sitter

This module provides a simple way to highlight a source code with a tree-sitter
parser.

## Requirements

You need a working `tree-sitter-highlight` and tree-sitter grammar highlighting
for the language you want to use.

## Example

```latex
\documentclass{article}

\usepackage{tree-sitter}

\begin{document}
\begin{tree-sitter}[language=c]
int main(int argc, char **argv) {
  printf("Hello World!\n");
}
\end{tree-sitter}
\end{document}
```

![Example](./.github/assets/example.png)

## Contributing

Pull requests are welcome. Feel free to open an issue if you want to add other features.
