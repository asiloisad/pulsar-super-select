# super-select

Text selection helpers and slash normalization commands.

## Features

- **String selection**: Select text inside quotes.
- **Bracket selection**: Select text inside brackets.
- **Character patterns**: Select by custom character sets.
- **Slash normalization**: Convert path separators to forward slash, backslash or double backslash.
- **HTML selection**: Select HTML body or tags.

## Installation

To install `super-select` search for [super-select](https://web.pulsar-edit.dev/packages/super-select) in the Install pane of the Pulsar settings or run `ppm install super-select`. Alternatively, you can run `ppm install asiloisad/pulsar-super-select` to install a package directly from the GitHub repository.

## Commands

Commands available in `atom-text-editor`:

- `super-select:chars-1`: select text by chars `/[0-9\\p{L}_\\.]/`,
- `super-select:chars-2`: select text by chars `/[0-9\\p{L}_\\.\\-\\[\\]\\(\\)#]/`,
- `super-select:string`: <kbd>Alt+S</kbd> select text inside `'''`, `"""`, `'` or `"`,
- `super-select:string-'-'`: select text inside`'''` or `'`,
- `super-select:string-'''-'''`: select text inside `'''`,
- `super-select:string-\`-\``: select text inside backticks,
- `super-select:string-"-"`: select text inside `"""` or `"`,
- `super-select:string-"""-"""`: select text inside `"""`,
- `super-select:brackets`: <kbd>Alt+D</kbd> select text inside `()`, `[]`, `{}` or `<>`,
- `super-select:brackets-(-)`: select text inside `()`,
- `super-select:brackets-[-]`: select text inside `[]`,
- `super-select:brackets-{-}`: select text inside `{}`,
- `super-select:brackets-<->`: select text inside `<>`,
- `super-select:normalize`: convert slashes to match the most left slash inside selection,
- `super-select:double-backslash`: <kbd>Ctrl+Alt+\\</kbd> convert slashes to `\\` inside selection,
- `super-select:backslash`: <kbd>Alt+\\</kbd> convert slashes to `\` inside selection,
- `super-select:forward-slash`: <kbd>Alt+/</kbd> convert slashes to `/` inside selection,
- `super-select:html-body`: select html body,
- `super-select:html-tags`: select html tags.

## Contributing

Got ideas to make this package better, found a bug, or want to help add new features? Just drop your thoughts on GitHub. Any feedback is welcome!
