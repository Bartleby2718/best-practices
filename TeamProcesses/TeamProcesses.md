1. Align on a consistent coding style, and enforce it programmatically both locally and in the CI pipeline.
* Reasoning
  - Different coding styles cause unnecessary code changes.
* Caveats
  - The coding style should platform-independent.
- How-To:
  - Use a code editor or an IDE that respects a config file.
    - Visual Studio: `.editorconfig`
    - Visual Studio Code: `settings.json`
  - Use a code editor or an IDE that supports a keyboard shortcut for formatting a file, and use the shortcut frequently.
    - Visual Studio: Ctrl+K, Ctrl+D
    - Visual Studio Code: Shift+Alt+F
  - Python: [black](https://github.com/psf/black)
