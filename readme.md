create env

......bash

 conda create -n wineque python=3.7 -y

 activate env
 ........bash

 conda activate wineque

 create requirements.txt
 .............bash
 pip install -r requirements.txt
 .....

 Download the dataset winequality.csvconda
.....bash
 git init
 dvc init
 ....bash
 dvc add data_given/winequality.csv
....bash
 git add .
....bash
 git commit -m "first commit"
 
 online updates for readme
 ....bash
 git add . && git commit -m "update readme.md" 
 ....bash
 $ git branch _M main
 ....bash
 $ git push origin main




