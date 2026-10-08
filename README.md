# 🤖 Laboratório Prático: Configuração e Uso do Azure AI Language Studio

Este repositório documenta a resolução prática do desafio de configuração e testes utilizando os serviços de Linguagem do Azure AI, focado na preparação para a certificação AI-900.

## 🚀 Objetivo
Aplicar conceitos de Processamento de Linguagem Natural (NLP), configurar recursos no portal do Azure e realizar testes de análise de sentimentos e extração de frases-chave.

## 🔧 Desafios Superados (Troubleshooting)
Durante o acesso ao portal [Language Studio](https://azure.com), foi enfrentado o erro de autenticação `AADSTS500200` devido à restrição de contas pessoais (`@hotmail.com`).
* **Solução:** Foi realizada a extração do **ID do Locatário (Tenant ID)** diretamente no painel do *Microsoft Entra ID* no Azure e gerada uma URL customizada para forçar a autenticação no diretório correto em uma guia anônima.

## 📝 Testes Realizados
Utilizando o recurso de idioma criado (`lailanguageai900`), foram processadas análises com textos fornecidos pela Microsoft:
* **Texto de Teste:** `I had a wonderful stay at the hotel. The staff was friendly and the room was very clean.`
* **Ferramentas aplicadas:** Sentiment Analysis e Key Phrase Extraction.

## 📂 Estrutura do Repositório
* `/images`: Capturas de tela do processo de configuração e resolução de problemas.
* `README.md`: Documentação oficial do projeto.
