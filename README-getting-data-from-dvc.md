



<!-- Getting Data using DVC pull -->


### Prerequisites
Git, DVC and AWS CLI should be installed on your machine

```
 pip install git
 pip install dvc
 pip install "dvc[s3]"
```
### Create a new directory to clone the project
```
 mkdir mydvc
 cd mydvc
 git clone https://github.com/pallavi-poddar/DVC-demo.git
```

### Pull Data from DVC
(This step may require you to configure AWS credentials. [Click here for details](https://github.com/pallavi-poddar/dvc-demo-ghc/blob/master/cred/README-cred.md))
```
 DVC pull
```

### Goto root folder and create a python virtual environment and activate it
```
 python3 -m venv dvc_env
 source dvc_env/bin/activate     
```
### Install the requirements
```
 cd DVC_demo
 pip install -r requirements.txt   
```
Incase of error while installing requirements, install the following dependcies one by one
```
 pip install numpy
 pip install pandas
 pip install sklearn
  
```

### Run the code
```
 cd src
 python3 predict_cancer.py 
```

## Links

- Project homepage: https://github.com/pallavi-poddar/dvc-demo-ghc
- Repository: https://github.com/pallavi-poddar/DVC-demo
- Kickstarting your project with GIT and DVC: https://github.com/pallavi-poddar/dvc-demo-ghc
- Cloning an existing project and excuting: https://github.com/pallavi-poddar/dvc-demo-ghc/blob/master/README-getting-data-from-dvc.md






