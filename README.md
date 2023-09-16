# Jarvis-Termux

Jarvis-Termux is a PHP project that allows you to interact with an AI chat and voice assistant powered by OpenAI's ChatGPT model. It provides a convenient way to have voice-based conversations with an AI assistant right from your Termux terminal. You can ask questions, get responses, and even have a natural language conversation.

## Features

- Voice-based AI assistant: Interact with Jarvis using voice commands and receive spoken responses.
- Chat-based AI assistant: Interact with Jarvis using text.
- Natural language conversation: Engage in free-flowing conversations with the AI assistant.
- OpenAI-powered: Jarvis utilizes the OpenAI ChatGPT model for generating intelligent responses.
- Easy installation: Simply install the required libraries using Composer and you're ready to go.

## Libraries Used

- [ChatGPT](https://github.com/HaoZiTeam/ChatGPT-PHP) by HaoZiTeam: A PHP library for interacting with OpenAI's ChatGPT model.
- [LibConfig](https://github.com/Amitminer/LibConfig-PHP) by AmitxD: A configuration management library for PHP.
- [LibVoice (Termux)](https://github.com/Amitminer/LibVoice) by AmitxD: A PHP library for voice interaction using Termux.

## Getting Started

### Prerequisites

- PHP: Make sure you have PHP installed on your system. You can check by running `php -v` in your terminal.
- Composer: Install Composer, the PHP dependency management tool, on your system. You can download it from the official Composer website.

### Installation

1. Clone the Jarvis-Termux repository from GitHub:
   ```bash
   git clone https://github.com/Amitminer/Jarvis-Termux.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Jarvis-Termux
   ```

3. Install the required libraries using Composer:
   ```bash
   composer install
   ```

### Usage

1. Obtain an API access token from OpenAI:
   - Login to your OpenAI account.
   - Visit https://chat.openai.com/api/auth/session to obtain your access_token.

2. Update the API token in the `config.yml` file:
   - Open the `config.yml` file in a text editor.
   - Replace `<i hate myself>` with your actual access token obtained from OpenAI.
   - Save the changes.

3. Run the Jarvis-Termux script:
   ```bash
   php src/Jarvis.php
   ```

4. Start talking to Jarvis:
   - Choose the mode you want to talk with Jarvis using that!.
   - Speak commands or ask questions to Jarvis.
   - Jarvis will respond with spoken answers and text answer generated by the AI.

### Todo

- Add functionality to open various apps using Jarvis.

## Contributions

Contributions to Jarvis-Termux are welcome! If you have any ideas, suggestions, or bug reports, please feel free to create an issue or submit a pull request on the [Jarvis-Termux GitHub repository](https://github.com/Amitminer/Jarvis-Termux). Let's make Jarvis-Termux even better together!

## License

Jarvis-Termux is released under the [MIT License](https://github.com/Amitminer/Jarvis-Termux/blob/main/LICENSE).

---

**Note:** This project is for educational purposes only. Use it responsibly and be aware of OpenAI's usage policies and any applicable terms and conditions.
