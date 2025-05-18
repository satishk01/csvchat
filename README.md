create a virtial env

python3 -m venv demo
cd demo
source ~/demo/bin/activate

in this folder copy the files
requirements.txt
streamlit_app.py
csv_data_insights.py
.env 

Install all required packages

pip install -r requirements.txt

Start the application
streamlit run streamlit_app.py

using the public IP address  in teh chrome browser

http://<<publicip add>>:8501 to view the app in browser
