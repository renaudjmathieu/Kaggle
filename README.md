# :scientist: Kaggle/ML Stuff

## :clipboard: Install and setup stuff

- Visual Studio Code - [download](https://code.visualstudio.com/Download)
- Python - [download](https://www.python.org/)
- Open the Visual Studio Code console and run these commands inside the terminal window to create new env and activate it and install packages : 
    ```	
    cd "Project"
    python3 -m venv venv
    ./venv/bin/Activate.ps1
    pip install --upgrade pip
    pip uninstall -r requirements.txt -y
    pip install -r requirements.txt
    ```

## :scroll: Download stuff

- Download titanic dataset from kaggle
 ```	
    mkdir -p kaggle/input/titanic
    kaggle competitions download -c titanic -p ./kaggle/input/
    unzip kaggle/input/titanic.zip -d ./kaggle/input/titanic
    del ./kaggle/input/titanic.zip
    ```