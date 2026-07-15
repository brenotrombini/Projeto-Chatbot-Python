# 🤖 Trombini Assistant

Chatbot inteligente desenvolvido com **Python**, **Streamlit** e a **API da OpenAI (GPT-4o)**. O projeto oferece uma interface de chat simples e responsiva, com histórico de conversa mantido durante a sessão.

## 📋 Sobre o projeto

O Trombini Assistant é uma aplicação web de chat que permite ao usuário conversar com um modelo de linguagem da OpenAI diretamente pelo navegador. A cada mensagem enviada, a aplicação:

1. Exibe a mensagem do usuário no chat
2. Envia a pergunta para o modelo de IA (GPT-4o)
3. Recebe e exibe a resposta da IA no chat
4. Mantém o histórico da conversa durante a sessão

## 🚀 Tecnologias utilizadas

- [Python 3](https://www.python.org/)
- [Streamlit](https://streamlit.io/) — interface web
- [OpenAI API](https://platform.openai.com/) — modelo GPT-4o
- [python-dotenv](https://pypi.org/project/python-dotenv/) — gerenciamento de variáveis de ambiente

## 📁 Estrutura do projeto

```
projeto-chatbox/
├── main.py            # código principal da aplicação
├── requirements.txt   # dependências do projeto
├── .env                # variáveis de ambiente (não versionado)
├── .gitignore
└── README.md
```

## ⚙️ Pré-requisitos

- Python 3.9 ou superior instalado
- Uma chave de API válida da OpenAI ([criar aqui](https://platform.openai.com/api-keys))

## 🔧 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/brenotrombini/Projeto-Chatbot-Python.git
cd Projeto-Chatbot-Python
```

2. Crie e ative um ambiente virtual:
```bash
python -m venv venv
```

No Windows (PowerShell):
```bash
.\venv\Scripts\Activate.ps1
```

No Linux/Mac:
```bash
source venv/bin/activate
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

Ou, se preferir instalar manualmente:
```bash
pip install streamlit openai python-dotenv
```

## 🔑 Configuração da API Key

Crie um arquivo `.env` na raiz do projeto com a sua chave da OpenAI:

```
OPENAI_API_KEY=sua_chave_aqui
```

> ⚠️ **Importante:** nunca compartilhe ou suba sua chave de API para o GitHub. O arquivo `.env` já está listado no `.gitignore` para evitar isso.

## ▶️ Como executar

Com o ambiente virtual ativado e as dependências instaladas, rode:

```bash
streamlit run main.py
```

A aplicação será aberta automaticamente no navegador, geralmente em `http://localhost:8501`.

## 💬 Como usar

1. Digite sua pergunta no campo de texto na parte inferior da tela
2. Pressione Enter
3. Aguarde a resposta da IA aparecer no chat
4. Continue a conversa normalmente — o histórico é mantido durante a sessão

## 🗺️ Possíveis melhorias futuras

- [ ] Persistir o histórico de conversas em banco de dados
- [ ] Adicionar seleção de diferentes modelos da OpenAI
- [ ] Adicionar autenticação de usuários
- [ ] Implementar limite de tokens/custos por conversa
- [ ] Deploy em produção (Streamlit Cloud, Render, etc.)

## 👤 Breno Trombini

**Breno Trombini Tertuliano**
- GitHub: [@brenotrombini](https://github.com/brenotrombini)
- LinkedIn: [breno-trombini-tertuliano](https://www.linkedin.com/in/breno-trombini-tertuliano-b2ab50342)

## 📄 Licença

Este projeto está disponível para fins de estudo e portfólio.
