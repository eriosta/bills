# OpenAI Usage Tracker

This is a Streamlit app that tracks your OpenAI usage and billing live.

## Installation

Clone the repository and navigate to the directory:

```bash
git clone https://github.com/yourusername/openai-usage-tracker.git
cd openai-usage-tracker
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Configuration

Create a `.env` file in the root directory of the project and add your OpenAI API Key and Streamlit Secret Key:

```bash
OPENAI_API_KEY=your_openai_api_key
STREAMLIT_SECRET_KEY=your_streamlit_secret_key
```

## Usage

Run the Streamlit app:

```bash
streamlit run app.py
```

The app will be live at `http://localhost:8501`.

## Files

- `requirements.txt`: Contains the required python packages.
- `config.py`: Loads the environment variables.
- `openai_tracker.py`: Contains the `OpenAITracker` class that fetches the usage data from OpenAI.
- `app.py`: The main Streamlit app.
- `.gitignore`: Specifies which files and directories Git should ignore.
- `README.md`: This file, containing information about the project and instructions on how to run it.

## License

This project is licensed under the terms of the MIT license.
