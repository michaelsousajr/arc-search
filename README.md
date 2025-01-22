# Arc Search Plugin for Oh My Zsh

A Zsh plugin that enables quick searches using Arc browser directly from your terminal. Features incognito mode support and URL encoding for search terms.

## Features

- Search web from terminal
- Incognito mode support with `-i` flag
- URL encoding for search terms
- Command completion
- Special character handling

## Prerequisites

- Oh My Zsh
- Arc Browser
- Python 3 (for URL encoding)

## Installation

1. Clone this repository into your Oh My Zsh custom plugins directory:

   ```bash
   git clone https://github.com/yourusername/arc-search ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/arc-search
   ```

2. Add the plugin to your `.zshrc`:

   ```bash
   plugins=(... arc-search)
   ```

3. Reload your shell:
   ```bash
   source ~/.zshrc
   ```

## Usage

```bash
# Open Arc browser
arc

# Search in Arc
arc how to code

# Search in incognito mode
arc -i how to code

# Open Arc in incognito mode
arc -i
```

## Testing

Run the test suite:

```bash
cd ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/arc-search/tests
./test_arc.zsh
```

## Contributing

1. Fork the repository.
2. Create your feature branch:
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/amazing-feature
   ```
5. Open a Pull Request.