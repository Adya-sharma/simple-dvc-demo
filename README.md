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

```bash
git init
```

```bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```

```bash
git add .
```

```bash
git commit -m "first commit"
```


oneline update for readme.md
```bash
git add . && git commit -m "update Readme.md"
```

```bash
git remote add origin https://github.com/Adya-sharma/simple-dvc-demo.git
git branch -M main
git push origin main
```