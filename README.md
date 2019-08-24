[GCP Flask Docs](https://cloud.google.com/appengine/docs/standard/python/getting-started/python-standard-env)

### Adding or updating requirements ###

After adding/upgrading the requirement in the virtualenv via pip:
* `pip freeze > requirements.txt`
* `pip install -t lib -r requirements.txt` - This updates it in the libraries in /lib, to be uploaded to AppEngine

### Deployment ###

`gcloud app deploy`
