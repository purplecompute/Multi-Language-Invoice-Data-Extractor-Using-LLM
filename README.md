# MultiLanguage Invoice Extractor

This project is a Streamlit application that uses Google Generative AI to analyze and extract information from invoices uploaded as images. The application allows users to input a prompt and upload an image of an invoice, and it returns a response based on the content of the image.

## Features

- Load environment variables from a `.env` file
- Use Streamlit for the web interface
- Upload and display images of invoices
- Use Google Generative AI to analyze the uploaded invoice and respond to user prompts

## Video Demo (Click the iameg to play the video)



[![Watch the video](https://raw.githubusercontent.com/purplecompute/Multi-Language-Invoice-Data-Extractor-Using-LLM/master/Media/Thumbnail_(Project_Demo).png)(https://raw.githubusercontent.com/purplecompute/Multi-Language-Invoice-Data-Extractor-Using-LLM/master/Media/demo.gif)
<!--(https://www.youtube.com/watch?v=snO5P9_n16E)-->

## Requirements

- Python 3.x
- Streamlit
- Google Generative AI
- Python Dotenv

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/multilanguage-invoice-extractor.git
    cd multilanguage-invoice-extractor
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv .venv
    source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Create a [.env](http://_vscodecontentref_/0) file in the root directory and add your Google API key:
    ```env
    GOOGLE_API_KEY=your_google_api_key
    ```

## Usage

1. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Enter a prompt in the input field, upload an image of an invoice, and click the "Tell me about the invoice" button.

## Project Structure

- [app.py](http://_vscodecontentref_/1): The main application file that contains the Streamlit app and the logic for interacting with Google Generative AI.
- [requirements.txt](http://_vscodecontentref_/2): A list of Python packages required for the project.
- [.env](http://_vscodecontentref_/3): A file to store environment variables (not included in the repository).
- [.gitignore](http://_vscodecontentref_/4): A file specifying which files and directories to ignore in the repository.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
