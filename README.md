



<!-- GETTING STARTED -->


## Getting Started


### Install git
   #### On Windows
   Download from here and install https://git-scm.com/download/win

#### On Mac
   Check if it is already installed
   ```
   git --version
   ```
   if not then download from here and install https://git-scm.com/download/mac

### Install dvc
   #### Installing using pip
   ```
   pip install dvc
   pip install 'dvc[s3]'
   ```
   For other install option check here https://dvc.org/doc/install

### Install AWS CLI
    Refer to instructions on https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html


## Running code

1. Clone the repo
   ```sh
   $ git clone https://github.com/pallavi-poddar/DVC-demo.git
   $ cd DVC-demo
   ```

2. Install Virtual Environment and install dependencies
   ```sh
   $ python3 -m venv dvc_env
   $ source dvc_env/bin/activate
   $ pip install -r requirements.txt
     
   ```
 3. Execute  the following command to train the classification model
 ```sh
   $ cd DVC-demo/src
   $ python3 predict_cancer.py

 ```


<!-- CONTACT -->
## Contact
Usha Jagannath - [LinkedIn]() - https://www.linkedin.com/in/jagannathan-usha/

Pallavi Poddar Gupta - [LinkedIn]() - https://www.linkedin.com/in/pallavi-poddar-b908b934/



<!-- ACKNOWLEDGMENTS -->
## All acknowledgments

* [DVC](https://dvc.org)
* [Data set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
* [GIT](https://git-scm.com/)

## Links

- Project homepage: https://github.com/pallavi-poddar/dvc-demo-ghc
- Repository: https://github.com/pallavi-poddar/DVC-demo
- Kickstarting your project with GIT and DVC: https://github.com/pallavi-poddar/dvc-demo-ghc
- Cloning an existing project and excuting: https://github.com/pallavi-poddar/dvc-demo-ghc/blob/master/README-getting-data-from-dvc.md
- Changing data set: https://github.com/pallavi-poddar/dvc-demo-ghc




