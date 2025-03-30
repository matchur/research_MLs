## **Instalação do Jupyter Notebook**

Para iniciar os notebooks, instale o Jupyter Notebook com o comando:

```bash
pip install notebook
```

Para iniciar o Jupyter Notebook, execute:

```bash
jupyter notebook
```

Se esse comando não funcionar, tente:

```bash
python -m notebook
```

No navegador do Jupyter Notebook, clique no arquivo desejado para abri-lo.

Para executar o código:

- Clique em **Run** ▶️

- Ou pressione `Shift + Enter` em uma célula para executar somente ela

## **Instalação das Bibliotecas Necessárias**

Antes de rodar os notebooks, instale todas as dependências executando:

```bash
pip install -r requirements.txt
```

## **Criando um Ambiente Virtual (Recomendado)**

Para isolar as dependências do projeto, crie um ambiente virtual:

```bash
pip install --user virtualenv
```

Depois, crie e ative o ambiente:

- **Windows**:

  ```bash
  python -m venv venv venv\Scripts\activate
  ```

- **Mac/Linux**:

  ```bash
  python3 -m venv venv source venv/bin/activate
  ```

Agora, instale as dependências dentro do ambiente virtual:

```bash
pip install -r requirements.txt
```

## **Instalação do TensorFlow**

Se precisar instalar manualmente:

```bash
pip install --upgrade tensorflow
```

Se houver problemas, tente:

```bash
pip install --upgrade https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-0.12.0-py3-none-any.whl
```

Caso queira a versão mais recente:
```bash
pip install tf-nightly
```

Bons estudos! 🚀
