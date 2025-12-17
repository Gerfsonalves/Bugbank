## CT-09 – Transferência com dados válidos

**Pré-condição:**

* Usuário autenticado no sistema
* Saldo disponível suficiente
* Conta de destino válida
* Sistema disponível

**Passos:**

1. Acessar a funcionalidade de transferência
2. Informar conta de destino válida
3. Informar valor válido para transferência
4. Confirmar a operação

**Resultado Esperado:**

* Transferência realizada com sucesso
* Saldo do usuário deve ser atualizado corretamente
* Deve ser exibida mensagem de confirmação da transferência

---
## CT-10 – Transferência com saldo insuficiente

**Pré-condição:**

* Usuário autenticado no sistema
* Saldo insuficiente para o valor informado

**Passos:**

1. Acessar a funcionalidade de transferência
2. Informar conta de destino válida
3. Informar valor maior que o saldo disponível
4. Confirmar a operação

**Resultado Esperado:**

* Transferência não deve ser realizada
* Deve ser exibida mensagem informando saldo insuficiente

---
## CT-11 – Transferência com campos obrigatórios em branco

**Pré-condição:**

* Usuário autenticado no sistema

**Passos:**

1. Acessar a funcionalidade de transferência
2. Não preencher um ou mais campos obrigatórios
3. Confirmar a operação

**Resultado Esperado:**

* Transferência não deve ser realizada
* Devem ser exibidas mensagens de validação nos campos obrigatórios

---
## CT-12 – Transferência para conta inexistente

**Pré-condição:**

* Usuário autenticado no sistema
* Saldo disponível suficiente

**Passos:**

1. Acessar a funcionalidade de transferência
2. Informar conta de destino inexistente
3. Informar valor válido
4. Confirmar a operação

**Resultado Esperado:**

* Transferência não deve ser realizada
* Deve ser exibida mensagem informando conta de destino inválida ou inexistente