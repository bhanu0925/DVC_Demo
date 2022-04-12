# DVC_Demo
DVC Basic setup demo demonstrates
1. inirializing dvc repository
2. setting up remote storage like gdrive
3. verstioning/configuring data

# Create environment and activate


1.	Git initiatize \
    git init
2.	Dvc initialize it creates few more files like dvcignore, config,temp folder – \
    dvc init
3.	Add data to the dvc to track it. \
    dvc add data/hour.csv \
    git add 'data\.gitignore' 'data\hour.csv.dvc'
