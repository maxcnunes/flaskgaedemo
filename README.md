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

 1. Excute `pip install virtualenv`
 2. Execute this rmdir `c:\virtualenvs` to create a folder to the Virtual Envs
 3. Execute `virtualenv flaskdemo` to create a virtualenv for you project
 4. Active the virtualenv `c:\virtualenvs\flask\scripts\activate`

**Install Google App Engine SDK**

 1. Install the SDK https://developers.google.com/appengine/downloads
 2. After install, already let opened the Google App Engine Launcher
 3. 