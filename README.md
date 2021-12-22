# TypeDoc Watch Mode Bug

Demonstrate bug with TypeDoc watch mode and typedoc-plugin-markdown

## Reproduction steps

1) Install packages with `yarn`
2) Running `yarn typedoc` generates correct output as a markdown file
3) Running `yarn typedoc-watch` correctly generates markdown output at first, but editing the source file (`src/index.ts`) and saving it results in HTML files being built and the original markdown is deleted.
