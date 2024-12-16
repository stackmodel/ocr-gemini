OCR App Using Gemini Flash
This is a Streamlit-based web application that allows users to upload an image and extract readable text from it using the Google Gemini Flash model.

Features
Upload an image in jpg, jpeg, or png format.
Extracts text from the uploaded image using the Google Gemini Flash model.
Displays the extracted text in a well-organized Markdown format.
Simple and intuitive interface using Streamlit.

You can install the required dependencies using pip:

pip install -r requirements.txt

Setup Instructions
1. Clone the repository

git clone 
cd ocr-gemini

2. Create a .env file
The app requires a Google API key to access the Google Gemini API. Store the API key in a .env file in the root of the project. The .env file should look like this:

GOOGLE_API_KEY=your-google-api-key-here
You can obtain your API key from Google Cloud.

3. Run the app
To start the app, use the following command:

streamlit run app.py
This will launch the app in your browser.

