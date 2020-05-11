Tuter


Installation guide:

1. Install miniconda if you dont already have it from
Link - https://docs.conda.io/en/latest/miniconda.html
Chose Python 3.7

2. Open command prompt and create an environment using
$ conda create --name anyNameForEnvironment python=3.7

3. Once the environment is created successfully, activate 
it using $ conda activate tuterApp

4. Go to the file where you downloaded the project and run
$ pip install -r requirements.txt


Run the app:

5. To start the application server, type
$ python manage.py runserver

6. Copy the link provided in the terminal after the
server sucessfully starts running and paste it in any 
browser and add /tuterAPP at the end in address bar to run the app.
e.g. http://127.0.0.1:8000/tuterApp/

7. You can navigate the app normally using the browser.
However, if you want to stop, come back to the terminal and 
press Ctrl + C to stop server.

8. To start the server again at any time repeat step 5 and 6.