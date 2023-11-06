# QHSE-APP Fastapi Backend

Python FastApi using ORM for Database Communication
 
 
## Environment Setup with Virtual ENV
Open terminal to create a virtual environment 

* Create a venv file
```
python -m venv venv
```
* Activate Environment <br>
>Windows
```
.\venv\Scripts\activate  
```
>Mac
```
source ./venv/bin/activate // mac
```


* Install all required Packages
```
pip install -r requirements.txt
```
## Environment Setup with Anaconda

```
conda create -n qhse python=3.9
```
```
conda activate qhse
```
```
pip install -r requirements.txt
```



## Database Dev Setup
To set up a connection with the database, Locate the "API" folder inside the backend directory. Open the "database.py" file in this directory.
In the "database.py" code set "prod=False" and in the "else" section type in your database Url after "SQLALCHEMY_DATABASE_URL=".

Download TablePlus from your browser.
Choose your required database(MySQL,Postgres).
Type in the required fields from the Developer KEY.

![image](https://github.com/10Sirus/qhse/assets/139644976/7a2a5f8b-e095-4714-a062-3729678fdccc)

![image](https://github.com/10Sirus/qhse/assets/139644976/6f71a0bb-f357-4676-a043-35c40b46ec19)

## Run the App

```
uvicorn main:app --reload

```
