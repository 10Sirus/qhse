# QHSE-APP Fastapi Backend

Python FastApi using ORM for Database Communication
 
 
## Environment Setup with Virtual ENV
### Open terminal and create a virtual environment 

* Create a venv file
```
python3 -m venv env
```
* Activate Environment
  a. Windows
```
.\venv\Scripts\activate  // windows
```
  b. Mac
```
source ./venv/bin/activate // mac
```
![Screenshot (27)](https://github.com/10Sirus/qhse/assets/139644976/44a3c514-8ccb-4d41-8aad-dcd4cbcaa6b0)

*Install all the required filea
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

In the database.py file set "prod=False" and in the "else" section type in your database Url after "SQLALCHEMY_DATABASE_URL=".

Download TablePlus from your browser.
Choose your required database(MySQL,Postgres).
Type in the required fields from the KEY.

![image](https://github.com/10Sirus/qhse/assets/139644976/7a2a5f8b-e095-4714-a062-3729678fdccc)

![image](https://github.com/10Sirus/qhse/assets/139644976/6f71a0bb-f357-4676-a043-35c40b46ec19)

## Run the App

```
uvicorn main:app --reload

```
