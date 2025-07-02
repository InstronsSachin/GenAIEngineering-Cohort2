# install virtual env
		Python -m venv .venv 
# Activate the Virtual Env
.venv\Scripts\activate
# Installing packages using Pip
	pip install <PKG Name>
	
# installing the Pkges using requirement.txt
pip install -r requirements.txt 

# Create the requirements.txt from VENV 
pip freeze > requirements.txt
