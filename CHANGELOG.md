# 📂 CHANGELOG — Modelagem de Banco de Dados

Este documento registra as principais alterações feitas no modelo `.mwb` e seus arquivos exportados. Use para acompanhar o progresso do projeto, validar contribuições e manter a transparência.

---

## 📅 [2025-07-05] - Primeira versão publicada
### Adicionado
- Modelo inicial criado no MySQL Workbench (`modelo.mwb`)
- Exportação para arquivo `.sql` e imagem `.png` adicionadas ao repositório
- Estrutura básica com tabelas: `clientes`, `pedidos`, `produtos`


## 💡 EXEMPLO DE FUTUROS CHANGELOGS

---

## 📅 [2025-07-06] - Atualização na estrutura de pedidos
### Alterado
- Campo `status` da tabela `pedidos` renomeado para `situacao`
- Tipo de dado do campo `valor_total` ajustado para `DECIMAL(10,2)`

### Removido
- Tabela intermediária `pedido_itens_temp` foi excluída por duplicidade

---

## 📅 [2025-07-07] - Inclusão de controle de pagamentos
### Adicionado
- Tabela `pagamentos` com campos: `id_pagamento`, `numero_cartao`, `data_pagamento`
- Relacionamento entre `pedidos` e `pagamentos` criado no DER

---

## 🔄 Como manter este arquivo atualizado

- Ao fazer um commit com alterações relevantes no `.mwb`, adicione um novo bloco neste changelog.
- Use datas reais e verbos claros: `Adicionado`, `Alterado`, `Removido`, `Corrigido`, `Reestruturado`, etc.
- Mantenha consistência na descrição das mudanças.

---

> 🔔 Lembre-se: mudanças pequenas também merecem ser registradas. Isso valoriza o esforço da equipe e facilita decisões futuras.
