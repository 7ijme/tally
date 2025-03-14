# The `tally` Package

The tally package automatically lists all todos in a document and highlights them.

## Usage

```typst
#import "@preview/tally:0.1.0": tally
#set text(font: "Barlow")
#show: tally.with(color: red)

= Introduction
#lorem(10)

TODO: Create introduction
```

Output:
