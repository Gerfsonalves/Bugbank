## CT-05 – Login com credenciais válidas

**Pré-condição:**

* Usuário previamente cadastrado no sistema
* Sistema disponível e acessível
* Usuário não estar logado

**Passos:**

1. Acessar página de login
2. Informar usuário válido
3. Informar senha válida
4. Clicar em Entrar

**Resultado Esperado:**

* O sistema deve autenticar o usuário com sucesso
* O usuário deve ser redirecionado para a página inicial/dashboard
* O sistema deve iniciar uma sessão válida para o usuário

---
## CT-06 – Login com senha inválida

**Pré-condição:**

* Usuário previamente cadastrado no sistema
* Usuário não estar logado

**Passos:**

01. Acessar a página de login
02. Informar usuário válido
03. Informar senha inválida
04. Clicar no botão Entrar

**Resultado Esperado:**

* O sistema não deve permitir o login
* Deve ser exibida uma mensagem de erro informando credenciais inválidas

---
## CT-07 – Login com usuário inexistente

**Pré-condição:**

* Sistema disponível e acessível

**Passos:**

01. Acessar a página de login
02. Informar usuário inexistente
03. Informar uma senha qualquer
04. Clicar no botão Entrar

**Resultado Esperado:**

* O sistema não deve permitir o login
* Deve ser exibida uma mensagem de erro informando usuário ou senha inválidos

---
## CT-08 – Login com campos obrigatórios em branco

**Pré-condição:**

* Sistema disponível e acessível

**Passos:**

01. Acessar a página de login
02. Deixar o campo usuário e/ou senha em branco
03. Clicar no botão Entrar

**Resultado Esperado:**

* O sistema não deve permitir o login
* Devem ser exibidas mensagens de validação nos campos obrigatórios