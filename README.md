# Synchronize
Simple project, that allow you manage your files from different cloud storages (Dropbox, Google Drive, etc.)
After login, you will be able to manage your files from all clouds on one screen. Also, you can delete and add new files.

To create and run virtual environment:
```
virtualenv venvname --no-site-packages
source venvname/bin/activate
```
To run locally, just execute:
```
cd synchronize
pip install -r requirements.txt
make init
make run
```
