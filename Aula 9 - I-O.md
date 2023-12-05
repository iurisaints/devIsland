# Aula 9 - Entrada e Saída de Dados

# Introdução à Entrada e Saída de Dados

## O que é Entrada e Saída de Dados?

Em programação, entrada de dados refere-se a receber informações do usuário, enquanto saída de dados significa exibir informações para o usuário.

## Entrada de Dados

### Função `input()` em Python

Em Python, podemos usar a função `input()` para receber entrada do usuário.

```python
# Exemplo simples de entrada de dados
nome = input("Qual é o seu nome? ")
idade = input("Quantos anos você tem? ")

# Exibindo os dados inseridos
print("Olá,", nome + "!", "Você tem", idade, "anos.")

```

## Saída de Dados

### Função `print()` em Python

A função `print()` é usada para exibir informações na tela.

```python
# Exemplo simples de saída de dados
print("Bem-vindos à aula de programação Ilha da Programação!")
print("Hoje aprenderemos sobre entrada e saída de dados.")

```

## Atividade Interativa: Criando um Programa de Conversa

Vamos criar um programa que faz perguntas simples e responde com base nas respostas dos usuários.

```python
# Programa de Conversa
print("Bem-vindos ao Programa de Conversa!")

# Perguntas
nome = input("Qual é o seu nome? ")
idade = input("Quantos anos você tem? ")

# Respostas
print("Olá,", nome + "!")
print("Legal! Você tem", idade, "anos.")

# Pergunta adicional
linguagem_favorita = input("Qual é a sua linguagem de programação favorita? ")

# Resposta final
print("Interessante! Eu também gosto de", linguagem_favorita + ".")
print("Espero que você se divirta programando!")

```

---

**Atividade Prática:**
Peça às crianças para personalizarem o programa de conversa. Podem mudar as perguntas, adicionar mais interações ou fazer com que o programa conte uma história simples com base nas respostas.
