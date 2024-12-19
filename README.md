# English-Vietnamese Translation with BERT – Transformer Model 🌐🔄🇬🇧🇻🇳

Welcome to the **English-Vietnamese Translation** project! This repository contains a web application powered by a transformer-based model (MarianMT) for translating English text into Vietnamese. The project is built using Flask for the backend and a simple HTML+JavaScript frontend for user interaction.

## Features ✨

- **Real-time Translation**: Translate English text to Vietnamese instantly.
- **User-Friendly Interface**: Simple and intuitive web interface.
- **Powered by Transformers**: Utilizes MarianMT model from Hugging Face for accurate translations.
- **Flask Backend**: Lightweight backend server using Flask.
- **CORS Enabled**: Allows cross-origin requests for seamless API integration.

## Getting Started 🚀

### Prerequisites

Ensure you have the following installed:
- Python 3.6+
- pip (Python package installer)
- virtualenv (optional but recommended)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/english-vietnamese-translation.git
    cd english-vietnamese-translation
    ```

2. **Create and activate a virtual environment** (optional but recommended):
    ```bash
    virtualenv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install required packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Ensure model files are in place**: Place the model files in the `opus-mt-en-vi` directory.

### Running the Application

1. **Start the Flask server**:
    ```bash
    python app.py
    ```

2. **Open the web interface**: Open `index.html` in your preferred web browser.

3. **Translate Text**: Enter English text into the provided textarea and click "Translate" to see the translation in Vietnamese.

## Usage Example 📚

Here's an example of how to use the API:

- **Endpoint**: `POST /translate`
- **Request Body**:
    ```json
    {
        "text": "Hello, how are you?"
    }
    ```
- **Response**:
    ```json
    {
        "translated_text": "Xin chào, bạn khỏe không?"
    }
    ```

## Contributing 🤝

Contributions are welcome! Please fork this repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements 🙌

- **Hugging Face** for the amazing transformers library.
- **Flask** for the lightweight web framework.
- **GitHub** for providing an amazing platform to share and collaborate on projects.

---

Feel free to customize this README.md to better fit your project. Happy coding! 😊
