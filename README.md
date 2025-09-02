# Kiddocare Flutter Snippets

Flutter code snippets with Kiddocare structure (constructors, fields, methods).

## Features

This extension provides Flutter/Dart code snippets that follow the Kiddocare coding standards with proper structure:

- Organized constructor, fields, and methods sections
- Consistent comment headers
- Common Flutter widget patterns

## Snippets

| Prefix | Description |
|--------|-------------|
| `stlsk` | StatelessWidget with Kiddocare structure |
| `stlsfk` | StatefulWidget with Kiddocare structure |
| `stlp` | Private widget template |

## Usage

1. Type the snippet prefix (e.g., `stlsk`)
2. Press `Tab` to expand the snippet
3. Use `Tab` to navigate through placeholders
4. Fill in your class names and content

## Example

Type `stlsk` and press Tab:

```dart
class WidgetName extends StatelessWidget {
  // ------------------------------- CONSTRUCTORS ------------------------------
  const WidgetName({super.key});

  // ------------------------------- FIELDS ------------------------------------
  // Add your fields here

  // --------------------------------- METHODS ---------------------------------
  @override
  Widget build(BuildContext context) {
    return Container();
  }

  // Add your methods here
}
```

## Installation

Install from VS Code Extensions Marketplace or manually install the .vsix file.

## License

MIT
