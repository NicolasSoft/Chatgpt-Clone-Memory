# 🤖 ChatGPT Clone com Memória de Conversa

Projeto desenvolvido em Python que simula um chatbot estilo ChatGPT, com **memória de contexto**, utilizando as tecnologias **LangChain**, **OpenAI API** e **Gradio**.

## 💡 Funcionalidades

- Interface de chat responsiva com Gradio
- Memória de conversa (contexto dinâmico)
- Integração com modelos LLM da OpenAI (ex: GPT-3.5, GPT-4)
- Arquitetura simples e extensível para futuros aprimoramentos

## 🛠️ Tecnologias utilizadas

- Python
- LangChain
- OpenAI API
- Gradio
- Dotenv (para variáveis de ambiente)

## 🚀 Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/chatgpt-clone-memory.git
cd chatgpt-clone-memory

# Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate  # Windows: venv\\Scripts\\activate

# Instale as dependências
pip install -r requirements.txt

# Crie o arquivo .env com sua chave da OpenAI
echo \"OPENAI_API_KEY=sua-chave-aqui\" > .env

# Inicie o app
python app.py

