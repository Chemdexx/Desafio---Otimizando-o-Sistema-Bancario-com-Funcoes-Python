# Desafio de Projeto - Otimizando o Sistema Bancário com Funções Python

## Regras de Negócio
### Geral
    Separar as funcionalidades existentes de saque, depósito e extrato em funções.
    Criar duas novas funções: criar usuário (cliente) e criar conta corrente.
    Cada função deve ter uma regra na passagem de argumentos.
    
### Saque
    A função saque deve receber os argumentos apenas por nome (keyword only).
    
### Depósito
    A função de depósito deve receber os argumentos apenas por posição (positional only).
    
### Extrato
    A função extrato deve receber os argumentos por posição e nome (positional only e keyword only).
    
### Criar Usuário
    O programa deve armazenar os usuários em uma lista, um usuário é composto por: nome, data de nascimento, cpf e endereço.
    O endereço é uma string com o formato: logradouro, nro - bairro - cidade/sigla estado. Deve ser armazenado somente os números do CPF. Não permitir cadastrar 2 usuários com o mesmo CPF.

### Criar conta corrente
    O programa deve armazenar contas em uma lista, uma conta é composta por: agência, número da conta e usuário.
    O número da conta é sequencial, iniciando em 1. O número da agência é fixo: "001". O usuário pode ter mais de uma conta, mas uma conta só pode pertencer a uma único usuário.
