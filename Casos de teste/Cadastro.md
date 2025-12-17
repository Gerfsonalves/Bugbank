## CT-01 – Cadastro com dados válidos

**Pré-condição:**

* Usuário não possuir cadastro no sistema
* Sistema disponível e acessível

**Passos:**

1. Acessar a página de cadastro
2. Preencher todos os campos obrigatórios com dados válidos
3. Clicar no botão **Cadastrar**

**Resultado Esperado:**

* O sistema deve cadastrar o usuário com sucesso
* Deve ser exibida uma mensagem de confirmação
* O usuário deve ser redirecionado para a página de login ou dashboard

---

## CT-10 – Cadastro com e-mail já existente

**Pré-condição:**

* E-mail já cadastrado no sistema
* Sistema disponível e acessível

**Passos:**

1. Acessar a página de cadastro
2. Informar um e-mail já existente
3. Preencher os demais campos obrigatórios com dados válidos
4. Clicar no botão **Cadastrar**

**Resultado Esperado:**

* O sistema não deve permitir o cadastro
* Deve ser exibida uma mensagem informando que o e-mail já está em uso

---

## CT-11 – Cadastro com campos obrigatórios em branco

**Pré-condição:**

* Sistema disponível e acessível

**Passos:**

1. Acessar a página de cadastro
2. Não preencher um ou mais campos obrigatórios
3. Clicar no botão **Cadastrar**

**Resultado Esperado:**

* O sistema não deve permitir o cadastro
* Devem ser exibidas mensagens de validação nos campos obrigatórios

---

## CT-12 – Cadastro com senha inválida

**Pré-condição:**

* Sistema disponível e acessível

**Passos:**

1. Acessar a página de cadastro
2. Preencher os campos obrigatórios
3. Informar uma senha fora do padrão definido pelo sistema
4. Clicar no botão **Cadastrar**

**Resultado Esperado:**

* O sistema não deve permitir o cadastro
* Deve ser exibida mensagem informando os critérios de senha inválidos