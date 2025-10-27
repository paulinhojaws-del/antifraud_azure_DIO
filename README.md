# 🧠 Análise de Documentos Antifraude com Azure AI

## 🎯 Objetivo do Projeto
Este projeto demonstra como utilizar o **Azure AI Document Intelligence** (antigo *Form Recognizer*) para **analisar documentos digitalizados** e **identificar possíveis inconsistências ou fraudes** em recibos e comprovantes de despesas.

A aplicação simula um processo de auditoria automatizada, extraindo informações como **nome do comerciante**, **data da transação** e **valor total** de cada documento digitalizado, permitindo detectar anomalias em relatórios financeiros ou reembolsos corporativos.

---

## 🧩 Arquitetura Utilizada

**Serviços do Azure:**
- **Azure AI Document Intelligence (Form Recognizer)** → Usado para extração automática de informações de documentos.  
- **Azure Blob Storage** → Armazenamento dos arquivos digitalizados enviados para análise.  
- **Azure Function (opcional)** →
