# TASK-1 Text-to-Speech Web Application
This project is a simple Text-to-Speech Converter built using Flask and gTTS (Google Text-to-Speech). It takes user input in the form of text and generates a downloadable audio file. The user can customize the voice gender, speech rate, and volume.

Features:
Text-to-Speech Conversion: Convert text input into speech using the Google Text-to-Speech API.
Voice Gender Selection: Choose between male and female voices.
Speech Rate: Choose between normal and slow speech rates.
Volume Control: Adjust the speech volume with a slider.
Responsive Interface: Fully responsive design that works on desktop and mobile devices.
Audio Playback: Listen to the generated speech directly on the page.

Technologies Used:
Python (Flask framework for the web server)
gTTS (Google Text-to-Speech) for generating speech from text
HTML, CSS, JavaScript for the front-end interface

How to Run the Application Locally
Clone the repository:

bash
git clone https://github.com/your-username/text-to-speech-flask.git
cd text-to-speech-flask
Create a virtual environment (Optional but recommended):

bash
python3 -m venv venv
Activate the virtual environment:

On Windows:

bash
.\venv\Scripts\activate
On macOS/Linux:

bash
source venv/bin/activate
Install dependencies:

Install the required libraries via pip:

bash
'''pip install -r requirements.txt''''
Run the application:

bash
python app.py
Access the application:

Open your browser and go to http://127.0.0.1:5000/.
File Structure:
graphql
.
├── app.py               # Main Flask application
├── speech.py            # Logic for generating speech using gTTS
├── templates
│   └── index.html       # The main HTML page with form and audio playback
├── static
│   └── audio           # Directory to store generated audio files
├── requirements.txt     # List of required Python packages
└── README.md            # This file


Dependencies:
Flask: Web framework for Python
gTTS: Google Text-to-Speech library
Werkzeug (comes with Flask for file handling)
To install the required dependencies, run the following:

bash
pip install flask gtts
