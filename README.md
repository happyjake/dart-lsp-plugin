# dart-lsp

Dart language server for Claude Code, providing code intelligence for Dart and Flutter projects.

## Supported Extensions

`.dart`

## Prerequisites

The Dart SDK includes the language server. Install via:

### macOS

```bash
brew install dart
```

### Or install Flutter (includes Dart)

```bash
brew install --cask flutter
```

After installation, `dart` should be available in your PATH.

## Usage

**Important:** LSP support requires a specific Claude Code version and environment variable:

```bash
ENABLE_LSP_TOOL=true npx @anthropic-ai/claude-code@2.0.67 --plugin-dir /path/to/dart-lsp-plugin
```

Once running, you can use LSP features on `.dart` files:
- Hover for type information
- Go to definition
- Find references

## More Information

- [Dart SDK](https://dart.dev/get-dart)
- [Flutter](https://flutter.dev/)
