# Profiles REST API

## Instructions

* Intall software dependencies:
  * VirtualBox
  * Vagrant
  * Postman

* Initialize a Vagrant server:
    ```
    vagrant init ubuntu/bionic64
    ```

* Run the Vagrant virtual machine and connect to it:
    ```
    vagrant up
    vagrant ssh
    ```

* Create and activate the virtual environment
    ```
    python -m venv ~/env
    source ~/env/bin/activate
    ```

* Install python dependencies:
    ```
    pip install -r requirements.txt
    ```
* Run django project
    ```
    python manage.py migrate
    python manage.py runserver
    ```
