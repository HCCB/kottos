# kottos
A RapidSMS project used to develop apps and backends

## Usage

If you have virtualenvwrapper, (_Highly Recommended_), create a virtual environment: `mkvirtualenv kottos`; then you can also set the virtual environment's default directory (to change to when activating) by running `setvirtualenvproject` after changing to the folder you want.  I usually do this after cloning the project.

1.  Clone this repository:
    
    ```
    $ git clone https://github.com/azuer88/kottos.git
    ```

2.  Install dependencies, make sure you are in your virtual environment if you have created one.

    ```
    $ pip install -U -r requirements.txt
    ```

3.  Migrate database

    ```
    $ cd src/rapidsms_dev
    $ python manage.py migrate
    ```

4.  Run server

    ```
    $ python manage.py runserver
    ```
    
