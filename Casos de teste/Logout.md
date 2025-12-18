## CT-09 – Logout com sucesso

**Pré-condição:**

* Usuário autenticado no sistema
* Sistema disponível e acessível

**Passos:**

1. Clicar na opção **Logout / Sair** no sistema
2. Confirmar a ação, se aplicável

**Resultado Esperado:**

* A sessão do usuário deve ser encerrada com sucesso
* O usuário deve ser redirecionado para a página de login
* O sistema não deve permitir acesso às páginas internas após o logout

---
## CT-10 – Acesso a páginas internas após logout

**Pré-condição:**

* Usuário realizou logout do sistema

**Passos:**

1. Tentar acessar diretamente uma URL interna do sistema

**Resultado Esperado:**

* O sistema deve bloquear o acesso
* O usuário deve ser redirecionado para a página de login