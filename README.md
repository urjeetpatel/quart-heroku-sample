# quart-heroku-sample
A sample Template on how to use the Quart Framework on Heroku.

## Local Install
1. Use Git to clone from github
    `$ git clone git@github.com:violentmagician/quart-heroku-sample.git`
2. Setup a virutal environment
    ```
    $ python3 -m venv venv
    $ source venv/bin/activate   
    (venv) $ pip install -r requirements.txt
    ```
    
3. Test The app

    ```
    (venv) $ python3 app.py
    ```
    
    or
    
    ```
    (venv) $ export QUART_APP=app:app
    (venv) $ quart
    ```
4. Open Browser to test http://127.0.0.1:5000
