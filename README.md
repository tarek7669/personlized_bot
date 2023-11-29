# PersonalizedBot

PersonalizedBot is a chatbot project that aims to replicate the user's personality using state-of-the-art natural language processing techniques. The chatbot is built on the llama-2-7b-chat-hf pretrained model from Hugging Face, fine-tuned with a dataset extracted from WhatsApp conversations. Additionally, the Lora pre-trained model, tokenization, dropout, PyTorch, and various optimization techniques are employed to enhance the chatbot's performance.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Personality Replication:** The chatbot is designed to emulate the user's personality, providing a unique and personalized interaction experience.
  
- **Fine-Tuning:** The project utilizes fine-tuning techniques to adapt the pretrained model to the specific conversational patterns found in the user's WhatsApp conversations.

- **Lora Model Integration:** The Lora pre-trained model is integrated to further enhance the language generation capabilities of the chatbot.

- **Tokenization and Dropout:** Tokenization methods and dropout techniques are implemented to optimize data input and ensure the model's robustness.

- **PyTorch Implementation:** The chatbot is developed using PyTorch, a powerful deep learning framework, for flexibility and efficiency in natural language processing tasks.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/tarek7669/personalized_bot.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Navigate to the project directory:

```bash
cd personalized_bot
```

2. Run the chatbot application:

```bash
python generate.ipynb
```

3. Interact with the chatbot and enjoy the personalized conversational experience!

## Technologies Used

- Hugging Face Models: [llama-2-7b-chat-hf](https://huggingface.co/models)
- PyTorch: [PyTorch](https://pytorch.org/)
- Lora Model: [alpaca-lora-7b](https://huggingface.co/models)
- Other tools: Tokenization, Dropout, Evaluation Metrics, Adam Optimizer

## Contributing

If you would like to contribute to the project, please contact me at [my mail](tarek.ashraf.7669@gmail.com).

Feel free to customize the sections and details based on your project's specific information and needs.
