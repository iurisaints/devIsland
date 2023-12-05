# Aula 11 - Desvios De Fluxo

# Descobrindo o Mundo dos Desvios de Fluxo

## O que são Desvios de Fluxo?

Desvios de fluxo são estruturas em programação que permitem que o código tome decisões com base em condições específicas. Em outras palavras, eles ajudam o programa a escolher diferentes caminhos a serem seguidos.

## Estruturas de Controle de Fluxo

### 1. **Condicional (Se... Então... Senão...)**

- Usada para executar um bloco de código se uma condição for verdadeira e outro bloco se for falsa.

```python
idade = 12

if idade < 18:
    print("Você é menor de idade.")
else:
    print("Você é maior de idade.")

```

### 2. **Laços de Repetição (Enquanto e Para)**

- Permitem que um bloco de código seja repetido várias vezes.

### Laço `while`

```python
contador = 0

while contador < 5:
    print(contador)
    contador += 1

```

### Laço `for`

```python
for i in range(5):
    print(i)

```

## Atividade Interativa: Criando uma História com Desvios de Fluxo

Vamos criar uma história interativa onde as crianças podem usar desvios de fluxo para alterar o rumo da história com base nas escolhas do usuário.

```python
# História Interativa com Desvios de Fluxo
print("Bem-vindos à História Interativa!")

# Pergunta inicial
escolha = input("Você quer ir para a floresta ou para a montanha? (floresta/montanha) ")

# Desvio de fluxo com base na escolha
if escolha == "floresta":
    print("Você entrou na floresta. Encontrou uma trilha misteriosa.")
    escolha_trilha = input("Você quer seguir a trilha ou explorar mais a floresta? (trilha/explorar) ")

    if escolha_trilha == "trilha":
        print("A trilha leva a uma clareira mágica. Você fez uma ótima escolha!")
    else:
        print("Explorando mais, você encontra uma família de coelhos. Uma experiência encantadora!")

else:
    print("Você subiu a montanha. No topo, há uma vista incrível do vale.")

print("Fim da História.")

```

## Boas Práticas com Desvios de Fluxo

1. **Clareza:** Certifique-se de que as condições são claras e fáceis de entender.
2. **Aninhamento Moderado:** Evite aninhar muitos níveis de desvios, pois pode tornar o código difícil de ler.
3. **Teste Diferentes Cenários:** Experimente diferentes escolhas para garantir que todos os caminhos estejam funcionando corretamente.

---

**Atividade Prática:**
Pedir às crianças para criarem suas próprias histórias interativas usando desvios de fluxo. Elas podem adicionar diferentes escolhas e resultados para criar uma narrativa única. Dar exemplos existentes.
