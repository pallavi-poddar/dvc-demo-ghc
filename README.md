<!-- GETTING STARTED -->

## Getting Started

### Install git

#### On Windows
   Download and Install git on Windows
   https://git-scm.com/download/win

#### On Mac
   Check if git is already installed
   ```
   git --version
   ```
   if not, download git client and install on your Mac 
   https://git-scm.com/download/mac

### Install DVC
   #### Installation done using pip
   ```
   pip install dvc
   pip install 'dvc[s3]'
   ```
   For other installation options, check out the link below 
   https://dvc.org/doc/install

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
 3. Execute the following command to train the classification model - Breast cancer detection public dataset
 ```sh
   $ cd DVC-demo/src
   $ python3 predict_cancer.py

 ```


<!-- CONTACT -->
## Contact Info
Usha Jagannathan - [LinkedIn]() - https://www.linkedin.com/in/jagannathan-usha/

Pallavi Poddar Gupta - [LinkedIn]() - https://www.linkedin.com/in/pallavi-poddar-b908b934/


<!-- ACKNOWLEDGMENTS -->
## Credits

* [DVC](https://dvc.org)
* [Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
* [GIT](https://git-scm.com/)

## Links

- Project homepage: https://github.com/pallavi-poddar/dvc-demo-ghc
- Repository: https://github.com/pallavi-poddar/DVC-demo
- Kickstarting your project with GIT and DVC: https://github.com/pallavi-poddar/dvc-demo-ghc
- Cloning an existing project and executing: https://github.com/pallavi-poddar/dvc-demo-ghc/blob/master/README-getting-data-from-dvc.md
- Changing data set: https://github.com/pallavi-poddar/dvc-demo-ghc




