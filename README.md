# flask-app-1
Basic web app by using Flask in Python

I used the PyCharm software (+interpreter) IDE on Windows 10 platform. 

Here, Flask framework is used to make a web app. I am demonstrating two functions in this ->
1) Hello "Name" with display for random quote and an image

Run the hello.py python file.

`$ python hello.py`
And then hit on the browser - `127.0.0.1:80/hello/kshiti`

![Output](https://github.com/kmurudi/flask-app-1/blob/master/flask1.PNG)

It uses the template - `test.html`

2) File uploader app 


`$ python uploader.py`

Hit on the browser - `127.0.0.1/upload` ->

![File upload Output](https://github.com/kmurudi/flask-app-1/blob/master/flask2.PNG)

After hitting 'submit' button you shall see ->
"File uploaded successfully!"


It uses the template - `upload.html` 

**NOTE -> If you intend to run files with same port numbers, then run second file only after killing the process running on that port (e.g. 5000) due to first file, else your URL for file upload will not work**


