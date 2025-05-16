# Streamlit Chat App

![Logo do Projeto]https://github.com/ItaloRochaj/streamlit-chat-app/blob/main/streamlit-chat-app/imagens%20do%20projeto/logo.jpg

## Visão Geral

O **Streamlit Chat App** é uma aplicação de chat inteligente desenvolvida em Python utilizando o framework Streamlit. O objetivo principal é oferecer uma interface acessível para advogados e profissionais do direito analisarem documentos jurídicos com o auxílio de inteligência artificial, tornando a análise documental mais rápida, precisa e acessível.

---

## Motivação e Conceitos

A crescente demanda por automação e eficiência no setor jurídico motivou a criação deste projeto. Muitos profissionais enfrentam desafios ao analisar grandes volumes de documentos, identificar informações relevantes e tomar decisões estratégicas rapidamente. O uso de IA aplicada ao Direito (LegalTech) pode transformar esse cenário, democratizando o acesso à análise jurídica de qualidade.

O projeto foi idealizado para:
- **Acelerar a triagem e análise de documentos jurídicos** (petições, sentenças, contratos, etc.).
- **Reduzir erros humanos** na identificação de partes, prazos, valores e fundamentos legais.
- **Apoiar advogados iniciantes** com linguagem técnica acessível e sugestões de estratégias jurídicas.
- **Promover inovação e inclusão digital** no setor jurídico brasileiro.

---

## Tecnologias Utilizadas

- **Python 3.12**: Linguagem principal do projeto.
- **Streamlit**: Framework para construção rápida de interfaces web interativas.
- **Boto3**: SDK para integração com serviços AWS, especialmente Amazon Bedrock.
- **Amazon Bedrock**: Serviço de IA generativa da AWS, utilizado para análise e geração de respostas jurídicas.
- **PyPDF2**: Leitura e extração de texto de arquivos PDF.
- **Pandas**: Manipulação de dados em arquivos CSV.
- **Autenticação customizada**: Middleware próprio para login seguro via cookies.
- **Docker** (opcional): Para facilitar a implantação em ambientes isolados.
- **Git/GitHub**: Versionamento e colaboração.

---

## Como Funciona

1. **Login Seguro**: Apenas usuários autenticados podem acessar o chat.
2. **Upload de Documentos**: O usuário pode enviar arquivos PDF, TXT ou CSV para análise.
3. **Contexto Adicional (RAG)**: Possibilidade de adicionar contexto manualmente ou via arquivo.
4. **Chat com IA Jurídica**: O usuário interage com uma assistente treinada para analisar documentos, extrair informações-chave e sugerir estratégias jurídicas.
5. **Histórico de Conversas**: Todas as interações são salvas, permitindo consulta e acompanhamento.
6. **Interface Intuitiva**: Desenvolvida para ser simples, responsiva e amigável, mesmo para quem não tem experiência em tecnologia.

---

## Aplicabilidade na Sociedade

- **Advocacia e Escritórios Jurídicos**: Automatização da análise de processos, petições e contratos.
- **Defensoria Pública**: Apoio a profissionais com alta demanda e poucos recursos.
- **Ensino Jurídico**: Ferramenta de apoio para estudantes e professores de Direito.
- **Cidadãos**: Democratização do acesso à informação jurídica de qualidade.
- **Inovação no Judiciário**: Potencial para integração com sistemas de tribunais e órgãos públicos.

---

## Estrutura do Projeto

```
streamlit-chat-app/
│
├── streamlit/
│   ├── app.py                # Aplicação principal Streamlit
│   ├── functions.py          # Funções utilitárias e integração com IA
│   ├── auth_middleware.py    # Middleware de autenticação
│   ├── .env / .env.local     # Variáveis de ambiente (perfil AWS)
│   ├── logo.jpeg             # Logotipo do projeto
│
├── requirements.txt          # Dependências do projeto
├── .gitignore                # Arquivos e pastas ignorados pelo Git
├── README.md                 # Este arquivo
```

---

## Como Executar

1. **Clone o repositório:**
   ```sh
   git clone <repository-url>
   cd streamlit-chat-app/streamlit-chat-app
   ```

2. **Instale as dependências:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Configure as variáveis de ambiente AWS:**
   - Edite `.env` ou `.env.local` com seu perfil AWS.

4. **Execute a aplicação:**
   ```sh
   streamlit run streamlit/app.py
   ```

5. **Acesse em:** [http://localhost:8501](http://localhost:8501)

---

## Demonstração

### Tela de Login

![Tela de Login](docs/login.png)

### Tela Principal do Chat

![Tela Principal](docs/chat.png)

### Upload de Documentos

![Upload de Documentos](docs/upload.png)

---

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

---

## Licença

MIT License. Consulte o arquivo LICENSE para mais detalhes.

---
