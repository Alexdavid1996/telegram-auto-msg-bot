Here is the complete README.md file with proper Markdown formatting and closing of code blocks:

markdown
Copy code
# DuTecZone Telegram Auto MsgBot

Welcome to the DuTecZone Telegram Auto MsgBot! This Python-based automation tool is designed to simplify the process of forwarding messages from your Saved Messages to multiple Telegram groups. Whether you're managing communication for a community or need to distribute messages efficiently, this tool helps automate the process.

## Features

- **Automated Message Forwarding**: Automatically sends the latest message from your Saved Messages to multiple Telegram groups.
- **Dynamic Configuration**: Prompts for API ID, API HASH, phone number, and verification code as needed.
- **File Management**: Creates necessary files (`Credentials.txt` and `Groups.txt`) if they do not exist and handles file reading/writing.
- **Continuous Operation**: Restarts automatically after sending all messages, ensuring ongoing operation.
- **Error Handling**: Provides feedback and error messages to help troubleshoot any issues.

## Installation

To get started, clone the repository and install the required dependencies. Follow these steps:

### Clone the Repository

```bash
git clone https://github.com/Alexdu1996/telegram-auto-msg-bot.git
cd telegram-auto-msg-bot
```
## Install Dependencies
```bash
pip install -r requirements.txt
```
## Usage
Run the Script
Execute the Python script to start the bot:
```bash
python TG_Auto.py
```
Provide Credentials
On first run, the script will ask for your API ID, API HASH, phone number, and verification code. These details will be saved in Credentials.txt for future use.

Configure Group URLs
Ensure that Groups.txt contains the URLs of the groups you want to forward messages to. If Groups.txt does not exist, the script will create it, but you need to add the URLs manually.

Set Delay
You can set a delay between messages to avoid hitting Telegram’s rate limits. This is prompted during the script’s execution.

Important Notes
Read Telegram's API Policy: Ensure you are compliant with Telegram's API Policy to avoid any issues.
Avoid Overloading: Set an appropriate delay to avoid excessive messaging that may lead to bans or restrictions.
Contributing
Feel free to contribute to this project by submitting issues or pull requests. Your feedback and contributions are welcome!

License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any questions or support, you can reach out to:

- **Name**: Alex David Du
- **Website**: [DuTecZone](https://duteczone.net/)
