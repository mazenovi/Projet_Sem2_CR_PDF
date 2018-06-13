## Install swig

```
sudo apt install swig
```

## Install python packages on virtual env

```
virtualenv ~/wc -p /usr/bin/python3
source ~/wc/bin/activate
pip install -r requirements.txt
```

## install as comman line in linux system

```
sudo cp PDF_to_WordCloud.py /usr/local/bin/pdf2wc
sudo chmod -R 755 /usr/local/bin/pdf2wc
```

use it!

```
pdf2wc
```
