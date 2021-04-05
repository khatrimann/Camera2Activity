# Camera2Activity

A simple App to stream images to server (without "clicking" any button) for further processing

## Running Server

Run post server using ```flask run --host 0.0.0.0```. For Linux/Unix/MacOS make sure to ```export FLASK_APP=upload_server.py``` and for Windows :- ```set FLASK_APP=upload_server.py```  before running the server and change the URL in ```UploadService.java```
