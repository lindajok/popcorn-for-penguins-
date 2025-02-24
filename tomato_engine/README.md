# Tomato Engine Commands

The virtual environment `tomato` is already installed (see folder tomato), you just have to activate the environment:

```
. tomato/bin/activate
```

There are all needed libraries installed in the `tomato` virtual environment. You don't have to download anything (except for Python3).

## Run Tomato Engine in Development Mode

### Set the following environment variables:

Show flask which file to run:

```
export FLASK_APP=search_engine.py
```

Enable development environment to activate interactive debugger and reloader:

```
export FLASK_ENV=development
```

Set the port in which to run the application, e.g.:

```
export FLASK_RUN_PORT=8000
```

Run the app:

```
flask run
```

Go to `localhost:8000/search` in your browser to see the website.

To leave the virtual environment:

```
deactivate
```


