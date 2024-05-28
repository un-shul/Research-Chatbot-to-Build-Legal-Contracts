I implemented a research chatbot designed to assist users in generating legal contracts based on their input. This project utilized the Groq API for language processing and the Serper API for document retrieval. The chatbot was deployed as a web application using Flask and styled with Tailwind CSS. Users can input their requirements, and the chatbot generates a .docx file of the contract, which is then available for download.

Technologies Used:

APIs: Groq API, Serper API
Frameworks: Flask, Tailwind CSS
Libraries: python-docx


Please follow the steps below to run the research chatbot:

1. Open a terminal and install the required packages by running:
   ```bash
   pip install Flask requests python-docx
   ```

2. Navigate to the directory containing the `app.py` file:
   ```bash
   cd /path/to/your/project/my_flask_app
   ```

3. Execute the application:
   ```bash
   python app.py
   ```

4. Open a web browser and go to:
   ```plaintext
   http://127.0.0.1:5000
   ```

