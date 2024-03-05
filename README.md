
# PDF Summarizer using AI

This project is a PDF summarizer that utilizes artificial intelligence (AI) to summarize the content of PDF files. The application extracts text from PDF files using pdf-parse and interacts with the OctoAI platform for natural language processing.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your_username/PDF-summarizer.git
    ```

2. Navigate to the project directory:

    ```bash
    cd PDF-summarizer
    ```

3. Install dependencies using npm:

    ```bash
    npm install
    ```

4. Create a `.env` file in the root directory of the project and add your OctoAI API token:

    ```
    OCTOAI_TOKEN=your_octoai_api_token
    ```

## Usage

1. Place your PDF files in the `files` directory within the project.

2. Run the application:

    ```bash
    node index.js
    ```

3. Follow the prompts to select the model and PDF file you want to summarize.

4. Once the summary is generated, it will be saved as a text file with the same name as the original PDF file in the `files` directory.

## Dependencies

- @octoai/client
- prompts
- pdf-parse

## Contributing

Contributions are welcome! If you encounter any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

