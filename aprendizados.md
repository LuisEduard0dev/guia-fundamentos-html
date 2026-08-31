# Relatório de Aprendizados e Boas Práticas

Documento de reflexão sobre os conceitos aplicados durante a estruturação do projeto formativo no GitHub.

---

## 1. Fluxo de Trabalho com Branches
O uso de ramificações (`branches`) permitiu isolar as alterações da documentação sem afetar o código principal na `main`. Isso viabiliza o trabalho colaborativo sem riscos de corromper a versão estável do projeto.

---

## 2. Pull Requests e Revisão Estruturada
A criação de Pull Requests com checklists descritivos garantiu:
* Rastreabilidade das mudanças realizadas.
* Facilidade para revisores identificarem os pontos críticos de inspeção.
* Validação automática de integridade estrutural pelo GitHub antes do merge.

---

## 3. Gestão e Resolução de Conflitos
A simulação de conflito demonstrou que marcadores como `<<<<<<< HEAD`, `=======` e `>>>>>>>` são mecanismos de proteção do Git. A resolução exige leitura crítica do contexto para unificar as alterações sem perda de informação.

---

## 4. Próximos Passos
* Expandir o guia com noções básicas de CSS para estilização dos elementos HTML.
* Implementar automações simples com GitHub Actions para validação contínua de links e formatação Markdown.
