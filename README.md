# PHP Harness for [Workspace]

To use this harness:

1. Install [Workspace]
2. Run `ws create <projectName> inviqa/php:v1.5.2`
3. Fill in project-specific AWS and Github credentials, set as blank if you don't need them
4. Change to the <projectName> directory: `cd <projectName>`
5. Create an initial commit, ensuring that `workspace.override.yml` is not added to git:
```bash
git init
git add .
git commit -m "Initial commit"
```
6. Store the `workspace.override.yml` contents in a suitable location (such as LastPass).

[Workspace]: https://github.com/my127/workspace
