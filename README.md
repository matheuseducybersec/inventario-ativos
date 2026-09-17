# Sistema de Inventário de Ativos

Sistema desenvolvido para controle e gerenciamento de ativos.

## Objetivo

Permitir o cadastro e gerenciamento dos ativos da organização.

## Funcionalidades

- Cadastro de ativos
- Consulta de ativos por patrimônio e com filtros
- Controle de patrimônio

## Cadastro de Ativos

A funcionalidade de cadastro permitirá registrar informações dos ativos, como:

- Nome do ativo
- Número de patrimônio
- Categoria
- Localização
- Responsável

## Resolução de Conflito

Durante o desenvolvimento, ocorreram alterações simultâneas na funcionalidade de consulta de ativos em duas branches diferentes.

A branch `feature/consulta-ativos` alterou a funcionalidade para consulta por patrimônio, enquanto a branch `ajuste-consulta` adicionou a possibilidade de utilizar filtros.

Durante o merge, o Git identificou um conflito porque as duas branches modificaram a mesma linha do arquivo `README.md`.

O conflito foi resolvido combinando as duas alterações:

- Consulta de ativos por patrimônio e com filtros

Após a resolução, o arquivo foi adicionado novamente à área de staging e o merge foi finalizado com o commit:

`c0e1109 merge: resolve conflito na consulta de ativos`
