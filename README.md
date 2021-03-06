# Livro de Machine Learning Matt Harrison

Scrips feitos em: 06/04/2022.

E-mail: jgmsantos@gmail.com

Homepage: [https://guilherme.readthedocs.io/en/latest/](https://guilherme.readthedocs.io/en/latest/)

## Links de apoio

[https://www.kaggle.com/code/praanj/titanic-decision-tree-complete-evaluation/notebook](https://www.kaggle.com/code/praanj/titanic-decision-tree-complete-evaluation/notebook)

## Exportar bibliotecas

Essa tarefa é interessante para replicar alguma aplicação em um novo ambiente virtual usando as mesmas bibliotecas do ambiente virtual antigo.


```
pip freeze > requirements.txt
```
ou
```
conda env export > environment.yml
```

**Para instalar as mesma bibliotecas em outro ambiente viartual**, ative o novo ambiente virtual e digite os comandos abaixo:

```
pip install -r my_lib.txt
```

ou

```
conda create -f my_lib.yml
```

## Datasets para uso:

[https://biostat.app.vumc.org/wiki/Main/DataSets](https://biostat.app.vumc.org/wiki/Main/DataSets)

## Ler excel:

[https://pypi.org/project/xlrd/#description](https://pypi.org/project/xlrd/#description)

```
conda install -c anaconda xlrd
```

ou

```
pip install xlrd
```

## Informa um relatório detalhado sobre o dataset:

[https://www.geeksforgeeks.org/how-to-install-pandas-profiling-on-linux/](https://www.geeksforgeeks.org/how-to-install-pandas-profiling-on-linux/)

```
pip3 install Pandas-Profiling
```

[https://stackoverflow.com/questions/41201686/from-configparser-import-safeconfigparser-importerror-no-module-named-configpa](https://stackoverflow.com/questions/41201686/from-configparser-import-safeconfigparser-importerror-no-module-named-configpa)

[https://github.com/pyjanitor-devs/pyjanitor/issues/696](https://github.com/pyjanitor-devs/pyjanitor/issues/696)

## Atualizar pip3

```
pip3 install --upgrade pip
```

## Instalar outra versão do Python

```
conda create --name mlbook python=3.9.12
```

## Desinstalar python 2

[https://stackoverflow.com/questions/44602191/how-to-completely-uninstall-python-2-7-13-on-ubuntu-16-04](https://stackoverflow.com/questions/44602191/how-to-completely-uninstall-python-2-7-13-on-ubuntu-16-04)

```
sudo apt purge -y python2.7-minimal
```

## Desinstalar Python 3.6

[https://askubuntu.com/questions/911448/uninstall-python-3-6](https://askubuntu.com/questions/911448/uninstall-python-3-6)

```
sudo apt-get remove --purge python3.6
```

## 

```
/tmp/ipykernel_20117/1564088600.py:15: UserWarning: Matplotlib is currently using agg, which is a non-GUI backend, so cannot show the figure.
  plt.show()
```

Solução:

```
pip3 install PyQt5
```

## Ao criar um novo ambiente virtual

Cria um novo ambiente virtual com o Python 3.9.12.

```
conda create --name mlmatt python=3.9.12
```

Atualizar o pip.

```
python -m pip install --upgrade pip
```

Executar o Jupyter Notebook.
```
/home/gui/anaconda3/envs/<nome_ambiente_virtual>/bin/python -m pip install ipykernel -U --force-reinstall
```


## Bibliotecas do livro

```
conda install python==3.6 | versão instalada: 3.9.12
pip install catboost==0.11.1 | versão instalada: 1.0.4
pip install category_encoders==2.0.0
pip install Missing dtreeviz | versão instalada: 1.3.5
pip install eli5==0.8.2
pip install fancyimpute==0.4.2
pip install fastai==1.0.28 | versão instalada: 2.5.6
pip install featuretools==0.4.0
pip install Missing glmnet_py | versão instalada: 0.1.0b2
pip install graphviz==0.10.1
pip install hdbscan==0.8.22
pip install imblearn==0.4.3 | versão instalada: 0.0
pip install janitor==0.16.6 | versão instalada: 0.1.1
pip install Missing lime | versão instalada: 0.2.0.1
pip install matplotlib==2.2.3 | versão instalada: 3.4.2
pip install missingno==0.4.2
pip install mlxtend==0.14.0
pip install numpy==1.15.2 | versão instalada: 1.22.3
pip install pandas==0.23.4 | versão instalada: 1.2.0
pip install Missing pandas_profiling | versão instalada: 3.1.0
pip install pdpbox==0.2.0
pip install phate==0.4.2
pip install Missing pydotplus | versão instalada: 2.0.2
pip install rfpimp | versão instalada: 1.3.7
pip install scikit-plot==0.3.7
pip install scipy==1.1.0 | versão instalada: 1.8.0
pip install seaborn==0.9.0 | versão instalada: 0.11.2
pip install shap==0.25.2
pip install sklearn==0.25 | versão instalada: 0.0
pip install --user scikit-learn==0.22.1
pip install statsmodels==0.9.0 | versão instalada: 0.13.2
pip install tpot==0.9.5
pip install treeinterpreter==0.1.0
pip install umap==0.3.8 | versão instalada: 0.1.1
pip install xgboost==0.81
pip install yellowbrick==0.9 | versão instalada: 1.4
pip install pyjanitor | versão instalada: 0.22.0
pip install xlrd | versão instalada: 2.0.1
pip install ipywidgets | versão instalada: 7.7.0
pip install jinja2==3.0.0 | versão instalada: 3.1.1
pip install configparser | versão instalada: 5.2.0
pip install Flask==2.1.1
pip install multimethod==1.4
pip install pydantic==1.9.0
```