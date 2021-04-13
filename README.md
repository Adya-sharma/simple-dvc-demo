create env

```bash
conda create -n mlo python=3.8 -y
```

activate env
```bash
conda activate mlo
```

created requirements.txt

install the requirements
```bash
pip install -r requirements.txt
```

download the dataset from
https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"


