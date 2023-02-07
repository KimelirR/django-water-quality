# Water-Quality Indicators Monitoring Tool

<!--Unordered lists-->
* Clone this repository to your computer.
    ```
    git clone https://github.com/KimelirR/django-water-quality.git
    ```
* Change file directory
    ```
     cd django-water-quality
    ```

* Create .env file 
    ```python
    pip install virtualenv
    ```
    
* We will name our virtual environment as **_env_**
   ```python
    python3 -m venv env
   ```

* Activate virtual environment on linux
   ```
    source env/bin/activate
   ```
* Install required dependencies through 
  ```python
   pip install -r requirements.txt
  ```
* Migrate databases
   ```python
    python3 manage.py makemigrations
   ```
   ```python
    python3 manage.py migrate
   ```

 > <b>Note!</b>
  1. Ensure you create SuperUser to manage django admin
  ```python
   python3 manage.py createsuperuser
  ```

> <b>Lastly!  Run your django app </b>

* All the functions and classes are inside src folder.

    ```python
     python3 manage.py runserver
    ```
  
* In your browser go to address below 
     [localhost](http://127.0.0.1:8000) 

## Note this and follow the procedure below to get your service account instructions.


* [EarthEngine](https://developers.google.com/earth-engine/cloud/earthengine_cloud_project_setup#create-a-cloud-project "Set service account")

* Check as well this 
[Register For Earth Engine](https://earthengine.google.com/ "Register")

* Register social account email
[Social-account](https://signup.earthengine.google.com/#!/service_accounts "Register social account email")


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

> On Ubuntu you need this to install mysqlclient
```
sudo apt-get install python3-dev default-libmysqlclient-dev build-essential
```

## Improved codes on ** on geefunctions.py which is on charts,maps and query **

```python
 scopes=ee.oauth.SCOPES.append(google_api)) 

 credentials = ee.ServiceAccountCredentials(email=service_account, key_file=privateKey)


 from 

 scopes=ee.oauth.SCOPE + ' https://www.googleapis.com/auth/drive ')

 credentials = ee.ServiceAccountCredentials(service_account, privateKey)


```

 
