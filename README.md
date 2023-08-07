# conta-bancaria-api
Exercicio de criação de API de conta bancária com Spring.

## Funcionalidades

- Exibir de todos as contas;
- Exibir de uma conta específica;
- Cadastro de uma nova conta;
- Deleção de uma conta;
- Atualização do valor atual caso tenha um depósito;
- Atualização do valor atual caso tenha um saque.

### Especificações

- id;
- numero de conta;
- agencia;
- nome do usuario;
- saldo;
- valor fornecido para saque ou deposito (valor a ser acrescido ou subtraído no valor final);
- tipo de serviço (saque ou depósito);

### Tratamento de exceções
- DataIntegrityViolationException
- MethodArgumentTypeMismatchException
- HttpMessageNotReadableException

