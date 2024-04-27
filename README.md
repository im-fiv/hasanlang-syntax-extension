# Hasanlang Syntax Extension
![Build Status](https://github.com/im-fiv/hasanlang/actions/workflows/build.yml/badge.svg)

This is a VS Code extension for [Hasanlang](https://github.com/im-fiv/hasanlang)

## Building
You can directly download the latest version from releases. Alternatively, if you want to build it yourself:

```bash
git clone https://github.com/im-fiv/hasanlang-syntax-extension.git
cd hasanlang-syntax-extension
npm i @vscode/vsce
npx vsce package
```

Then, you can go to `Extensions` in VS Code, click on the ellipsis, and `Install from VSIX...`. Finally, choose the file that VSCE generated and reload VS Code.

## Contributing
As with Hasanlang, all contributions are welcome. This is my first experience with writing a syntax highlighting extension.

## License
This extension is [MIT licensed](https://en.wikipedia.org/wiki/MIT_License).