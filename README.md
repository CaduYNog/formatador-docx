# 📝 Formatador de Provas em .docx

Este projeto é um script em **Python** que automatiza o processo de formatação de arquivos `.docx`, usado principalmente para provas ou avaliações escolares.

## 🚀 Funcionalidades
- Remove conteúdo do documento a partir da palavra **"INÍCIO"**.
- Aplica formatação padrão:
  - Fonte **Arial**, tamanho **10**.
  - Espaçamento simples (1.0).
  - Sem espaço antes e depois de parágrafos.
- Extrai e lista alternativas de questões no formato `A) opção`.
- Identifica alternativas **duplicadas**.

## 📂 Estrutura
- `prova.docx` → Documento inicial.
- `prova_limpa.docx` → Documento após remoção de conteúdo indesejado.
- `prova_montada.docx` → Documento montado antes da formatação.
- `prova_final.docx` → Documento final, limpo e formatado.

## ⚙️ Tecnologias
- [python-docx](https://python-docx.readthedocs.io/en/latest/)  
- [re (expressões regulares)](https://docs.python.org/3/library/re.html)  
- [collections.Counter](https://docs.python.org/3/library/collections.html#collections.Counter)
