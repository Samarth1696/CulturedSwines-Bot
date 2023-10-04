# Discord Chat Bot with ChatGPT

This is a Discord chat bot implemented in Rust using the Serenity library and the ChatGPT language model provided by OpenAI. The bot is capable of engaging in conversations with users, answering questions, and providing various functionalities.

## Features

- Responds to user messages with the help of ChatGPT, a powerful language model.
- Handles commands starting with a specific prefix.
- Roasts users and provides clever and witty replies.
- Persists conversation history for each user in JSON format.
- Supports token-based system for rewards and penalties.

## Prerequisites

- Rust programming language and Cargo package manager installed.
- Discord bot token (obtainable from the Discord Developer Portal).
- OpenAI API key for ChatGPT access.

## Installation

1. Clone the repository:
  ```bash
  git clone https://github.com/Samarth1696/CulturedSwines-Bot.git
  ```
2. Change into the project directory:
  ```bash
  cd discord-chat-bot
  ```
3. Install the dependencies and run the project using Cargo shuttle:
  ```bash
  cargo shuttle run
  ```

## Configuration

1. Create a `Secrets.toml` file in the project directory.

2. Add the following entries to the `Secrets.toml` file:
  ```toml
  DISCORD_TOKEN = "<your_discord_bot_token>"
  API_KEY = "<your_openai_api_key>"
  ```
  Replace `<your_discord_bot_token>` with your actual Discord bot token and `<your_openai_api_key>` with your OpenAI API key.

## Commands

The bot responds to messages starting with a specific prefix, which is set to `!` by default. Simply write any message with `!` as the prefix and you will get the response.

## Conversation and History

The bot maintains a conversation history for each user in JSON format. The history is stored in separate files named `<username>.json`. The conversation history is used to provide context and improve the quality of responses.

## License

This project is licensed under the MIT License.

## Disclaimer

This project is a proof-of-concept and should be used responsibly. The use of ChatGPT and its responses should comply with OpenAI's content policies and guidelines. OpenAI's content policies apply even if the bot claims to "do anything now".
