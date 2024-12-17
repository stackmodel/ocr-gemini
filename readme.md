**OCR App Using Gemini Flash**
This is a Streamlit-based web application that allows users to upload an image and extract readable text from it leveraging Google Gemini Flash model.

**Features**
-  📸 Upload an image in JPG, JPEG, or PNG format.
-  🤖 Extract text from the uploaded image using the Google Gemini Flash model.
-  📝 Display the extracted text in a well-organized Markdown format.
-  🖥️ Simple and intuitive interface using Streamlit.


**Setup Instructions**
1. Clone the repository
```
git clone https://github.com/stackmodel/ocr-gemini.git
cd ocr-gemini
```
2. install Dependencies:

    - Make sure you have Python 3.7 or higher installed. Then, create a virtual environment and install the dependencies:
      
      ```
      python -m venv env
      source env/bin/activate  # For Linux/macOS
      .\env\Scripts\activate   # For Windows
      pip install -r requirements.txt
      ```
3. Rename .env.example to .env file and populate the google gemini api key.
   You can obtain your API key from [Google AI Studio](https://aistudio.google.com/app/apikey).

4. Run the app using the following command: ```streamlit run app.py```
   This will launch the app in your browser.
   
![ocr_1](https://github.com/user-attachments/assets/644af73d-7a03-43e5-a411-bb31603b6311)

