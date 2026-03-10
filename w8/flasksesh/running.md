Start local server with

```
FLASK_ENV=development FLASK_APP=app.py flask run
```

or

```
python (or python3) app.py
```

Then in a new terminal run:

```
curl -X POST -F "file=@kitten.jpg" http://127.0.0.1:5000/predict
```

Which sends a image file to the "predict" endpoint and logs what it is
