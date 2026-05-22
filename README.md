# Agente de Processamento de Faturas de IA

## Objetivo
Automatizar o processamento de notas fiscais e faturas recebidas por e-mail utilizando IA generativa.

---

## Tecnologias utilizadas

- n8n
- Google Gemini
- Gmail Trigger
- Google Drive
- Google Sheets

---

## Fluxo do processo

1. Recepciona e-mail com anexo
2. Identifica PDF
3. Extrai dados usando Gemini
4. Classifica despesa
5. Salva no Google Drive
6. Registra no Google Sheets

---

## Evidências

### Workflow completo
![Workflow](imagem/01-workflow-completo.png)

---

### Execução concluída com sucesso
![Execução](imagem/02-execucao-sucesso.png)

---

### Resultado no Google Sheets
![Sheets](imagem/03-google-sheets-resultados.png)

---

### Drive Pessoal
![Drive Pessoal](imagem/04-drive-pessoal.png)

---

### Drive Corporativo
![Drive Corporativo](imagem/05-drive-corporativo.png)

---

## Arquivo do Workflow

O arquivo `n8n_workflow_sanitized.json` contém o workflow exportado sem credenciais.

---

## Objetivo técnico

Este projeto demonstra:

- Automação inteligente de processos
- Processamento automatizado de documentos
- Extração de dados utilizando IA Generativa
- Integração entre serviços Google
- Orquestração de workflows com n8n

---

## Observações

As credenciais e informações sensíveis foram removidas antes da publicação do projeto.
