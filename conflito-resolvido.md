# Registro de Resolução de Conflito de Merge

Este documento registra a simulação, identificação e resolução de um conflito de integração no repositório.

---

## 1. Cenário
* **Branch Ativa:** `main`
* **Branch Integrada:** `feature/simulacao-conflito`
* **Arquivo Conflitante:** `README.md` (seção de status do projeto)

---

## 2. Causa do Conflito
Alteração concorrente da mesma linha de texto em ramos distintos sem sincronização prévia, gerando divergência que o Git não pôde mesclar automaticamente.

---

## 3. Evidência dos Marcadores de Conflito
```text
<<<<<<< HEAD
Status: Projeto concluído e integrado na branch main.
=======
Status: Projeto em fase de revisão na branch feature/simulacao-conflito.
>>>>>>> feature/simulacao-conflito
