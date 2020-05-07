# gcs_resumable_uploads

This is a simple python file adapted from [here](https://dev.to/sethmlarson/python-data-streaming-to-google-cloud-storage-with-resumable-uploads-458h) that uploads large file to Google Cloud Storage in a resumable fashion i.e. it robustly handles poor internet connection.

## Usage
- Set-up google cloud storage as described [here](https://cloud.google.com/docs/authentication/getting-started#auth-cloud-implicit-python)

- Install relevant packages listed in the [requirements.txt](requirements.txt)
```bash
pip install -r requirements.txt
```

- Specify bucket name and the list of files to be sent.

- run the [resumable_uploads.py](resumable_uploads.py) script:

```bash
python resumable_uploads.py
```