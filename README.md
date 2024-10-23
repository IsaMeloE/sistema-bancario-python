# Sistema Bancário em Python

Este projeto é uma atividade desenvolvida como parte do Bootcamp da NTT DATA - Engenharia de Dados com Python oferecido pela [Digital Innovation One (DIO)](https://web.dio.me/). O objetivo é criar um sistema bancário simples que permita realizar operações de depósito, saque e exibição de extrato bancário.

## Funcionalidades

- **Depósito**: O usuário pode depositar valores positivos em sua conta.
- **Saque**: O usuário pode realizar até 3 saques diários, com limite de R$500 por saque. O sistema verifica se há saldo suficiente antes de permitir o saque.
- **Extrato**: Exibe uma lista de todas as movimentações (depósitos e saques) e o saldo atual da conta.

## Regras do Sistema

1. O sistema não identifica agência ou número da conta, pois foi pensado para apenas um usuário.
2. Depósitos são permitidos apenas com valores positivos.
3. Saques possuem um limite diário de três operações, e cada saque não pode exceder o valor de R$500.
4. Caso o saldo seja insuficiente, o saque não será permitido.
5. Todos os depósitos e saques são registrados no extrato.


