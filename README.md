#  💳 Azure Document Intelligence -  Extração de dados de cartão de crédito

## 📃 Descrição do Projeto

Este projeto demonstra como extrair informações de cartão de crédito de imagens usando o serviço Azure Document Intelligence (anteriormente Form Recognizer) e Python. 

O projeto consiste em um aplicativo Streamlit simples que permite aos usuários fazer upload de imagens de cartões de crédito e visualizar as informações extraídas, como:

* Nome do titular
* Número do cartão
* Data de validade
* CVV
* Bandeira do cartão

## 🚀 Começando

### 💻 Pré-requisitos

* **Python 3.7 ou superior:**  🐍 Baixe e instale a versão mais recente do Python em [https://www.python.org/downloads/](https://www.python.org/downloads/).

* **Gerenciador de Pacotes (pip):**  📦 O pip geralmente é instalado junto com o Python. Verifique se você o tem instalado executando `pip --version` no seu terminal.

* **Conta do Azure:** ☁️ Crie uma conta gratuita do Azure em [https://azure.microsoft.com/free/](https://azure.microsoft.com/free/).

* **Recurso de Inteligência de Documentos do Azure:**  📄 Crie um recurso de Inteligência de Documentos no portal do Azure e obtenha a **chave de endpoint** e a **chave de assinatura**. Anote esses valores, pois você precisará deles mais tarde.

### 📥 Clonando o Repositório

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/your-username/azure-document-intelligence-credit-card.git
   cd azure-document-intelligence-credit-card
🔧 Instalação
Crie um ambiente virtual (recomendado):

Linux/macOS:
python3 -m venv .venv
source .venv/bin/activate
Windows:
python -m venv .venv
.venv\Scripts\activate
Instale as dependências:

pip install -r requirements.txt
⚙️ Configuração
Crie um arquivo .env na raiz do projeto:

ENDPOINT="YOUR_ENDPOINT"
API_KEY="YOUR_API_KEY"
AZURE_STORAGE_CONNECTION_STRING="YOUR_CONNECTION_STRING"
CONTAINER_NAME="YOUR_CONTAINER_NAME"
Substitua os espaços reservados pelos seus valores reais:

YOUR_ENDPOINT: O endpoint do seu recurso de Inteligência de Documentos do Azure.
YOUR_API_KEY: A chave de assinatura do seu recurso de Inteligência de Documentos do Azure.
YOUR_CONNECTION_STRING: A string de conexão da sua conta de armazenamento do Azure.
YOUR_CONTAINER_NAME: O nome do contêiner na sua conta de armazenamento do Azure onde as imagens serão carregadas.
▶️ Executando o aplicativo
Inicie o aplicativo Streamlit:

streamlit run app.py
Acesse o aplicativo:

Abra um navegador da web e navegue até http://localhost:8501/ (ou a URL fornecida pelo Streamlit).
🎉 Uso
Faça upload de uma imagem de cartão de crédito:

Clique no botão "Browse files" e selecione uma imagem do seu computador.
Visualize as informações extraídas:

O aplicativo exibirá a imagem carregada e as informações do cartão de crédito extraídas abaixo dela.
🤝 Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou solicitações pull.

📄 Licença
Este projeto está licenciado sob a Licença MIT - consulte o arquivo LICENSE para obter detalhes.

