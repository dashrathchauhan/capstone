# CRYPTOCURRENCY PROTOTYPE.

## CERTAIN REQUIREMENTS.


**Activate the virtual environment**
<br>
Make sure you create a virtual python environment using the command given as follows
```
python3 -m venv blockchain-env
```
This is a requirement because any change in the python module in the system can affect the whole code. A virtual environment will not cause any such problem to the system modules.

```
source blockchain-env/bin/activate
```
For windows, make sure to create a seperate virtual enviroment named 'blockchain-env'
To run the code for blockchain environment
```
./blockchain-env/Scripts/activate
```

**Installing all the requirements**
<br>
All the requirements will be updated in the requirements.txt file hence there will not be any requirement of typing numbers of code. Enter the following code in the terminal or command prompt to install the given requirements. Make sure you have pip installed.
```
pip3 install -r requirements.txt
```
For windows , make sure you have Microsoft Visual C++ installed in your computer  (14.0 or higher). Otherwise some modules may not get installed which will cause the application to crash. If you are not able to run the requirements, please type the required module without the version number. This will give you the program with latest version.

For windows installation
```
pip install -r requirements.txt
```

**Running tests**
<br>
Make sure to activate the virtual environment first. Then later perform these tests.
```
python3 -m pytest backend/tests
```
For windows 
```
python -m pytest backend/tests
```

**Running the app and API**
<br>
Make sure to activate the virtual environment first. Then perform these tests.
```
python3 -m backend.app
```
For windows
```
python -m backend.app
```

**Running a peer instance**
<br>
Make sure to activate the virtual environment.
```
export PEER=True && python3 -m backend.app
```

**Run the frontend**
<br>
Make sure to navigate to frontend directory of python-blockchain
Make sure to have react installed or at lease react-scripts.
```
npm run start 
```