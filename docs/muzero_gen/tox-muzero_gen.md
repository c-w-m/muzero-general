```shell
muzero_gen37 create: /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero-general/.tox/muzero_gen37
muzero_gen37 installdeps: -r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero-general/requirements.txt
muzero_gen37 installed: absl-py==1.0.0,attrs==21.2.0,bayesian-optimization==1.2.0,cachetools==4.2.4,certifi==2021.10.8,charset-normalizer==2.0.8,click==8.0.3,cloudpickle==2.0.0,cma==3.1.0,cycler==0.11.0,Deprecated==1.2.13,filelock==3.4.0,fonttools==4.28.2,google-auth==2.3.3,google-auth-oauthlib==0.4.6,grpcio==1.42.0,gym==0.21.0,idna==3.3,importlib-metadata==4.8.2,importlib-resources==5.4.0,joblib==1.1.0,jsonschema==4.2.1,kiwisolver==1.3.2,Markdown==3.3.6,matplotlib==3.5.0,msgpack==1.0.3,nevergrad==0.4.3.post9,numpy==1.21.4,oauthlib==3.1.1,packaging==21.3,pandas==1.3.4,Pillow==8.4.0,protobuf==3.19.1,pyasn1==0.4.8,pyasn1-modules==0.2.8,pyparsing==3.0.6,pyrsistent==0.18.0,python-dateutil==2.8.2,pytz==2021.3,PyYAML==6.0,ray==1.8.0,redis==4.0.2,requests==2.26.0,requests-oauthlib==1.3.0,rsa==4.8,scikit-learn==1.0.1,scipy==1.7.3,seaborn==0.11.2,setuptools-scm==6.3.2,six==1.16.0,tensorboard==2.7.0,tensorboard-data-server==0.6.1,tensorboard-plugin-wit==1.8.0,threadpoolctl==3.0.0,tomli==1.2.2,torch==1.10.0,typing_extensions==4.0.0,urllib3==1.26.7,Werkzeug==2.0.2,wrapt==1.13.3,zipp==3.6.0
muzero_gen37 run-test-pre: PYTHONHASHSEED='3264757519'
muzero_gen37 run-test: commands[0] | python -c 'print((80*"=")+"\n"+"python3.7_testenv:muzero_gen"+"\n"+(80*"="))'
================================================================================
python3.7_testenv:muzero_gen
================================================================================
muzero_gen37 run-test: commands[1] | python -c 'print((80*"~")+"\n"+"pip install --upgrade pip setuptools wheel"+"\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip install --upgrade pip setuptools wheel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero_gen37 run-test: commands[2] | pip install --upgrade pip
Requirement already satisfied: pip in ./.tox/muzero_gen37/lib/python3.7/site-packages (21.3.1)
muzero_gen37 run-test: commands[3] | pip install --upgrade setuptools
Requirement already satisfied: setuptools in ./.tox/muzero_gen37/lib/python3.7/site-packages (58.3.0)
Collecting setuptools
  Downloading setuptools-59.3.0-py3-none-any.whl (952 kB)
Installing collected packages: setuptools
  Attempting uninstall: setuptools
    Found existing installation: setuptools 58.3.0
    Uninstalling setuptools-58.3.0:
      Successfully uninstalled setuptools-58.3.0
Successfully installed setuptools-59.3.0
muzero_gen37 run-test: commands[4] | pip install --upgrade wheel
Requirement already satisfied: wheel in ./.tox/muzero_gen37/lib/python3.7/site-packages (0.37.0)
muzero_gen37 run-test: commands[5] | python -c 'print((80*"~")+"\n"+"python -m pip list --format=columns"+"\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
python -m pip list --format=columns
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero_gen37 run-test: commands[6] | python -m pip list --format=columns
Package                 Version
----------------------- -----------
absl-py                 1.0.0
attrs                   21.2.0
bayesian-optimization   1.2.0
cachetools              4.2.4
certifi                 2021.10.8
charset-normalizer      2.0.8
click                   8.0.3
cloudpickle             2.0.0
cma                     3.1.0
cycler                  0.11.0
Deprecated              1.2.13
filelock                3.4.0
fonttools               4.28.2
google-auth             2.3.3
google-auth-oauthlib    0.4.6
grpcio                  1.42.0
gym                     0.21.0
idna                    3.3
importlib-metadata      4.8.2
importlib-resources     5.4.0
joblib                  1.1.0
jsonschema              4.2.1
kiwisolver              1.3.2
Markdown                3.3.6
matplotlib              3.5.0
msgpack                 1.0.3
nevergrad               0.4.3.post9
numpy                   1.21.4
oauthlib                3.1.1
packaging               21.3
pandas                  1.3.4
Pillow                  8.4.0
pip                     21.3.1
protobuf                3.19.1
pyasn1                  0.4.8
pyasn1-modules          0.2.8
pyparsing               3.0.6
pyrsistent              0.18.0
python-dateutil         2.8.2
pytz                    2021.3
PyYAML                  6.0
ray                     1.8.0
redis                   4.0.2
requests                2.26.0
requests-oauthlib       1.3.0
rsa                     4.8
scikit-learn            1.0.1
scipy                   1.7.3
seaborn                 0.11.2
setuptools              59.3.0
setuptools-scm          6.3.2
six                     1.16.0
tensorboard             2.7.0
tensorboard-data-server 0.6.1
tensorboard-plugin-wit  1.8.0
threadpoolctl           3.0.0
tomli                   1.2.2
torch                   1.10.0
typing_extensions       4.0.0
urllib3                 1.26.7
Werkzeug                2.0.2
wheel                   0.37.0
wrapt                   1.13.3
zipp                    3.6.0
muzero_gen37 run-test: commands[7] | python -c 'print((80*"~")+"\n"+"pip freeze\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip freeze
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero_gen37 run-test: commands[8] | pip freeze
absl-py==1.0.0
attrs==21.2.0
bayesian-optimization==1.2.0
cachetools==4.2.4
certifi==2021.10.8
charset-normalizer==2.0.8
click==8.0.3
cloudpickle==2.0.0
cma==3.1.0
cycler==0.11.0
Deprecated==1.2.13
filelock==3.4.0
fonttools==4.28.2
google-auth==2.3.3
google-auth-oauthlib==0.4.6
grpcio==1.42.0
gym==0.21.0
idna==3.3
importlib-metadata==4.8.2
importlib-resources==5.4.0
joblib==1.1.0
jsonschema==4.2.1
kiwisolver==1.3.2
Markdown==3.3.6
matplotlib==3.5.0
msgpack==1.0.3
nevergrad==0.4.3.post9
numpy==1.21.4
oauthlib==3.1.1
packaging==21.3
pandas==1.3.4
Pillow==8.4.0
protobuf==3.19.1
pyasn1==0.4.8
pyasn1-modules==0.2.8
pyparsing==3.0.6
pyrsistent==0.18.0
python-dateutil==2.8.2
pytz==2021.3
PyYAML==6.0
ray==1.8.0
redis==4.0.2
requests==2.26.0
requests-oauthlib==1.3.0
rsa==4.8
scikit-learn==1.0.1
scipy==1.7.3
seaborn==0.11.2
setuptools-scm==6.3.2
six==1.16.0
tensorboard==2.7.0
tensorboard-data-server==0.6.1
tensorboard-plugin-wit==1.8.0
threadpoolctl==3.0.0
tomli==1.2.2
torch==1.10.0
typing_extensions==4.0.0
urllib3==1.26.7
Werkzeug==2.0.2
wrapt==1.13.3
zipp==3.6.0
muzero_gen37 run-test: commands[9] | python -c 'print((80*"~")+"\n"+"End-of-Commands\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
End-of-Commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero_gen38 create: /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero-general/.tox/muzero_gen38
muzero_gen38 installdeps: -r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero-general/requirements.txt
muzero_gen38 installed: absl-py==1.0.0,attrs==21.2.0,bayesian-optimization==1.2.0,cachetools==4.2.4,certifi==2021.10.8,charset-normalizer==2.0.8,click==8.0.3,cloudpickle==2.0.0,cma==3.1.0,cycler==0.11.0,Deprecated==1.2.13,filelock==3.4.0,fonttools==4.28.2,google-auth==2.3.3,google-auth-oauthlib==0.4.6,grpcio==1.42.0,gym==0.21.0,idna==3.3,importlib-metadata==4.8.2,importlib-resources==5.4.0,joblib==1.1.0,jsonschema==4.2.1,kiwisolver==1.3.2,Markdown==3.3.6,matplotlib==3.5.0,msgpack==1.0.3,nevergrad==0.4.3.post9,numpy==1.21.4,oauthlib==3.1.1,packaging==21.3,pandas==1.3.4,Pillow==8.4.0,protobuf==3.19.1,pyasn1==0.4.8,pyasn1-modules==0.2.8,pyparsing==3.0.6,pyrsistent==0.18.0,python-dateutil==2.8.2,pytz==2021.3,PyYAML==6.0,ray==1.8.0,redis==4.0.2,requests==2.26.0,requests-oauthlib==1.3.0,rsa==4.8,scikit-learn==1.0.1,scipy==1.7.3,seaborn==0.11.2,setuptools-scm==6.3.2,six==1.16.0,tensorboard==2.7.0,tensorboard-data-server==0.6.1,tensorboard-plugin-wit==1.8.0,threadpoolctl==3.0.0,tomli==1.2.2,torch==1.10.0,typing_extensions==4.0.0,urllib3==1.26.7,Werkzeug==2.0.2,wrapt==1.13.3,zipp==3.6.0
muzero_gen38 run-test-pre: PYTHONHASHSEED='3264757519'
muzero_gen38 run-test: commands[0] | python -c 'print((80*"=")+"\n"+"python3.8_testenv:muzero_gen"+"\n"+(80*"="))'
================================================================================
python3.8_testenv:muzero_gen
================================================================================
muzero_gen38 run-test: commands[1] | python -c 'print((80*"~")+"\n"+"pip install --upgrade pip setuptools wheel"+"\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip install --upgrade pip setuptools wheel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero_gen38 run-test: commands[2] | pip install --upgrade pip
Requirement already satisfied: pip in ./.tox/muzero_gen38/lib/python3.8/site-packages (21.3.1)
muzero_gen38 run-test: commands[3] | pip install --upgrade setuptools
Requirement already satisfied: setuptools in ./.tox/muzero_gen38/lib/python3.8/site-packages (58.3.0)
Collecting setuptools
  Using cached setuptools-59.3.0-py3-none-any.whl (952 kB)
Installing collected packages: setuptools
  Attempting uninstall: setuptools
    Found existing installation: setuptools 58.3.0
    Uninstalling setuptools-58.3.0:
      Successfully uninstalled setuptools-58.3.0
Successfully installed setuptools-59.3.0
muzero_gen38 run-test: commands[4] | pip install --upgrade wheel
Requirement already satisfied: wheel in ./.tox/muzero_gen38/lib/python3.8/site-packages (0.37.0)
muzero_gen38 run-test: commands[5] | python -c 'print((80*"~")+"\n"+"python -m pip list --format=columns"+"\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
python -m pip list --format=columns
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero_gen38 run-test: commands[6] | python -m pip list --format=columns
Package                 Version
----------------------- -----------
absl-py                 1.0.0
attrs                   21.2.0
bayesian-optimization   1.2.0
cachetools              4.2.4
certifi                 2021.10.8
charset-normalizer      2.0.8
click                   8.0.3
cloudpickle             2.0.0
cma                     3.1.0
cycler                  0.11.0
Deprecated              1.2.13
filelock                3.4.0
fonttools               4.28.2
google-auth             2.3.3
google-auth-oauthlib    0.4.6
grpcio                  1.42.0
gym                     0.21.0
idna                    3.3
importlib-metadata      4.8.2
importlib-resources     5.4.0
joblib                  1.1.0
jsonschema              4.2.1
kiwisolver              1.3.2
Markdown                3.3.6
matplotlib              3.5.0
msgpack                 1.0.3
nevergrad               0.4.3.post9
numpy                   1.21.4
oauthlib                3.1.1
packaging               21.3
pandas                  1.3.4
Pillow                  8.4.0
pip                     21.3.1
protobuf                3.19.1
pyasn1                  0.4.8
pyasn1-modules          0.2.8
pyparsing               3.0.6
pyrsistent              0.18.0
python-dateutil         2.8.2
pytz                    2021.3
PyYAML                  6.0
ray                     1.8.0
redis                   4.0.2
requests                2.26.0
requests-oauthlib       1.3.0
rsa                     4.8
scikit-learn            1.0.1
scipy                   1.7.3
seaborn                 0.11.2
setuptools              59.3.0
setuptools-scm          6.3.2
six                     1.16.0
tensorboard             2.7.0
tensorboard-data-server 0.6.1
tensorboard-plugin-wit  1.8.0
threadpoolctl           3.0.0
tomli                   1.2.2
torch                   1.10.0
typing_extensions       4.0.0
urllib3                 1.26.7
Werkzeug                2.0.2
wheel                   0.37.0
wrapt                   1.13.3
zipp                    3.6.0
muzero_gen38 run-test: commands[7] | python -c 'print((80*"~")+"\n"+"pip freeze\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip freeze
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero_gen38 run-test: commands[8] | pip freeze
absl-py==1.0.0
attrs==21.2.0
bayesian-optimization==1.2.0
cachetools==4.2.4
certifi==2021.10.8
charset-normalizer==2.0.8
click==8.0.3
cloudpickle==2.0.0
cma==3.1.0
cycler==0.11.0
Deprecated==1.2.13
filelock==3.4.0
fonttools==4.28.2
google-auth==2.3.3
google-auth-oauthlib==0.4.6
grpcio==1.42.0
gym==0.21.0
idna==3.3
importlib-metadata==4.8.2
importlib-resources==5.4.0
joblib==1.1.0
jsonschema==4.2.1
kiwisolver==1.3.2
Markdown==3.3.6
matplotlib==3.5.0
msgpack==1.0.3
nevergrad==0.4.3.post9
numpy==1.21.4
oauthlib==3.1.1
packaging==21.3
pandas==1.3.4
Pillow==8.4.0
protobuf==3.19.1
pyasn1==0.4.8
pyasn1-modules==0.2.8
pyparsing==3.0.6
pyrsistent==0.18.0
python-dateutil==2.8.2
pytz==2021.3
PyYAML==6.0
ray==1.8.0
redis==4.0.2
requests==2.26.0
requests-oauthlib==1.3.0
rsa==4.8
scikit-learn==1.0.1
scipy==1.7.3
seaborn==0.11.2
setuptools-scm==6.3.2
six==1.16.0
tensorboard==2.7.0
tensorboard-data-server==0.6.1
tensorboard-plugin-wit==1.8.0
threadpoolctl==3.0.0
tomli==1.2.2
torch==1.10.0
typing_extensions==4.0.0
urllib3==1.26.7
Werkzeug==2.0.2
wrapt==1.13.3
zipp==3.6.0
muzero_gen38 run-test: commands[9] | python -c 'print((80*"~")+"\n"+"End-of-Commands\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
End-of-Commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero_gen39 create: /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero-general/.tox/muzero_gen39
muzero_gen39 installdeps: -r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero-general/requirements.txt
muzero_gen39 installed: absl-py==1.0.0,attrs==21.2.0,bayesian-optimization==1.2.0,cachetools==4.2.4,certifi==2021.10.8,charset-normalizer==2.0.8,click==8.0.3,cloudpickle==2.0.0,cma==3.1.0,cycler==0.11.0,Deprecated==1.2.13,filelock==3.4.0,fonttools==4.28.2,google-auth==2.3.3,google-auth-oauthlib==0.4.6,grpcio==1.42.0,gym==0.21.0,idna==3.3,importlib-metadata==4.8.2,joblib==1.1.0,jsonschema==4.2.1,kiwisolver==1.3.2,Markdown==3.3.6,matplotlib==3.5.0,msgpack==1.0.3,nevergrad==0.4.3.post9,numpy==1.21.4,oauthlib==3.1.1,packaging==21.3,pandas==1.3.4,Pillow==8.4.0,protobuf==3.19.1,pyasn1==0.4.8,pyasn1-modules==0.2.8,pyparsing==3.0.6,pyrsistent==0.18.0,python-dateutil==2.8.2,pytz==2021.3,PyYAML==6.0,ray==1.8.0,redis==4.0.2,requests==2.26.0,requests-oauthlib==1.3.0,rsa==4.8,scikit-learn==1.0.1,scipy==1.7.3,seaborn==0.11.2,setuptools-scm==6.3.2,six==1.16.0,tensorboard==2.7.0,tensorboard-data-server==0.6.1,tensorboard-plugin-wit==1.8.0,threadpoolctl==3.0.0,tomli==1.2.2,torch==1.10.0,typing_extensions==4.0.0,urllib3==1.26.7,Werkzeug==2.0.2,wrapt==1.13.3,zipp==3.6.0
muzero_gen39 run-test-pre: PYTHONHASHSEED='3264757519'
muzero_gen39 run-test: commands[0] | python -c 'print((80*"=")+"\n"+"python3.9_testenv:muzero_gen"+"\n"+(80*"="))'
================================================================================
python3.9_testenv:muzero_gen
================================================================================
muzero_gen39 run-test: commands[1] | python -c 'print((80*"~")+"\n"+"pip install --upgrade pip setuptools wheel"+"\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip install --upgrade pip setuptools wheel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero_gen39 run-test: commands[2] | pip install --upgrade pip
Requirement already satisfied: pip in ./.tox/muzero_gen39/lib/python3.9/site-packages (21.3.1)
muzero_gen39 run-test: commands[3] | pip install --upgrade setuptools
Requirement already satisfied: setuptools in ./.tox/muzero_gen39/lib/python3.9/site-packages (58.3.0)
Collecting setuptools
  Using cached setuptools-59.3.0-py3-none-any.whl (952 kB)
Installing collected packages: setuptools
  Attempting uninstall: setuptools
    Found existing installation: setuptools 58.3.0
    Uninstalling setuptools-58.3.0:
      Successfully uninstalled setuptools-58.3.0
Successfully installed setuptools-59.3.0
muzero_gen39 run-test: commands[4] | pip install --upgrade wheel
Requirement already satisfied: wheel in ./.tox/muzero_gen39/lib/python3.9/site-packages (0.37.0)
muzero_gen39 run-test: commands[5] | python -c 'print((80*"~")+"\n"+"python -m pip list --format=columns"+"\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
python -m pip list --format=columns
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero_gen39 run-test: commands[6] | python -m pip list --format=columns
Package                 Version
----------------------- -----------
absl-py                 1.0.0
attrs                   21.2.0
bayesian-optimization   1.2.0
cachetools              4.2.4
certifi                 2021.10.8
charset-normalizer      2.0.8
click                   8.0.3
cloudpickle             2.0.0
cma                     3.1.0
cycler                  0.11.0
Deprecated              1.2.13
filelock                3.4.0
fonttools               4.28.2
google-auth             2.3.3
google-auth-oauthlib    0.4.6
grpcio                  1.42.0
gym                     0.21.0
idna                    3.3
importlib-metadata      4.8.2
joblib                  1.1.0
jsonschema              4.2.1
kiwisolver              1.3.2
Markdown                3.3.6
matplotlib              3.5.0
msgpack                 1.0.3
nevergrad               0.4.3.post9
numpy                   1.21.4
oauthlib                3.1.1
packaging               21.3
pandas                  1.3.4
Pillow                  8.4.0
pip                     21.3.1
protobuf                3.19.1
pyasn1                  0.4.8
pyasn1-modules          0.2.8
pyparsing               3.0.6
pyrsistent              0.18.0
python-dateutil         2.8.2
pytz                    2021.3
PyYAML                  6.0
ray                     1.8.0
redis                   4.0.2
requests                2.26.0
requests-oauthlib       1.3.0
rsa                     4.8
scikit-learn            1.0.1
scipy                   1.7.3
seaborn                 0.11.2
setuptools              59.3.0
setuptools-scm          6.3.2
six                     1.16.0
tensorboard             2.7.0
tensorboard-data-server 0.6.1
tensorboard-plugin-wit  1.8.0
threadpoolctl           3.0.0
tomli                   1.2.2
torch                   1.10.0
typing_extensions       4.0.0
urllib3                 1.26.7
Werkzeug                2.0.2
wheel                   0.37.0
wrapt                   1.13.3
zipp                    3.6.0
muzero_gen39 run-test: commands[7] | python -c 'print((80*"~")+"\n"+"pip freeze\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip freeze
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero_gen39 run-test: commands[8] | pip freeze
absl-py==1.0.0
attrs==21.2.0
bayesian-optimization==1.2.0
cachetools==4.2.4
certifi==2021.10.8
charset-normalizer==2.0.8
click==8.0.3
cloudpickle==2.0.0
cma==3.1.0
cycler==0.11.0
Deprecated==1.2.13
filelock==3.4.0
fonttools==4.28.2
google-auth==2.3.3
google-auth-oauthlib==0.4.6
grpcio==1.42.0
gym==0.21.0
idna==3.3
importlib-metadata==4.8.2
joblib==1.1.0
jsonschema==4.2.1
kiwisolver==1.3.2
Markdown==3.3.6
matplotlib==3.5.0
msgpack==1.0.3
nevergrad==0.4.3.post9
numpy==1.21.4
oauthlib==3.1.1
packaging==21.3
pandas==1.3.4
Pillow==8.4.0
protobuf==3.19.1
pyasn1==0.4.8
pyasn1-modules==0.2.8
pyparsing==3.0.6
pyrsistent==0.18.0
python-dateutil==2.8.2
pytz==2021.3
PyYAML==6.0
ray==1.8.0
redis==4.0.2
requests==2.26.0
requests-oauthlib==1.3.0
rsa==4.8
scikit-learn==1.0.1
scipy==1.7.3
seaborn==0.11.2
setuptools-scm==6.3.2
six==1.16.0
tensorboard==2.7.0
tensorboard-data-server==0.6.1
tensorboard-plugin-wit==1.8.0
threadpoolctl==3.0.0
tomli==1.2.2
torch==1.10.0
typing_extensions==4.0.0
urllib3==1.26.7
Werkzeug==2.0.2
wrapt==1.13.3
zipp==3.6.0
muzero_gen39 run-test: commands[9] | python -c 'print((80*"~")+"\n"+"End-of-Commands\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
End-of-Commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
___________________________________ summary ____________________________________
  muzero_gen37: commands succeeded
  muzero_gen38: commands succeeded
  muzero_gen39: commands succeeded
  congratulations :)
```