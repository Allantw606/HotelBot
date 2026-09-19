# 🏨 Hotel Assistant Bot - Google Gemini

## Descrição do Projeto

Este projeto consiste no desenvolvimento de um chatbot especialista em atendimento hoteleiro utilizando inteligência artificial através do Google Gemini.

O objetivo é criar um assistente virtual capaz de responder perguntas utilizando uma base de conhecimento privada, evitando respostas inventadas pelo modelo (alucinações).

O chatbot foi desenvolvido em Python utilizando o ambiente Google Colab e a API do Google Gemini.

## Funcionalidades

- Integração com o modelo Google Gemini;
- Base de conhecimento privada sobre um hotel fictício;
- Respostas direcionadas ao contexto informado;
- Controle para evitar respostas fora da base de conhecimento;
- Limite de três perguntas por interação;
- Geração de resumo final da conversa.

## Tecnologias utilizadas

- Python;
- Google Colab;
- Google Gemini API;
- Biblioteca google-genai.

## Estrutura do projeto

```
HotelBot/
│
├── HotelBot_final.ipynb
├── README.md
└── .env.example
```

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Instalar a biblioteca necessária

No Google Colab ou ambiente Python:

```bash
pip install google-genai
```

### 3. Configurar a chave da API

Crie uma chave de API do Google Gemini.

Depois utilize o arquivo `.env.example` como referência para configurar a variável:

```
GOOGLE_API_KEY=SUA_CHAVE_AQUI
```

Nunca publique uma chave real no GitHub.

### 4. Executar o notebook

Abra:

```
HotelBot_final.ipynb
```

Execute as células em sequência.

## Demonstração

O chatbot deve ser testado com três tipos de perguntas:

1. Pergunta sobre uma informação existente na base de conhecimento;
2. Pergunta sobre regras do hotel;
3. Pergunta sobre uma informação inexistente, verificando se o chatbot evita inventar respostas.

## Objetivo acadêmico

O projeto demonstra uma aplicação prática de modelos de linguagem com contexto controlado, utilizando uma base específica para direcionar as respostas da inteligência artificial.
