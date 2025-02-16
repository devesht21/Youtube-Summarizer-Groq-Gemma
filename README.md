
# # Summarize Text From YT or Website using Langchain and Gemma

This project is a Streamlit application that allows users to summarize content from YouTube videos or websites. The application uses the Langchain framework, Groq API, Gemma Large language mode and various document loaders to fetch and summarize the content.

You can check the live project [here](https://youtube-summarizer-groq-gemma.streamlit.app/)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites

- Python 3.10 or higher
- [Streamlit](https://streamlit.io/)
- [Langchain](https://github.com/hwchase17/langchain)
- [dotenv](https://pypi.org/project/python-dotenv/)
- [pypdf](https://pypi.org/project/pypdf/)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/devesht21/Youtube-Summarizer-Groq-Gemma
   cd Youtube-Summarizer-Groq-Gemma

2. Create a virtual environment:

    ```bash
    conda create -p venv python==3.10.0 -y
    conda activate venv

3. Install the required packages:

    ```bash
    pip install -r requirements.txt


4. Run the Streamlit application:

    ```bash
    streamlit run app.py


## Usage

1. Open your web browser and navigate to http://localhost:8501.
2. Enter your Groq API Key in the Sidebar
3. Enter the youtube video or article link link youn want to summarize
4. The application will display the summary generated by the Gemma model based on the video or article provided

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.

1. Fork the repository.
2. Create your feature branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.



