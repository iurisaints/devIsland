# Aula 6 - Conceitos Iniciais

# Conceitos de Programação: Variáveis e Desvios de Fluxo no Scratch

## O que são Variáveis?

Variáveis são espaços de armazenamento que contêm informações ou valores modificáveis durante a execução do programa. Elas são fundamentais para armazenar e manipular dados.

## Por que Usamos Variáveis?

Variáveis permitem que programas armazenem e manipulem dados dinamicamente. Elas são cruciais para adaptar o comportamento do programa com base nas condições e na entrada do usuário.

## Exemplo Prático no Scratch: Usando Variáveis

Suponha que queremos criar um programa simples para contar quantas vezes um personagem se move para a direita e exibir essa contagem.

1. Crie uma variável chamada "Contagem".
2. Arraste um bloco "Quando a bandeira verde for clicada".
3. Adicione um bloco "Mover 10 passos" e, em seguida, um bloco "Mudar [Contagem] por 1".

```
quando a bandeira verde for clicada
  mover 10 passos
  mudar [Contagem] por 1
  dizer "Contagem: " & [Contagem]
```

## **O que são Desvios de Fluxo?**

Desvios de fluxo são estruturas que permitem que o programa tome decisões com base em condições específicas. No Scratch, isso é geralmente feito usando blocos "Se... Então", "Se Não" e "Então".

## **Exemplo Prático no Scratch: Desvios de Fluxo**

Suponha que queremos criar um programa que verifica se a pontuação de um jogo atingiu um certo limite e exibe uma mensagem correspondente.

1. Arraste um bloco "Quando a bandeira verde for clicada".
2. Adicione um bloco "Se... Então" e encaixe-o abaixo do bloco anterior.
3. Dentro do bloco "Se... Então", adicione um bloco "pontuação > 100".
4. Adicione um bloco "Dizer" com a mensagem "Parabéns, você atingiu uma pontuação alta!".

```jsx
quando a bandeira verde for clicada
  se <pontuação > 100> então
    dizer "Parabéns, você atingiu uma pontuação alta!"
```

**Atividade Interativa:**

Pedir para os alunos criarem projetos no Scratch que envolvam o uso de variáveis e desvios de fluxo e se compararem com os projetos que levarei como exemplo.
