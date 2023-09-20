# ChitChat Project Readme

ChitChat is a Python-powered Social Network.

## Installation

1. cd into backend folder
    cd backend

2. create virtual environment
    ### Installing virtualenv
    ```pip install virtualenv```

    ### Creating virtual environment
    ```python -m venv venv```

    ### Activating the virtual environment
    ```source venv/bin/activate```

3. Install dependencies from the requirements text file.
```pip install -r requirements.txt```

## Usage
To run this project do the following:

1. Make migrations:<br>
    ```python manage.py makemigrations```

2. Run migrations:
```python manage.py migrate```

3. Create super user:
```python manage.py createsuperuser```

4. Run the server:
```python manage.py runserver```



## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)