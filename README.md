# Pipeline de Dados com Python

## Contexto: Fusão de Empresas

Duas empresas (Empresa A e Empresa B) se fundiram e os dados precisam ser unificados. O objetivo é:

- Obter os dados brutos de ambas as empresas.
- Transportá-los e transformá-los.
- Entregá-los prontos para o time de Analytics.

---

## Ambiente de Desenvolvimento: Linux no Windows (WSL)

Utilizamos o **WSL (Windows Subsystem for Linux)** para rodar um ambiente Linux dentro do Windows. Isso permite trabalhar com comandos, ferramentas e bibliotecas típicas do Linux diretamente no Windows.

> ⚠️ Como o WSL é independente do Windows, **tudo deve ser instalado do zero** dentro dele (Python, bibliotecas, ferramentas, etc.).

---

## Comandos básicos do Linux

| Comando                    | Descrição                                 |
|---------------------------|-------------------------------------------|
| `mkdir <nome_pasta>`      | Cria uma nova pasta                      |
| `cd <nome_pasta>`         | Entra em uma pasta                       |
| `cd ..`                   | Volta uma pasta                          |
| `ls`                      | Lista arquivos e pastas do diretório     |
| `wget [URL]`              | Baixa arquivos a partir de uma URL       |
| `wget -O arquivo.txt [URL]` | Salva o conteúdo da URL com nome específico |

---

## Preparando o Ambiente: Python e Virtualenv

1. **Atualize os pacotes do sistema:**
```bash
sudo apt update
sudo apt upgrade -y
```

2. **Instale Python 3 e ferramentas auxiliares:**
```bash
sudo apt install python3.10 -y
sudo apt install python3-pip -y
sudo apt install python3-venv -y
```


3. **Crio o projeto e um ambiente virtual:**
```bash
mkdir pipeline_dados
cd pipeline_dados
python3 -m venv venv
source venv/bin/activate

```

4. **Instale as bibliotecas:**
```bash
pip install requests==2.28.2
pip install pandas==2.0.0

```


## Versões
Nesse ambiente de Data Engineer é muito importante documentar a vesão das ferramentas que estamos ultilizando

```bash
pip install requests==2.28.2
pip install pandas==2.0.0
```

###### Trazer arquivos WSL -> Windows
```bash
cp ~/Documentos/pipeline_dados/notebooks/Data_mining.ipynb /mnt/c/Users/joaoh
```
 


# Separação

1. **Data Raw**

2. **Data Processed**

3. **Notebooks**











