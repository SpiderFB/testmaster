This project is to build a Framework where a user will be able to use a Gherkin formated feature file to generate TestScripts.

(Windows Guide) -->

Check Python and pip versions:
python --version
python -m pip --version

Create a Virtual Environment(Named -> .venv):
python -m venv .venv 

Activate the Virtual Environment(Root folder where the Environment was created):
.venv\Scripts\Activate

Upgrade the PIP(Python’s package installer - tool)
python -m pip install --upgrade pip

Install the dependencies in the Virtual Environment using the requirements.txt file
pip install -r requirements.txt

Start the server
python .\manage.py runserver