# Sangeet Guru

**Sangeet Guru** is a music generation app that allows users to create custom audio tracks based on their input style descriptions. It combines the power of FastAPI for backend processing and Streamlit for a user-friendly frontend interface.
![image](https://github.com/user-attachments/assets/ddfa0799-7725-4547-bf31-4f034f72fe34)

![image](https://github.com/user-attachments/assets/d3e36896-c077-45d1-8c70-270de9363fd4)

## Features

- **Interactive Interface**: Input a music style description and generate a custom audio track.
- **Example Prompts**: Provides example music styles for quick experimentation.
- **Clean Design**: Features a minimalistic logo and a simple layout for easy use.

## Installation

To get started with Sangeet Guru, follow these steps:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/sangeet-guru.git
    cd sangeet-guru
    ```

2. **Set Up the Environment**

    Create a virtual environment and install the required packages:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3. **Run the Application**

    You can run the FastAPI server or the Streamlit app.

    - To start the FastAPI server:

      ```bash
      uvicorn main:app --reload
      ```

    - To start the Streamlit app:

      ```bash
      streamlit run main.py
      ```

## Usage

- **Streamlit Interface**: Open the Streamlit app in your browser. Enter a music style description in the text input box and click "Generate" to create a custom audio track. You can also select from example prompts to see different styles in action.

- **FastAPI Endpoint**: You can use the FastAPI endpoint to programmatically generate audio tracks by sending a POST request to `/generate-audio/` with a JSON body containing the music style description.

## Example Prompts

- "80s pop track with bassy drums and synth"
- "Earthy tones, environmentally conscious, ukulele-infused"
- "90s rock song with loud guitars and heavy drums"
- "Heartful EDM with beautiful synths and chords"
- "Classical Indian raga with sitar and tabla"

## Requirements

- Python 3.8 or higher
- FastAPI
- Streamlit
- Uvicorn
- Pydantic
- Other dependencies listed in `requirements.txt`

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with any improvements or bug fixes.


---

*Made with ❤️ by Tabrez and openvino*

