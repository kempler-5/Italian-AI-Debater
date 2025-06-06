# Italian AI Debater 🤖🇮🇹

![Italian AI Debater](https://img.shields.io/badge/Download%20Releases-Click%20Here-blue)

Welcome to the **Italian AI Debater** repository! This project is a Python-based system designed to engage two AI personalities with opposing views in a debate on various topics. It generates topics, manages the conversation, and determines a winner. The system supports multiple AI models and is customizable, making it ideal for educational and creative purposes.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Customization](#customization)
- [Supported AI Models](#supported-ai-models)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Features

- **Dynamic Debates**: The system can generate a wide range of topics for debate.
- **Personality Simulation**: Two AI personalities engage in conversation, providing contrasting viewpoints.
- **Winner Determination**: The system evaluates the debate and declares a winner based on predefined criteria.
- **Customizable Settings**: Users can tweak various parameters to suit their needs.
- **Educational Tool**: Perfect for classrooms and learning environments.
- **Open Source**: Contribute to the project and help it grow.

## Getting Started

To get started with the Italian AI Debater, follow these steps:

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/kempler-5/Italian-AI-Debater.git
   cd Italian-AI-Debater
   ```

2. **Install Requirements**: 
   Ensure you have Python installed, then install the necessary packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the Latest Release**: 
   Visit the [Releases section](https://github.com/kempler-5/Italian-AI-Debater/releases) to download the latest version. Extract the files and execute the main script.

## Usage

To run the Italian AI Debater, use the following command in your terminal:

```bash
python main.py
```

The program will prompt you to select a debate topic or generate one randomly. Once you make your choice, the two AI personalities will start their debate.

### Example Interaction

1. **Select a Topic**: "Should pineapple be on pizza?"
2. **AI Personalities Engage**: 
   - AI 1: "Pineapple adds a sweet flavor that balances the savory taste of pizza."
   - AI 2: "Pizza should be traditional. Pineapple has no place on it."

3. **Winner Declaration**: After a series of arguments, the system will announce the winner based on the strength of the arguments presented.

## Customization

You can customize various aspects of the Italian AI Debater to enhance your experience:

- **AI Personalities**: Modify the characteristics of the AI personalities in the `config.py` file.
- **Debate Topics**: Add your own topics in the `topics.txt` file.
- **Evaluation Criteria**: Change how the winner is determined by editing the `evaluation.py` file.

## Supported AI Models

The Italian AI Debater supports multiple AI models, including:

- OpenAI GPT-3
- BERT
- DistilBERT
- Custom-trained models

You can switch between models in the configuration settings to see how different AIs handle debates.

## Contributing

We welcome contributions from the community! If you would like to help improve the Italian AI Debater, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Links

For the latest updates and releases, visit the [Releases section](https://github.com/kempler-5/Italian-AI-Debater/releases).

Thank you for your interest in the Italian AI Debater! We hope you find it engaging and useful for your educational and creative endeavors. Happy debating!