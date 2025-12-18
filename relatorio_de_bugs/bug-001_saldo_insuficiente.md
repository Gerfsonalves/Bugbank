# 🐞 Relatório de Bug – BugBank

## ID do Bug

BUG-001

---

## Título

Transferência é realizada mesmo com saldo insuficiente

---

## Descrição

Ao realizar uma tentativa de transferência com valor superior ao saldo disponível na conta, o sistema permite a conclusão da operação, o que viola a regra básica de negócio de um sistema bancário.

---

## Ambiente

* Aplicação: BugBank
* URL: [https://bugbank.netlify.app/](https://bugbank.netlify.app/)
* Navegador: Google Chrome
* Sistema Operacional: Windows 10/11

---

## Pré-condição

* Usuário autenticado no sistema
* Conta de origem com saldo inferior ao valor a ser transferido

---

## Passos para Reproduzir

1. Acessar o sistema BugBank
2. Realizar login com usuário válido
3. Acessar a funcionalidade de transferência
4. Informar uma conta de destino válida
5. Informar um valor maior que o saldo disponível
6. Confirmar a transferência

---

## Resultado Atual

O sistema realiza a transferência mesmo sem saldo suficiente na conta de origem.

---

## Resultado Esperado

O sistema deve bloquear a operação e exibir uma mensagem informando saldo insuficiente.

---

## Severidade

Alta

---

## Prioridade

Alta

---

## Status

Aberto

---

## Evidências

* (Adicionar print ou vídeo da execução)

---

## Observações

Este bug impacta diretamente a integridade financeira do sistema e pode gerar inconsistências de saldo.

---

👤 **Reportado por:** Gerfson Alves
📅 **Data:** 17/12/2025
