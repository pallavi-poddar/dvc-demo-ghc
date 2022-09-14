



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
   (This step may require you to configure AWS creentials)

   ```
   DVC pull
   ```

### Create a python virtual environment and activate it
   ```
   $ python3 -m venv dvc_env
   $ source dvc_env/bin/activate     
   ```
 ### Install the requirements
 ```
   pip install -r requirements.txt   
 ```

  ### Run the code
 ```
      cd src
      python3 predict_cancer.py 
 ```

## Links

Even though this information can be found inside the project on machine-readable
format like in a .json file, it's good to include a summary of most useful
links to humans using your project. You can include links like:

- Project homepage: https://github.com/pallavi-poddar/dvc-demo-ghc
- Repository: https://github.com/pallavi-poddar/DVC-demo
- Kickstarting your project with GIT and DVC: https://github.com/pallavi-poddar/dvc-demo-ghc
- Cloning an existing project and excuting: https://github.com/pallavi-poddar/dvc-demo-ghc
- Changing data set: https://github.com/pallavi-poddar/dvc-demo-ghc
- Kickstarting your project: https://github.com/pallavi-poddar/dvc-demo-ghc




