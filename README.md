# Mochila de Itens em C (Projeto de ADS)

Este projeto foi desenvolvido como parte de um exercício do meu curso de **Análise e Desenvolvimento de Sistemas (ADS)**, em uma fase em que eu estava tendo um dos meus **primeiros contatos com C e com programação no geral**.

A proposta foi criar um sistema simples de terminal para simular uma mochila de itens (inspirada no tema Free Fire), praticando lógica, organização de dados e interação com o usuário.

## Intuito do exercício

O principal objetivo da atividade era consolidar fundamentos de programação estruturada em C, como:

- uso de `struct` para representar dados de forma organizada;
- manipulação de vetores estáticos;
- construção de menu interativo com `do...while` e `switch`;
- criação de funções para separar responsabilidades;
- aplicação de algoritmos clássicos de ordenação e busca.

Em resumo, o exercício foi pensado para transformar teoria em prática e mostrar como problemas reais podem ser resolvidos com lógica passo a passo.

## O que foi implementado no programa

O código atual representa a versão mais completa do desafio (nível mestre), contendo:

1. **Cadastro de itens**
   - Cada item possui: `nome`, `tipo`, `quantidade` e `prioridade`.
   - A mochila suporta até 10 itens.

2. **Remoção de itens**
   - É possível remover um item pelo nome.
   - Quando removido, os próximos itens do vetor são deslocados para manter a estrutura consistente.

3. **Listagem formatada**
   - Exibição em formato de tabela com todos os itens cadastrados.

4. **Ordenação por critério**
   - Ordenação por **nome**, **tipo** ou **prioridade**.
   - Uso do algoritmo **Insertion Sort**.
   - Contagem de comparações para observar desempenho.

5. **Busca binária por nome**
   - Busca rápida de item por nome.
   - Só é permitida quando a lista está ordenada por nome (pré-requisito da busca binária).
   - Exibe item encontrado e número de comparações.

## Conceitos praticados

Durante a construção desse exercício, foram praticados pontos importantes para quem está começando:

- tipos compostos com `struct`;
- `enum` para critérios de ordenação;
- controle de fluxo e validações básicas;
- comparação de strings com `strcmp`;
- noções de eficiência com busca sequencial x busca binária;
- organização de código em funções.

## Aprendizado

Mesmo sendo um projeto inicial, ele foi importante para entender como montar um programa completo do início ao fim:

- receber dados do usuário;
- processar regras de negócio;
- exibir saídas claras;
- evoluir a solução em níveis de complexidade.

Esse trabalho marcou uma etapa importante da minha formação em ADS e serviu como base para projetos mais avançados depois.
