# 🃏 Super Trunfo — Nível Mestre

Projeto desenvolvido em linguagem **C** como parte do **Desafio Final - Super Trunfo**.
O programa compara duas cartas de cidades brasileiras com base em **dois atributos escolhidos pelo jogador**.

---

## 🚀 Funcionalidades

* Cadastro de **duas cartas** com os seguintes atributos:

  * Estado (A–H)
  * Código da carta (ex: A01)
  * Nome da cidade
  * População
  * Área (km²)
  * PIB (em bilhões de reais)
  * Número de pontos turísticos
* Cálculo automático de:

  * Densidade populacional
  * PIB per capita
* Menu interativo com **escolha de dois atributos diferentes** para comparação.
* Exibição de resultados detalhados com:

  * Valores de cada atributo em ambas as cartas
  * Soma dos atributos
  * Indicação da carta vencedora ou empate

---

## 🧠 Atributos disponíveis para comparação

1. População
2. Área
3. PIB
4. Pontos turísticos
5. Densidade populacional
6. PIB per capita

## 🖥️ Exemplo de uso

```
=====================================
        BEM-VINDO AO SUPER TRUNFO
=====================================
Neste jogo, voce vai cadastrar 2 cartas
com informacoes sobre cidades brasileiras.
Depois, vamos comparar seus atributos!
-------------------------------------

Digite o Estado da Carta 1 (A-H): A
Digite o Codigo da Carta 1: A01
Digite o Nome da Cidade: Rio de Janeiro
...

Escolha o primeiro atributo: 1 (População)
Escolha o segundo atributo: 6 (PIB per capita)

Comparando cartas...
Carta 1 venceu no primeiro atributo!
Carta 2 venceu no segundo atributo!
...
Soma total: Carta 1 venceu a rodada!

```

## 🧾 Observações
O programa usa switch, operadores ternários e tratamento de empates.  
Em caso de empate na soma total, o programa exibe:  
Empate!

## ⚠️ Autoria
Projeto desenvolvido por Ana Clara do Nascimento de Oliveira  
Repositório GitHub: https://github.com/Ana-ac-427/desafio_logica_super_trunfo.c.git
