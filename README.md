**FinAPI - Financeira**

Requisitos
 Deve ser possível criar uma conta
 Deve ser possível buscar o extrato bancário do cliente
 Deve ser possível realizar um depósito
 Deve ser possível realizar um saque
 Deve ser possível buscar o extrato bancário do cliente por data
 Deve ser possível atualizar dados da conta do cliente
 Deve ser possível obter dados da conta do cliente
 Deve ser possível deletar uma conta
 Deve ser possível retornar o balance

Regras de negócio
 Não deve ser possível cadastrar uma conta com CPF já existente
 Não deve ser possível fazer depósito em uma conta não existente
 Não deve ser possível buscar extrato em uma conta não existente
 Não deve ser possível fazer saque em uma conta não existente
 Não deve ser possível fazer saque quando o saldo for insuficiente
 Não deve ser possível excluir uma conta não existente

O que precisa ter:
/**
 * cfp: string
 * name: string
 * id: uuid => https://medium.com/trainingcenter/o-que-%C3%A9-uuid-porque-us%C3%A1-lo-ad7a66644a2b
 * statement: [] => extrato, lançamentos, debitos, créditos etc.
 */