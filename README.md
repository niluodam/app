<pre>
  virtual try-on web app
</pre>
<pre>
1) Download this repository
  
2) set this variables 
    ~ export ROOT_DIR="/path/to/app"
    ~ export SECRET_KEY="some_secret_text"
    ~ export FLASK_APP=wsgi.py
  
3) install using requirements file  
    ~ cd $ROOT_DIR
    ~ pip install -r requirements.txt

4) Download model files
~ cd $ROOT_DIR/src/cmate/segmentation/models
~ sh get_models.sh


5) Run Flask App
  ~ cd $ROOT_DIR/src/flask_app/
  ~ flask run --host=127.0.0.1 --port=8080 --debug

6) web-app
  open browser & paste 
  http://127.0.0.1:8080
</pre>
