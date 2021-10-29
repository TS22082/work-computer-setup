# Necessary Software

- Slack
  - Have this installed on your computer rather than use the web app.
- VScode
- Zoom
- Git bash
- Node
  - Current version; Not LTS

# Extensions

- Auto Close Tag
- Auto Import
- Auto Import - ES6, TS, JSX, TSX
- Auto Rename Tag
- Better Comments
- Bracket Pair Colorizer 2
- Code Spell Checker
- Color Highlight
- colorize
- ES7 React/Redux/GraphQL/React-Native snippets
  - we may end up creating our own snippet library to replace this one
- Git Graph
- Highlight Matching Tag
- Javascript Booster
- Mantas Third Eye
- Material Color
- npm intellisense
- Path Autocomplete
- vscode-styled-components

- Prettier

  - open you settings.json file add add this

  ```js
  "editor.formatOnSave": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  ```

Note:

To open the settings.json file press and hold:

- `ctrl + SHIFT + p`.

In the text box that opens type:

- `settings (JSON)`

Click on the matching result and you will be in the settings.json file
