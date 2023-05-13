# Google Cloud Functions Project
## Project to learn all about Google Cloud Functions
To start a new project in Google Cloud you can go to the [Firebase Console](https://console.firebase.google.com) or crate it from the [Google Cloud Platform Console](https://console.cloud.google.com)

## Creating a virtual environment
First we have to install 'python-venv' with the following command
```commandline
python -m venv google_cloud_project
```
Then we created a virtual by executing the following command
```
python -m venv venv
```
Now the virtual environment is activated.
```
.\venv\Scripts\Activate
```
Then we added the file requirements.txt

But first I had to change the execution policy. I could check it with:
```commandline
get-ExecutionPolicy -List
```
and then change it in this instance, with:
```commandline
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```
Ideally I would have used:
```commandline
pip install --use-pep517 -r  requirements.txt
```
To ensure that all the requirements were installed.
I checked the packages by going"File,Settings,Project:Google_Cloud_Project" and then selecting Python Interpreter.
The Wheel package didn't install and that had to be pip installed.
