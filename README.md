# Rhino for Alfresco Web Scripts - Basic Language Support

Alfresco Content Services 6.2 uses [Rhino](https://github.com/mozilla/rhino) as its JavaScript engine for Web Scripts.  
Rhino differs significantly from modern JavaScript runtimes supported by Visual Studio Code, which causes the built-in JavaScript language support to behave incorrectly.

This extension provides **basic syntax highlighting** tailored for Rhino-based Web Scripts used in Alfresco 6.2.

<img width="956" height="440" alt="image" src="https://github.com/user-attachments/assets/e2c61897-d1da-452d-ac1a-a245120a4875" />

<img width="380" height="66" alt="image" src="https://github.com/user-attachments/assets/5cdea502-64d5-4f20-a422-9e0bf39f71e7" />

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
