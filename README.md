# Classificador de Números - Complexidade Ciclomática 10

Trabalho acadêmico de Engenharia de Software / Testes de Software.

## Objetivo
Identificar e implementar um problema que possua, no mínimo, um método com **Complexidade Ciclomática de McCabe igual a 10**.

## Problema Escolhido
Classificação de um número inteiro nas seguintes categorias:
- negativo
- zero
- digito_unico
- dezenas_pares
- dezenas_impares
- centenas_pares_multiplo_de_5
- centenas_pares
- centenas_impares_multiplo_de_5
- centenas_impares
- grande

## Complexidade Ciclomática
O método `classificar(int valor)` possui **complexidade ciclomática = 10**.

## Estrutura do Projeto
- `ClassificadorDeNumeros.java` → Classe principal
- `ClassificadorDeNumerosTest.java` → 10 casos de teste (Análise de Valor Limite)
- `GrafoMcCabe.puml` → Grafo de Fluxo de Controle
- `TabelaValoresLimite.md` → Tabela de valores de teste

## Tecnologias
- Java 17
- JUnit 5
- Maven
- PlantUML

## Como executar os testes
```bash
mvn test