download tokenizers with download.py
copy model files into models/ with "gsutil cp -r gs://aiml-art-data/lyricgen_models/* models/"
copy lyricgenerator-gunicorn.conf to /etc/supervisor/conf.d/
launch with:
sudo supervisorctl update
sudo supervisorctl start gunicorn
