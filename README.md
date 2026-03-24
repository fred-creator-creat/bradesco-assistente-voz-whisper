# 🎙️ Assistente Virtual Inteligente: Voz + GenAI (Projeto DIO & Bradesco)

Este repositório contém o projeto do bootcamp da **Bradesco - GenAI & Dados** em parceria com a **DIO**. Desenvolvi uma assistente de voz interativa que utiliza modelos de última geração para audição, processamento de linguagem e fala.

## 🚀 Evoluções e Diferenciais do Projeto
Diferente da estrutura básica, este projeto foi aprimorado com:
- **Inteligência Artificial (Gemini 2.5 Flash):** Implementação da versão mais recente da API do Google para respostas rápidas e precisas.
- **Ajuste de Fuso Horário:** Lógica Python para correção automática do horário de Brasília (GMT-3), garantindo que a assistente informe a hora certa no Brasil.
- **Segurança com Google Secrets:** Uso da biblioteca `userdata` do Colab para proteger a API Key, evitando a exposição de dados sensíveis no código.
- **Interação Natural:** Sistema de encerramento via voz (comandos como "Sair" ou "Tchau").

## 🛠️ Tecnologias e Ferramentas
Clique nos links abaixo para acessar a documentação oficial:

* **[Python](https://www.python.org/):** Linguagem base do projeto.
* **[Google Gemini API](https://ai.google.dev/):** Cérebro da assistente (Modelo 2.5 Flash).
* **[OpenAI Whisper](https://github.com/openai/whisper):** Reconhecimento de fala (Speech-to-Text).
* **[gTTS (Google Text-to-Speech)](https://pypi.org/project/gTTS/):** Conversão de texto para voz brasileira.
* **[Google Colab](https://colab.research.google.com/):** Ambiente de execução em nuvem.

## 📂 Estrutura do Código
Você pode visualizar o código fonte diretamente aqui:
👉 **[Acesse o Notebook do Projeto](./Desafio_Bradesco_Assistente_GenAI_Whisper.ipynb)**

---

## 📋 Como Executar o Projeto
1. Abra o arquivo no **Google Colab**.
2. No menu lateral, clique no ícone de chave (**Secrets**) e adicione sua chave:
   - Nome: `GOOGLE_API_KEY`
   - Valor: `Sua_Chave_Aqui`
   - Ative a opção "Acesso ao notebook".
3. Execute as células em ordem (1 a 5).
4. Quando aparecer "Ouvindo...", interaja com a assistente por voz.

---

## 👨‍💻 Desenvolvedor
**Fred**
* *Técnico em Desenvolvimento de Sistemas*
* *Estudante de Machine Learning & Data Analytics*

---

### 🎓 Instituições Parceiras
* **[DIO (Digital Innovation One)](https://www.dio.me/)**
* **[Bradesco](https://www.bradesco.com.br/)**
