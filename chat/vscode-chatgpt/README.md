<h3 align="center">
Codeflow - VS Code Chat GPT extension
</h3>
<p align="center"><strong>Prompt OpenAI's GPT-4, GPT-3.5, GPT-3 and Codex models within Visual Studio Code</strong></p>


Forked from [ChatGPT - Genie AI](https://marketplace.visualstudio.com/items?itemName=genieai.chatgpt-vscode)

## Features

- ➕ Use GPT-4, GPT-3.5, GPT3 or Codex models using your OpenAI API Key
- 📃 Get streaming answers to your prompts in sidebar conversation window
- 🔥 Stop the responses to save your tokens.
- 📝 Create files or fix your code with one click or with keyboard shortcuts.
- ➡️ Export all your conversation history at once in Markdown format.
- Automatic partial code response detection. Continues and combines automatically, when response is cut off.
- Ad-hoc prompt prefixes for you to customize what you are asking ChatGPT
- Edit and resend a previous prompt
- Copy, insert or create new file from the code, ChatGPT is suggesting right into your editor.

## License

> If you are developing completely another extension and release it to the public, make sure you follow this.

This project is released under ISC License - See root License for details. Copyright notice and the respective permission notices must appear in all copies.

## How to build and run

- Clone the repository to your local machine
- On the root directory, run `yarn` command to install the dependencies listed in `package.json`
- Within VS Code - run the project by simply hitting `F5`

## How to install locally

- Install `vsce` if you don't have it on your machine (The Visual Studio Code Extension Manager)
  - `npm install --global vsce`
- Run `vsce package`
- Follow the <a href="https://code.visualstudio.com/docs/editor/extension-marketplace#_install-from-a-vsix">instructions</a> and install manually.
