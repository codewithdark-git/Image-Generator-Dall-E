
# Ai Image Generator Flask App

This Flask app allows you to generate images using the OpenAI API based on a given prompt. It uses the OpenAI GPT-3 API to create images based on the provided prompt.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/codewithdark-git/ai-image-generator-flask-app.git
    cd ai-image-generator-flask-app
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up your OpenAI API key:

    - Open the `config.py` file and replace `YOUR_OPENAI_API_KEY` with your actual OpenAI API key.

4. Run the Flask app:

    ```bash
    python main.py
    ```

    The app will be accessible at `http://127.0.0.1:5000/` in your web browser.

## Usage

### 1. Home Page

Visit the home page to interact with the Ai Image Generator.

### 2. Generate Images

Make a request to the `/generateimages/<prompt>` endpoint to generate images based on a specific prompt. For example:

- Open your browser and go to `http://127.0.0.1:5000/generateimages/your_prompt_here`.

### 3. Results

The generated images will be displayed on the home page or as specified in your HTML and JavaScript code.

## Dependencies

- Flask
- OpenAI

## Configuration

Ensure that you have a valid OpenAI API key and set it in the `config.py` file.

## Author
@codewithdark-git

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
