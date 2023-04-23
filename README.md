# libras_projeto_6
Projeto de Machine Learning para classificar sinais de LIBRAS e ajudar pessoas que querem aprender a Língua Brasileira de Sinais

## Como rodar o projeto no Mac M1?

1. Download miniforge com o Homebrew

```brew install miniforge```

2. Após a instalação do Miniforge, por padrão, ele nos fornece um ambiente base. Você pode desativar o ambiente base padrão executando o seguinte comando:

```conda config --set auto_activate_base false```

3. Crie um ambiente virtual para nosso projeto

```conda create --name librasenv python=3.8```

4. Para ativar o librasenv

```conda activate librasenv```

5. Instalar as dependencias do conda

```conda install -c conda-forge tensorflow```

```conda install -c anaconda ipykernel```

6. Configurar o ipykernel no librasenv

```python3 -m ipykernel install --user --name=librasenv```

7. Iniciar Jupyter notebook no ambiente librasenv. Você também pode mudar o kernel no VS Code para rodar no librasenv.

```jupyter notebook```
