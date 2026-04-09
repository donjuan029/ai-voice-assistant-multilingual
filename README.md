# 🎙️ AI Voice Assistant Multilingual

## 🎯 Contexto

Com o avanço da Inteligência Artificial, assistentes por voz evoluíram de simples executores de comandos para sistemas capazes de compreender, responder e manter contexto em conversas reais.

Este projeto integra tecnologias de Speech-to-Text, LLMs e Text-to-Speech para criar um assistente de voz inteligente, multilíngue e com memória contextual.

## 🚀 Objetivos

- Criar um assistente de voz funcional com IA
- Integrar Whisper, ChatGPT e gTTS
- Implementar memória conversacional
- Permitir comunicação em múltiplos idiomas
- Demonstrar aplicação prática de IA

## ⚙️ Arquitetura

Usuário (voz)

↓
   
Whisper (Speech-to-Text)

↓
   
ChatGPT (Processamento + contexto)

↓
   
gTTS (Text-to-Speech)

↓
   
Resposta em áudio

## 🧠 Tecnologias Utilizadas

- OpenAI (Whisper + ChatGPT)
- Python
- Google Text-to-Speech (gTTS)
- Google Colab

## 🤖 Funcionalidades

- 🎤 Reconhecimento de voz (Speech-to-Text)
- 🌍 Suporte a múltiplos idiomas
- 🧠 Memória de contexto
- 🔊 Resposta em áudio
- 🎓 Modo estudo com IA

## 🧪 Engenharia de Prompts

### Prompt Base
"Você é um assistente inteligente e responde de forma clara e objetiva."

### Prompt com Personalidade
"Você é um especialista em tecnologia e explica conceitos de forma didática."

### Prompt com Contexto
"Considere o histórico da conversa e responda de forma coerente."

## 📌 Conceitos Aprendidos

- Speech-to-Text
- Text-to-Speech
- LLMs
- Engenharia de prompts
- IA aplicada

## 🔑 Configuração da API Key da OpenAI

Para executar este projeto, é necessário possuir uma API Key válida da OpenAI.

### 📌 Como obter sua API Key

1. Acesse: https://platform.openai.com/
2. Crie uma conta ou faça login
3. Acesse: https://platform.openai.com/api-keys
4. Clique em "Create new secret key"
5. Copie sua chave

---

### 🔐 Configuração segura

#### Windows (PowerShell)
setx OPENAI_API_KEY "sua-chave-aqui"

#### Linux / Mac
export OPENAI_API_KEY="sua-chave-aqui"

---

### 🧪 Usando arquivo .env (recomendado)

1. Instale:
pip install python-dotenv

2. Crie o arquivo `.env`:
OPENAI_API_KEY=sua-chave-aqui

3. No código:
from dotenv import load_dotenv
load_dotenv()

---

### ⚠️ Boas práticas

- Nunca compartilhe sua API Key
- Não envie sua chave para o GitHub
- Não coloque a chave diretamente no código
- Utilize variáveis de ambiente

## ▶️ Execução

1. Clone o repositório
git clone https://github.com/donjuan029/ai-voice-assistant-multilingual

2. Acesse a pasta
cd ai-voice-assistant-multilingual

3. Instale as dependências
pip install openai gtts whisper python-dotenv

4. Execute o projeto
python main.py

## 💣 Diferencial do Projeto

Este projeto evolui o modelo tradicional de assistente de voz ao integrar memória contextual, suporte multilíngue e engenharia de prompts, demonstrando aplicação prática de IA moderna em cenários reais.

## 🧠 Insights

- IA por voz é uma das interfaces do futuro
- Contexto melhora drasticamente a qualidade das respostas
- Engenharia de prompts é uma habilidade essencial no mercado

## 📌 Melhorias Futuras

- Interface web (Streamlit)
- Deploy em nuvem
- Integração com RAG (memória avançada)
- Implementação de agentes autônomos
