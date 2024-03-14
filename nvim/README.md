## My Config for NeoVim

This config is mostly based on Typecraft's config from the NeoVim for Newbs video series.

However, I needed to add in a few other plugins. They are as follows:

- Auto close HTML tags
- Auto close brackets, parentheses, and quotes
- Support for the Svelte language server for LSP autocomplete

On that last point, to enable Svelte-LSP support, install the LSP through Mason, run the following:

```
npm i -g svelte-language-server
```

Then everything should work. The config for svelte capabilities has already been added.

I will continue to update this config over time. I'm eying whichkey, oil, and some other fun plugins.
