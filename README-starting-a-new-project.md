


<!-- Starting a new project -->
## Creating a new ML project from the scratch with focus on code and data versioning


### Prerequisites
Git and DVC should be installed on your machine

```
 pip install git
 pip install dvc
```
### Create a new directory
```
 mkdir ghc-demo
 cd ghc-demo
 mkdir src
```

### Create or copy model code
```
 cd src
 cp ../../DVC-demo/src/predict_cancer.py .
```
### Initialize git 
```
 cd ../
 git init
```

### Add the files to git and commit 
```
 git add predict_cancer.py
 git commit -m "initial commit"
```
### Create a new repo ghc-demo on git
![repo](https://github.com/pallavi-poddar/dvc-demo-ghc/blob/master/images/Screenshot%202022-09-22%20at%203.57.30%20PM.png)
### Push the code to git
```
 git remote add origin https://github-com/<account-name>/ghc-demo.git
 git branch -M main
 git push -u origin main 
```
You may be asked for authentication while pushing your code to git which may require a personal access token(PAT). This is link to generate PAT
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

### Create data folder and add sample data
```
 mkdir dataset
 cd dataset
 cp ../../cancer-data.txt .
 ls
```

###  Create a DVC remote on local
```
 cd <root-folder>
 mkdir dvc_remote
```
### Initialize dvc
```
 dvc init
 
```

### Add a DVC remote
```
 dvc remote add -d remote_local <absolute path>/dvc_remote
 
```
### Add sample data set to dvc
```
 dvc add cancer-data.txt
 
```

### Push the newly generated metafiles to git
```
 git status
 git add .
 git commit -m "adding data files to dvc"
 git push
```


### Push the sample data to dvc
```
 dvc push
```

## Links

- Project homepage: https://github.com/pallavi-poddar/dvc-demo-ghc
- Repository: https://github.com/pallavi-poddar/DVC-demo
- Cloning an existing project and executing: https://github.com/pallavi-poddar/dvc-demo-ghc/blob/master/README-getting-data-from-dvc.md
- Getting started with a new project: https://github.com/pallavi-poddar/dvc-demo-ghc/blob/master/README-getting-data-from-dvc.md





