## Commands For DVC

- pip install dvc
- git init
- dvc init
- dvc add data/hour.csv
- git add data/hour.csv.dvc data/.gitignore

### Configure Remote Drive

- pip install dvc[gdrive]
- dvc remote add -d dvc_remote gdrive://[Folder ID]
- git commit .dvc/config -m "config remote storage"
- dvc push (authentication required)
