# 🎙️ Assistente de Voz com IA (Python)

Este projeto é um assistente virtual inteligente desenvolvido em Python no Google Colab. Ele é capaz de ouvir comandos de voz, processar a linguagem natural usando a API da OpenAI (GPT-3.5) e responder em áudio.

## 🚀 Funcionalidades

- **👂 Audição (Speech-to-Text):** Grava o áudio do microfone e transcreve para texto usando o modelo **Whisper** da OpenAI.
- **🧠 Inteligência (LLM):** Envia a transcrição para o **GPT-3.5 Turbo**, que gera uma resposta contextualizada e útil.
- **🗣️ Fala (Text-to-Speech):** Converte a resposta de texto da IA de volta para áudio usando a biblioteca **gTTS** (Google Text-to-Speech).

## 🛠️ Tecnologias Utilizadas

- **Python**
- **OpenAI API** (GPT-3.5 Turbo e Whisper)
- **gTTS** (Google Text-to-Speech)
- **IPython Display** (Para reprodução de áudio no Colab)
- **FFmpeg** (Processamento de áudio)

## 📦 Como Usar

### Pré-requisitos
Você precisará de uma API Key da OpenAI. [Obtenha aqui](https://platform.openai.com/).

### Executando no Google Colab
1. Clone este repositório ou copie o código para um Notebook do Google Colab.
2. Instale as dependências necessárias:
   ```python
   !pip install openai whisper-openai gTTS ffmpeg-python
Ao executar o código, insira sua OpenAI API Key quando solicitado (o código utiliza getpass para segurança).

Permita o uso do microfone no navegador.

Fale sua pergunta e aguarde a resposta em áudio!

⚠️ Nota de Segurança
Este projeto foi configurado para não expor a API Key no código fonte. Recomenda-se usar variáveis de ambiente ou input seguro (getpass) ao executar.

Desenvolvido por Samuel Maggi
   
