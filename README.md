When you clone the project:

# this is for initialisation
cd FrontEnd
npm install
cd ../BackEnd
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt

# when you add new packages for the backend do this:
pip freeze > requirements.txt