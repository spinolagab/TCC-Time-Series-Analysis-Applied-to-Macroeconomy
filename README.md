# Testes iniciais dos dados obtidos da API

## Como preparar o ambiente python:

### Máquina Virtual

Windows:

```bash
python -m venv venv
venv/Scripts/activate
```

Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

Após essa etapa, vamos

---

### ipykernel, python-dotenv e requests

Para usarmos o jupyter notebook com o VS-Code, precisamos do ipykernel instalado para que possa reconhecer o ambiente jupyter e torne possível o uso das células de execução.

Por questões de segurança da nossa chave de API usaremos python-dotenv para evitar chamar ela abertamente no código, colocando no gitignore

```bash
pip install ipykernel
pip install python-dotenv
pip install requests
```

---

### Criar um novo kernel

Exemplo do kernel "projetoTeste" sendo criado

Windows

```bash
python -m ipykernel install --user --name=projetoTeste
```

Linux:

```bash
python3 -m ipykernel install --user --name=projetoTeste
```

---

### Executando o ambiente Jupyter

No seu terminal digite `Jupyter notebook` e um localhost será aberto para usar o notebook Jupyter para desenvolvimento local.

---

## Usando a API com python

[Acesse o notebook por aqui](./Untitled-1.ipynb)

---

## Problemas atuais
