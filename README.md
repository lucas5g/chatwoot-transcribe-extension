# 🚀 Tutorial: Como Gerar uma Chave de API Groq (API Key)

Este guia simples mostra como gerar uma chave de API para utilizar os modelos de linguagem grande (LLMs) ultrarrápidos da Groq em seus projetos.

**Site Oficial:** [groq.com](https://groq.com)

---

### 1. Acessar e Fazer Login no GroqCloud Console

1.  Vá para o site oficial da Groq e navegue até a seção de **desenvolvedores** ou **console** (Geralmente, há um botão "Get Started" ou "Free API Key").
2.  Faça login em sua conta Groq (o login via Google é uma opção comum).

### 2. Navegar para a Seção de API Keys

1.  Após o login no GroqCloud Console (Dashboard), procure e clique na aba **API Keys** no menu superior.
    
### 3. Criar a Nova Chave de API

1.  Na página **API Keys**, clique no botão **+ Create API Key** (Criar Chave de API).
2.  Na janela pop-up:
    * **Verifique sua identidade** (Complete o desafio de segurança, como um CAPTCHA).
    * **Insira um Nome:** Digite um **nome de exibição** para sua chave (ex: `chave-projeto-x`). Isso ajuda a identificar seu uso.
3.  Clique em **Submit** (Enviar).

---

### 4. Copiar e Salvar a Chave (Passo Crítico!)

1.  Uma nova janela pop-up será exibida com sua chave de API completa.
2.  **IMPORTANTE:** Clique em **Copy** (Copiar) e **salve esta chave de forma segura** imediatamente.
    * **Aviso:** Esta é a única vez que a chave será exibida por completo. Após fechar esta janela, ela não poderá ser recuperada, apenas excluída e recriada.
3.  Após copiar e salvar, clique em **Done** (Concluído).

Agora você tem sua chave de API Groq (`gsk_...`) pronta para ser usada em seu projeto.

---

### 💡 Dica de Segurança: Usando Variáveis de Ambiente

Para manter sua chave de API segura e longe do seu código-fonte, use-a como uma **variável de ambiente**.

1.  Crie um arquivo `.env` (se ainda não tiver um) na raiz do seu projeto.
2.  Adicione a chave neste formato:

    ```
    # Arquivo .env
    GROQ_API_KEY="SUA_CHAVE_COMPLETA_AQUI" 
    ```

3.  Certifique-se de adicionar o arquivo **`.env`** ao seu arquivo **`.gitignore`** para que ele nunca seja enviado para o GitHub.