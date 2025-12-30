# Rhino for Alfresco Web Scripts - Basic Language Support

Alfresco Content Services 6.2 uses [Rhino](https://github.com/mozilla/rhino) as its JavaScript engine for Web Scripts.  
Rhino differs significantly from modern JavaScript runtimes supported by Visual Studio Code, which causes the built-in JavaScript language support to behave incorrectly.

This extension provides **basic syntax highlighting** tailored for Rhino-based Web Scripts used in Alfresco 6.2.

## Features

- `<import>` tags don't break the entire file. They're also syntax highlighted differently.
- Unusual declarations such as `for each` aren't detected as errors.
- Retains most of the default JavaScript syntax highlighter behavior.

## Limitations

- Does **not** format code.
- Does **not** validate syntax.
- Does **not** provide IntelliSense or linting.

It is strictly a language grammar for highlighting.

## Release Notes

### 0.1.0

Initial version.
