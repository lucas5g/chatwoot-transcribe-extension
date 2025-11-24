# 🚀 Tutorial: Como Gerar uma Chave de API Groq 

Este guia simples mostra como gerar uma chave de API para utilizar os modelos de linguagem grande (LLMs) ultrarrápidos da Groq em seus projetos.

**Site Oficial:** [groq.com](https://groq.com)

---

### 1. Acessar e Fazer Login no GroqCloud Console

1.  Vá para o site oficial da Groq e navegue até a seção de **desenvolvedores** ou **console**.
2.  Faça login em sua conta Groq (o login via Google é uma opção comum).

### 2. Navegar para a Seção de API Keys

1.  Após o login no GroqCloud Console (Dashboard), procure e clique na aba **API Keys** no menu superior.
    
### 3. Criar a Nova Chave de API

1.  Na página **API Keys**, clique no botão **+ Create API Key** (Criar Chave de API).
2.  Na janela pop-up:
    * **Verifique sua identidade** (Complete o desafio de segurança, como um CAPTCHA).
    * **Insira um Nome:** Digite um **nome de exibição** para sua chave (ex: `chave-projeto-x`). Isso ajuda a identificar seu uso.
3.  Clique em **Submit** (Enviar).

### 4. Copiar e Salvar a Chave (Passo Crítico!)

1.  Uma nova janela pop-up será exibida com sua chave de API completa.
2.  **IMPORTANTE:** Clique em **Copy** (Copiar) e **salve esta chave de forma segura** imediatamente.
    * **Aviso:** Esta é a única vez que a chave será exibida por completo. Após fechar esta janela, ela não poderá ser recuperada, apenas excluída e recriada.
3.  Após copiar e salvar, clique em **Done** (Concluído).

Agora você tem sua chave de API Groq (`gsk_...`) pronta para ser usada em seu projeto.


## ⚙️ Tutorial: Como Instalar a Extensão do Navegador Localmente (Modo Desenvolvedor)

Este guia rápido mostra como carregar e instalar a extensão do seu projeto em navegadores baseados em Chromium (como Chrome, Edge, Brave, etc.) usando o **Modo Desenvolvedor**.

---

### 1. Preparação dos Arquivos

1.  Certifique-se de que a pasta da extensão (a pasta que contém o arquivo principal `manifest.json`) esteja **descompactada** em um local de fácil acesso em seu computador.

### 2. Acessar o Gerenciamento de Extensões

1.  Abra o seu navegador (Chrome, Edge, etc.).
2.  Na barra de endereço (URL), digite o seguinte comando e pressione Enter:
    ```
    chrome://extensions
    ```
    *(Se estiver usando o Edge, você pode usar `edge://extensions`)*.
3.  Você será direcionado para a página de gerenciamento de extensões.

### 3. Habilitar o Modo Desenvolvedor

1.  No canto superior direito da página de extensões, localize e ative a chave **Modo Desenvolvedor** (Developer Mode).

### 4. Carregar a Extensão

1.  Com o Modo Desenvolvedor ativado, clique no botão **Carregar sem compactação** (Load unpacked / Carregar descompactada) que apareceu no topo da página.
2.  Na janela de seleção de pastas, **selecione a pasta raiz** da extensão (a pasta que contém o arquivo `manifest.json`).
3.  Clique em **Selecionar Pasta**.

---

### 5. Verificação e Fixação

1.  A extensão será instalada e aparecerá imediatamente na lista de extensões ativas.
2.  Para facilitar o acesso, clique no ícone de peça de quebra-cabeça (Extensões) na barra de ferramentas do seu navegador.
3.  Localize o nome da extensão e clique no ícone de **alfinete** (Pin) para fixá-la na barra de ferramentas.

Sua extensão está instalada e pronta para o desenvolvimento!