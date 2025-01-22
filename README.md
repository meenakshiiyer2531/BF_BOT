# Telegram Chatbot Using Pretrained Models

## Overview
This project involves the development and deployment of a Telegram chatbot leveraging pretrained language models such as DialoGPT, GPT-2, and LLaMA. The chatbot was shared with users to conduct a small research study aimed at analyzing response quality and understanding user perceptions of conversational AI. Insights gathered from the study were used to compare the performance of the models and improve user interactions.

## Features
- **Pretrained Models**: Utilizes DialoGPT, GPT-2, and LLaMA for generating conversational responses.
- **Telegram Integration**: Deployed as a Telegram bot for easy accessibility and interaction.
- **User Study**: Conducted a research study to gather user feedback and analyze the chatbot's performance.
- **Model Performance Comparison**: Compared the performance of different models based on user interaction and feedback.

## Installation

### Prerequisites
- Python 3.7+
- Telegram Bot API token
- Required Python libraries (listed in `requirements.txt`)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/meenakshiiyer2531/BF_BOT
   cd telegram-chatbot
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the Telegram Bot:
   - Create a bot using BotFather on Telegram.
   - Obtain the API token and update the `config.py` file with your token.

4. Run the chatbot:
   ```bash
   python bot.py
   ```

## Usage
- Users can interact with the chatbot by sending messages on Telegram.
- The bot responds using the selected pretrained model.
- User interactions are logged for research and analysis purposes.

## Research Study
### Objectives
- Analyze the response quality of the chatbot.
- Understand user perceptions of conversational AI.
- Compare the performance of different pretrained models.

### Methodology
- The bot was shared with a selected group of users.
- Users were encouraged to interact and provide feedback.
- Data was collected and analyzed to gather insights on model performance.

### Findings
- **Response Quality**: DialoGPT provided more conversationally natural responses, while GPT-2 and LLaMA showed varying strengths.
- **User Perception**: Users found the bot engaging but noted differences in response relevance across models.
- **Model Comparison**: DialoGPT was preferred for casual conversations, whereas GPT-2 and LLaMA had niche advantages.

## Future Work
- Further fine-tuning of models based on user feedback.
- Expanding the user base for a more comprehensive study.
- Implementing additional features to enhance user interaction.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Contact
For any questions or feedback, please contact [vmeenakshi122002@gmail.com](mailto:vmeenakshi122002@gmail.com).
