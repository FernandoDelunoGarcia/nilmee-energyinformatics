# Data set

- [Training data](https://drive.google.com/file/d/1T82ZtwV85xHV3g-cAZFWtjlutb65_P57/view?usp=sharing).
- [Testing data](https://drive.google.com/file/d/1OdOhYX6o840UEwTuqz7_CZlaNhz6ytkn/view?usp=sharing).


# NILMTK:

1. Clone the sources:

```sh
git clone https://github.com/FernandoDelunoGarcia/nilmtk
git clone https://github.com/FernandoDelunoGarcia/nilm_metadata
```

For testing, the nilmtk experiment API had to be changed in order to access all monitored attributes. Changes are currently maintained in the "estudos" branch of the nilmtk repository:

```sh
git checkout estudos
```

In addition, the nilmtk and nilmtk_metadata directories must be exported to the PYTHONPATH environment variable. The packages used in the virtual environment are listed in the requirements.txt file. To create the environment:

```sh
python3 -m even env_nilmtk
. env_nilmtk/bin/activate
python -m pip install -r requirements.txt
```