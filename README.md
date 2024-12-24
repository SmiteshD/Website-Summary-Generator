##LangChain: Website Summary Generator 🦜
This is a Streamlit-based web app that generates summaries of website content using the LangChain framework and the Gemma2 model via the Groq API.
Link: https://website-summary-generator-ngpve9ojhre6q3wwtx2crc.streamlit.app/

#Features
Summarization: Generates a concise summary of any website content.
Groq Integration: Leverages the Gemma2-9b-it model through the Groq API.
Custom Prompting: Uses a customizable prompt template to tailor the summary generation.

#Requirements
Python 3.10
Dependencies listed in requirements.txt.

#Installation
Clone the repository:
git clone https://github.com/your-username/website-summary-generator.git  
cd website-summary-generator 

Install dependencies:
pip install -r requirements.txt  

#Run the app:
streamlit run app.py

#Usage
Enter your Groq API Key in the sidebar.
Provide a valid website URL in the text box.
Click Summarize to generate a summary of the content.

#Notes
Ensure you have a valid Groq API key to access the Gemma2 model.
The app uses UnstructuredURLLoader for fetching website content.

#Contributing
Contributions are welcome! Please open an issue or create a pull request.
