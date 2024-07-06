<br>
<p align="center">
  <a href="https://chatide.dev" target="_blank">
    <img width="350" alt="image" src="https://i.pinimg.com/originals/f4/6a/88/f46a8822d4f2a6988c3769aefcdab512.png" alt="ChatIDE logo" >
  </a>
</p>
<p align="center">
    <b>CodeWhisper - AI assistant in your IDE</b><br/>
    <i>Upgrade from CodeGPT</i><br/>
  Converse with <a href="https://openai.com/blog/openai-api" target="_blank">OpenAI's ChatGPT</a> in VSCode
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=akshats911.CodeWhisper" target="_blank">
    <img width="309" alt="image" src="https://user-images.githubusercontent.com/3611042/232336724-71df6bf8-94e0-4b08-93fc-089ed70ad8ed.png">
  </a>
</p>


## Installation

Grab the latest CodeWhisper version from the Extensions Marketplace:<br>
https://marketplace.visualstudio.com/items?itemName=akshats911.CodeWhisper

## Bring Your Own API keys

To use ChatGPT in CodeWhisper, you need to procure API Key from OpenAI.
- **OpenAI**: https://openai.com/product#made-for-developers

## Usage

1. Bring up CodeWhisper with `Cmd + Shift + i` (or `Ctrl + Shift + i` on non-Apple platforms).
2. Choose your AI model. Currently supported: 
    - `'gpt-4'`, `'gpt-4-0613'`,`'gpt-3.5-turbo'`,`'gpt-3.5-turbo-16k'`  (OpenAI)
    - `'claude-v1.3'` (Anthropic)
4. On first usage, you'll be prompted to enter your API key for your chosen AI providers (will be stored in VSCode `secretStorage`).
5. Enjoy!

## Configuration

- Use the `Ctrl + Shift + P` keychord and type `>Open ChatIDE Settings`
  - Choose your preferred `model`, `max_tokens`, and `temperature`.
  - Adjust the system prompt to your liking
  - Note: settings will auto save
- Run CodeWhisper with `Ctrl + Shift + i`. You'll be asked for your OpenAI / Anthropic API key on first time you use the model.
  - Note: your API keys will be stored in [VS Code's `secretStorage`](https://code.visualstudio.com/api/references/vscode-api#SecretStorage)


### Updating your API key

1. Run `cmd + shift + P` (or `ctrl + shift + P`)
2. Start typing `>CodeWhisper`

#### OpenAI
3. Select `>Update your OpenAI API Key for CodeWhisper`.

#### Anthropic
3. Select `>Update your Anthropic API Key for CodeWhisper`.


## Warning

⚠️ This is an early prototype, use at your own peril.

🧐 Remember to keep an eye on your OpenAI billing.