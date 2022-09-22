



<!-- Starting a new project -->


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
 git init
```

### Add the files to git and commit 
```
 git add predict_cancer.py
 git commit -m "initial commit"
```
### Create a new repo ghc-demo on git

### Push the code to git
```
 git remote add origin https://github-com/<account-name>/ghc-demo.git
 git branch -M main
 git push -u origin main 
```
### Create data folder and add sample data to oy
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
### initialize dvc and add data files to it
```
 dvc init
 
```

### Push the code to git
```
 git remote add origin https://github-com/<account-name>/ghc-demo.git
 git branch -M main
 git push -u origin main
```

### Push the code to git
```
 git remote add origin https://github-com/<account-name>/ghc-demo.git
 git branch -M main
 git push -u origin main
```
## Links

- Project homepage: https://github.com/pallavi-poddar/dvc-demo-ghc
- Repository: https://github.com/pallavi-poddar/DVC-demo
- Kickstarting your project with GIT and DVC: https://github.com/pallavi-poddar/dvc-demo-ghc
- Cloning an existing project and excuting: https://github.com/pallavi-poddar/dvc-demo-ghc/blob/master/README-getting-data-from-dvc.md






