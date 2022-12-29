# flask
from flask import Flask

app=Flask(__name__)

@app.route('/')

def home():

    return 'HI this is Raj'

if __name__=="__main__"
    app.run()
