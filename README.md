

# STEPS TO RUN THE APPLICATION

# Clone the repository

    git clone git@github.com:kunalwagh101/Parking_space.git



# Create a virtual environment

**For Linux and macOS**
   
   ```
    cd .\Parking_space\  

    ```

    python3.8 -m venv venv
    source venv/bin/activate

**For Windows**
   ```
    cd .\Parking_space\  

    ```

    pip install virtualenv
    python -m venv venv
    virtualenv venv
    venv/Scripts/activate


# Install the necessary modules

    pip install -r requirements.txt

**If it shows error, run**

    pip install django



# You can also test the app using the test command 
    python manage.py makemigrations
    python manage.py migrate


**generate dummy data using below command**



```
   python manage.py dummy_data 10 

```

**run this command to test the app**


```python
python manage.py test polls

```
    
# Run the application



**run server using below command**



```
    python manage.py runserver

```

# Open the below url on your browser

     http://127.0.0.1:8000/
