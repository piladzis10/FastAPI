1) Install dependencies
pip install fastapi uvicorn
2) Initializing server 
uvicorn main:app --reload
* main the name of the file without extension (.py)
* app is the name given in the main.py file
* --reload tells the webserver to update each time there is change to python file