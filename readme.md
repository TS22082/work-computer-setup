# Necessary Software

- ZSH + oh-my-zsh + powerline

  - follow the instructions on this guide:
    https://caffeinedev.medium.com/customize-your-terminal-oh-my-zsh-on-ubuntu-18-04-lts-a9b11b63f2

- Slack

  - Have slack installed on your computer rather than using the web app.
  - Search and install "Slack" in Ubuntu Software.

- VScode

  - Search "VScode" and install "code" in Ubuntu Software.

- Zoom

  - follow this address : https://zoom.us/download?os=linux
  - Choose linux type: "Ubuntu".
  - Double click the .deb file that was downloaded and it should begin the install.

- Node

  - Do not install node from Ubuntus repos; it is out of date (version: 10)
  - Begin by installing curl:
    - run `sudo apt install curl`
  - Verify installation:
    - run `curl --version`
  - Install Node Version Manager (nvm):
    - `curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash`
  - Run all three just to be sure:
    - run `source ~/.profile`
    - run `source ~/.bashrc`
    - run `source ~/.zshrc`
  - Confirm latest LTS version available:
    - run `nvm list-remote`
  - In my case the latest LTS version was v16.13.0
    - run `nvm install v16.13.0`
      - The latest version of node (17.01) does not work with current version of expo. LTS is guaranteed to be stable.

- ## Expo cli

- run `npm install --global expo-cli`

# VScode Extensions + settings

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

  - open you settings.json file add add these lines

  ```js
  "editor.tabSize": 2,
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
