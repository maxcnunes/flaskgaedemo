flaskgaedemo
============

Flask and Google App Engine


**Running Python, Virtualenv, Flask and GAE on Windows**

**Install Python**

 1. Install Python http://www.python.org/ftp/python/2.7.2/python-2.7.2.msi
 2. Click in Windows Start button and search by "Edit the system environment" and open
 3. Go to the tab Advanced and click on button "Environment Variables…"
 4. When the Environment Variables window opens, choose Path from the System variables list and click Edit…
 5. Add this `;C:\Python27;C:\Python27\Scripts` at the end of the value and save

**Install setuptools MS Windows installer** (Necessary to install PIP on Windows)

 1. Choose the correct installer for you in this page http://pypi.python.org/pypi/setuptools#files( I used this one: http://pypi.python.org/packages/2.7/s/setuptools/setuptools-0.6c11.win32-py2.7.exe#md5=57e1e64f6b7c7f1d2eddfc9746bbaf20)
 2. Download the installar and Install that


**Install PIP**

 1. Download PIP http://pypi.python.org/pypi/pip#downloads
 2. Extract it to any folder
 3. From that directory, type `python setup.py install`


**Install Virtualenv**

 1. Execute `pip install virtualenv`
 2. Execute this rmdir `c:\virtualenvs` to create a folder to the Virtual Envs
 3. Execute `virtualenv flaskdemo` to create a virtualenv for you project
 4. Active the virtualenv `c:\virtualenvs\flask\scripts\activate`

**Install Google App Engine SDK**

 1. Install the SDK https://developers.google.com/appengine/downloads

**Create the project**

 1. Create a directory for your project
 2. Create the main of your application https://github.com/maxcnunes/flaskgaedemo/blob/master/main.py
 3. Create the configuration of your appliction for Google App Engine https://github.com/maxcnunes/flaskgaedemo/blob/master/app.yaml
 4. Create a file to let GAE initialize your application https://github.com/maxcnunes/flaskgaedemo/blob/master/initialize_gae.py

(Look a example of the code here: https://github.com/maxcnunes/flaskgaedemo )

**Install Flask to run Locally**

 1. Execute `pip install flask`

**Install Flask to run on the GAE**

 1. Download Flask https://github.com/mitsuhiko/flask/archive/0.9.zip and extract the folder flask inside your project
 2. Download Werkzeug https://github.com/mitsuhiko/werkzeug/archive/0.8.3.zip and extract the folder werkzeug inside your project
 3. Download Jinja2 https://github.com/mitsuhiko/jinja2/archive/2.6.zip and extract the folder jinja2 inside your project
 4. Download Simple Json https://github.com/simplejson/simplejson/archive/v3.0.5.zip and extract the folder simplejson inside your project

**Running the application with GAE SDK**

 1. Open Google App Engine Launcher
 2. Add a new application
 3. Run the application
 4. Click in Browse button to open your application on browser
 5. Finally click on Deploy button to deploy your application