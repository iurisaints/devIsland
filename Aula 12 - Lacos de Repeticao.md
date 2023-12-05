# Aula 12 - Laços.md

# Explorando o Mundo dos Laços de Repetição

## O que são Laços de Repetição?

Laços de repetição são estruturas fundamentais em programação que permitem executar um bloco de código várias vezes. Eles ajudam a automatizar tarefas repetitivas e a tornar o código mais eficiente.

## Tipos de Laços de Repetição

### 1. **Laço `while` (Enquanto)**

O laço `while` repete um bloco de código enquanto uma condição específica for verdadeira.

```python
contador = 0

while contador < 5:
    print(contador)
    contador += 1

```

### 2. **Laço `for` (Para)**

O laço `for` é usado para iterar sobre uma sequência (como uma lista) ou para executar um bloco de código um número específico de vezes.

```python
for i in range(5):
    print(i)

```

## Atividade Interativa: Criando uma Contagem Regressiva

Vamos criar um programa simples que utiliza um laço `for` para fazer uma contagem regressiva.

```python
# Contagem Regressiva
print("Vamos fazer uma contagem regressiva!")

for i in range(10, 0, -1):
    print(i)

print("Foguete lançado!")

```

## Aplicações dos Laços de Repetição

### Automatização de Tarefas Repetitivas

```python
# Imprimir "Olá" cinco vezes
for _ in range(5):
    print("Olá")

```

### Iteração sobre Elementos

```python
# Iterar sobre uma lista
frutas = ["maçã", "banana", "laranja"]

for fruta in frutas:
    print("Gosto de", fruta)

```

## Boas Práticas com Laços de Repetição

1. **Inicialização Adequada:** Certifique-se de que as variáveis usadas como contadores ou condições iniciais estão configuradas corretamente.
2. **Atualização Consciente:** Garanta que o laço tenha uma condição que eventualmente seja falsa para evitar loops infinitos.
3. **Legibilidade:** Mantenha o código dentro do bloco do laço de repetição claro e conciso.

---

**Atividade Prática:**
Pedir para as crianças criarem seu próprio programa usando um laço de repetição. Pode ser algo como imprimir números pares, contar de 1 a 20 ou qualquer outra ideia criativa. Vamos verificar em aula como elas correspondem ao assunto.
