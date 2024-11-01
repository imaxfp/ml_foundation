### ML Foundation

Main ML algorithms and trends

#### Setup env:

- python3 -m venv ./venv
- source ./venv/bin/activate
- pip cache purge
- pip3 install -r requirements.txt

#### !Check for Dependency Conflicts
- pip install pipdeptree
- pipdeptree

#### for the large files support
git lfs install
git lfs ls-files
git add path/to/your/largefile.zip
git commit -m "Track large file with LFS"
git push origin main

```
Make sure to update your transformers installation via pip install --upgrade transformers.
```