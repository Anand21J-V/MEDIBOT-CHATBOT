# MEDIBOT-CHATBOT

**MEDIBOT-CHATBOT** is an AI-powered medical chatbot designed to assist users with health-related queries. Built using Python and Jupyter Notebook, this project aims to provide accessible medical information through a conversational interface.

## Features

- **Conversational AI**: Engage in natural language conversations to receive medical information.
- **Data-Driven Responses**: Utilizes datasets stored in the `Data/` directory to inform responses.
- **Modular Architecture**: Organized codebase with separate directories for source code, templates, static files, and research materials.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Anand21J-V/MEDIBOT-CHATBOT.git
   cd MEDIBOT-CHATBOT
   ```


2. **Create and Activate Virtual Environment**:
   ```bash
   conda create -n medibot python=3.10 -y
   conda activate medibot
   ```


3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```


## Usage

1. **Run the Application**:
   ```bash
   python app.py
   ```


2. **Interact with the Chatbot**:
   Open your browser and navigate to `http://localhost:5000` to start interacting with MEDIBOT.

## Project Structure


```plaintext
MEDIBOT-CHATBOT/
├── Data/               # Contains datasets used by the chatbot
├── research/           # Research materials and documentation
├── src/                # Source code for the chatbot's functionality
├── static/             # Static files (CSS, JS, images)
├── templates/          # HTML templates for the web interface
├── app.py              # Main application script
├── requirements.txt    # Python dependencies
├── setup.py            # Setup script for the project
├── store_index.py      # Script for indexing data
├── template.py         # Template script (details TBD)
├── test.py             # Test script for the application
├── LICENSE             # MIT License
└── README.md           # Project documentation
```


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Anand Vishwakarma
