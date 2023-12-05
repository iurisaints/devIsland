# Aula 8 - Iniciando no Python

# Introdução ao Python: Primeiros Passos

## O que é Python?

Python é uma linguagem de programação de alto nível, de código aberto e fácil de aprender. É conhecida por sua sintaxe clara e concisa, tornando-a uma ótima escolha para iniciantes.

## O que é o Google Colab?

O Google Colab é um ambiente de notebook baseado na nuvem que permite escrever e executar código em Python. Ele é executado no Google Drive e oferece acesso gratuito a recursos computacionais, incluindo GPUs.

## Acesso ao Google Colab

1. Acesse o [Google Colab](https://colab.research.google.com/) usando sua conta do Google.
2. Crie um novo notebook ou abra um existente.

## Interface do Google Colab

O ambiente do Google Colab é semelhante ao Jupyter Notebook. Ele é composto por células que podem conter código, texto ou gráficos.

### Criando uma Célula de Código

1. Clique no botão "+" na barra de ferramentas para adicionar uma nova célula.
2. Selecione o tipo "Código" no menu suspenso.

### Executando Células de Código

- Pressione `Shift + Enter` para executar uma célula de código.

### Adicionando Texto com o Markdown

1. Mude o tipo da célula para "Texto" no menu suspenso.
2. Use a sintaxe Markdown para formatar o texto.

Exemplo:

```markdown
# Título
Isso é um parágrafo em **negrito**.

```

## Utilizando Bibliotecas em Python

O Google Colab já inclui muitas bibliotecas populares de ciência de dados e aprendizado de máquina. Para usar uma biblioteca específica, você pode instalá-la ou importá-la diretamente.

Exemplo:

```python
# Instalando uma biblioteca
!pip install numpy

# Importando biblioteca
import numpy as np

```

## Upload de Dados e Arquivos

Você pode fazer o upload de dados diretamente para o ambiente do Google Colab.

1. Execute a célula abaixo para abrir o seletor de arquivos.

```python
from google.colab import files
uploaded = files.upload()

```

1. Selecione os arquivos que deseja enviar.

## Acesso a GPUs Gratuitas

O Google Colab oferece acesso gratuito a GPUs, o que pode ser útil para tarefas intensivas em computação, como treinamento de modelos de aprendizado de máquina.

1. Selecione "Ambiente de execução" no menu.
2. Escolha "Alterar tipo de ambiente de execução".
3. Selecione "GPU" no menu suspenso.

---

## Seu Primeiro Programa Python

Vamos começar com um programa simples em Python.

1. Abra seu editor de código ou IDE.
2. Crie um novo arquivo e digite o seguinte código:
    
    ```python
    # Meu primeiro programa em Python
    print("Olá, mundo!")
    
    ```
    
3. Salve o arquivo com a extensão ".py", por exemplo, "meu_primeiro_programa.py".
4. Execute o programa no terminal:
    
    ```bash
    python3 meu_primeiro_programa.py
    
    ```
    

Se tudo estiver configurado corretamente, você verá a saída "Olá, mundo!".

## Conceitos Básicos em Python

### Variáveis e Tipos de Dados

Em Python, você pode declarar variáveis sem especificar seu tipo. O interpretador Python faz isso automaticamente.

```python
nome = "Alice"
idade = 25
altura = 1.75

```

### Estruturas de Controle de Fluxo

### Condicionais (if, else, elif)

```python
idade = 18

if idade < 18:
    print("Você é menor de idade.")
elif idade == 18:
    print("Você tem exatamente 18 anos.")
else:
    print("Você é maior de idade.")

```

### Loops (for, while)

```python
for i in range(5):
    print(i)

contador = 0
while contador < 5:
    print(contador)
    contador += 1

```

---

**Atividade Prática:**
Peça aos alunos para escreverem um pequeno programa Python que peça ao usuário seu nome e idade, e então imprima uma mensagem personalizada.
