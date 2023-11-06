# QHSE-APP Fastapi Backend

Python FastApi using ORM for Database Communication
 
 
## Environment Setup with Virtual ENV

```
#Create venv file
python3 -m venv env
```
```
#Activate Environment

.\venv\Scripts\activate  //windows

source ./venv/bin/activate // mac
```
A![Screenshot (27)](https://github.com/10Sirus/qhse/assets/139644976/44a3c514-8ccb-4d41-8aad-dcd4cbcaa6b0)
```
pip install --upgrade pip
```
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

## Database Setup

Create Database With Name of 'mydb' or your choice (then change db name in config.py)

lso setup config.db according to your Database credentials

## Run the App

```
uvicorn main:app --reload

```
