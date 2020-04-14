# plagiarism

## Python web app to find plagiarism ##

To run locally
```
$ pip install -r requirements.txt
$ python main.py

$ python main.py 
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
To deploy to Google App Engine
```
$ pip install -t lib/ -r requirements.txt ## to install all requiremts so that it'll be moved to GAE
$ gcloud app deploy
```
### The idea for this code base is developed from the following blogs ###
- [here](http://amunategui.github.io/idea-to-pitch/index.html)
 &
- [here](https://opensource.com/article/20/3/open-source-writing-tools)