# Recife City Hall Bidding Dashboard

This project presents a statistical analysis of the bidding processes conducted by the Recife City Hall, based on a public dataset. 
[Original Dataset](http://dados.recife.pe.gov.br/dataset/591a6ed4-7beb-4304-a2a1-2af521517a06/resource/c5d7505c-381c-4670-a0c2-1fbf56df50b1/download/dados_abertos_licitacao_concluida.csv)

## 🚀 Getting Started

These instructions will guide you through getting a copy of the project running on your local machine or online via Google Colab.

### 📋 Prerequisites

**To run in the cloud:**
* [GOOGLE COLAB](https://colab.research.google.com)

**To run locally:**
* [PYTHON](https://www.python.org/downloads/)
* [JUPYTER NOTEBOOK](https://jupyter.org/install)

---

## 🔧 Installation

### Google Colab
No installation is required to run the project in the cloud. You only need a Google account to access the following links:

* [DASHBOARD](https://colab.research.google.com/github/dayviddouglas/ciencia_de_dados_licitacoes_prefeitura_do_recife/blob/main/dashboard.ipynb)
* [BIDDING & DECISION TREE](https://colab.research.google.com/github/dayviddouglas/ciencia_de_dados_licitacoes_prefeitura_do_recife/blob/main/Licita%C3%A7%C3%B5es.ipynb)

### Windows
1. [Download Python for Windows](https://www.python.org/downloads/windows/)
2. **Create a project folder:** Choose a location on your file system and create a folder for your Python project.
3. **Open the terminal and navigate to the folder:** Use the Command Prompt or terminal to go to the created directory.
4. **Create a virtual environment (venv):**
   ```bash
   python -m venv venv
   ```
Activate the virtual environment:
```bash 
$ venv\Scripts\activate
```
Install dependencies from requirements.txt:
```bash 
$ pip install -r requirements.txt
```
Note: The dashboard.ipynb file is in Python Notebook format and operates through code and text cells. To start the project, you must run all cells in order. The last cell will provide a local server link running on port 8050 (the default DashApp port).

## MAC

[DOWLOAD DO PYTHON FOR MAC](https://www.python.org/downloads/macos/)

Create and navigate to your project folder using the Terminal.

Create a virtual environment (venv):

```bash 
$ python -m venv venv
```
Activate the virtual environment:
```bash 
$ source venv/bin/activate
```
Install dependencies:
```bash 
$ pip install -r requirements.txt
```


## LINUX

[INSTALAÇÃO PYTHON FOR LINUX](https://python.org.br/instalacao-linux/)

Setup: While most modern GNU/Linux systems come with Python installed, creating a virtual environment is recommended to avoid system conflicts.

Navigate to the folder and create a venv:

```bash 
$ python -m venv venv
```

Activate the virtual environment:

```bash 
$ source venv/bin/activate
```

Install dependencies:

```bash 
$ pip install -r requirements.txt
```
## 📌 Versioning

We use GitHub for version control. For available versions, see the [commits](https://github.com/dayviddouglas/ciencia_de_dados_licitacoes_prefeitura_do_recife/commits/main/). 

## 🛠️ Built With

* [PYTHON](https://www.python.org/doc/) - The programming language used.
* [DASH](https://dash.plotly.com) - The framework used for the dashboard.
* [PLOTLY](https://plotly.com/python/) - Library for building charts.
* [PANDAS](https://pandas.pydata.org/docs/) - Library for data analysis and structuring.

## ✒️ Authors

* *Alessandro Henrique* - Planning, Prototyping, and Documentation - [Alessandro Henrique](https://github.com/alessandrohpsf)
* *Dayvid Douglas* - Full-stack Development - [Dayvid Douglas](https://github.com/dayviddouglas)
* *Lacê Renê* - Planning and Front-end Development - [Renne Gomes](https://github.com/rennegomes)
* *Márcio Milet* - Full-stack Development - [Marcio Milet](https://github.com/marciomilet)
* *Rarissa Gabriele* -Planning, Prototyping, and Documentation - [Rarissa Santos](https://github.com/rarissasantos29)
