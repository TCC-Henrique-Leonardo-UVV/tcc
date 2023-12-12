# TCC

![GitHub repo size](https://img.shields.io/github/repo-size/TCC-Henrique-Leonardo-UVV/tcc)
![GitHub language count](https://img.shields.io/github/languages/count/TCC-Henrique-Leonardo-UVV/tcc)
![GitHub forks](https://img.shields.io/github/forks/TCC-Henrique-Leonardo-UVV/tcc)

<!-- <img src="imagem.png" alt="Exemplo imagem"> -->

Example description

## 💻 Prerequisites

Before starting, check if you have all the prerequisites nailed down:

- You have the latest version of `git` installed
- You have `python 3.10` or you have a `conda` distribution installed
- You have the latest PostgreSQL version running with the ![pgvector](https://github.com/pgvector/pgvector) plugin installed
  or alternatively
- You have the latest version of docker installed

## 🚀 Installation

To install this project, follow this steps:

First clone the repository with git:
```
git clone https://github.com/TCC-Henrique-Leonardo-UVV/tcc.git
```

If you want to use a venv, create and activate it (you must be using python version 3.10):
```
python -m venv article-recommendation

# Activate the environment in Linux and macOS
source article-recommendation/bin/activate

# Activate the environment in Windows
article-recommendation\bin\activate.ps1
```

or if you prefer to use conda, create an environment with python 3.10 and activate it:
```
conda create -n "article-recommendation" python=3.10
```

With the environment activated, install the appropriate dependencies:
```
# using venv and pip
pip install -r requirements.txt

# using conda
conda env update --name article-recommendation --file environment.yml --prune
```

To install and run the database, you can follow the steps at the ![pgvector](https://github.com/pgvector/pgvector) repository. If you prefer a
more automated and easier approach, there is a docker image available that can be used the same way than a normal PostgreSQL image:
```
docker run --name pgvector-article-recommendation -e POSTGRES_PASSWORD=admin -e POSTGRES_USER=postgres -p 5432:5432 ankane/pgvector
```

## ☕ Getting Started

To use this project, follow this steps:

```
<example>
```

## 🤝 Colaborators

We would like to thank the people who contributed to this project:

<table>
  <tr>
    <td align="center">
      <a href="#" title="define link title">
        <img src="https://avatars.githubusercontent.com/u/62520316" width="100px;" alt="Leonardo Chaga's Profile Picture"/><br>
        <sub>
          <b>Leonardo Chaga</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#" title="defina o titulo do link">
        <img src="https://avatars.githubusercontent.com/u/51490953" width="100px;" alt="Henrique Miossi's Profile Picture"/><br>
        <sub>
          <b>Henrique Miossi</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 📝 License

Read the [LICENSE](LICENSE.md) for more details.
