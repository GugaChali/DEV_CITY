<div align="center">

# 🌆 DEV_CITY

**"It's not just a game. Choose a Dev City legend. Or take a selfie and become one."**  
**"Não é só um jogo. Escolha uma lenda de Dev City. Ou tire uma selfie e vire uma."**

![HTML5](https://shields.io)
![CSS3](https://shields.io)
![JavaScript](https://shields.io)
![Puter.js](https://shields.io)
![License](https://shields.io)

[🇺🇸 English](#-english) • [🇧🇷 Português](#-português)

</div>

---

## 🇺🇸 English

An interactive web application inspired by the **GTA universe**, built with **HTML5, CSS3, and Vanilla JavaScript**. Switch between iconic characters (Lucia, Jason, and CJ) or upload your own selfie to turn yourself into a video game character using **Artificial Intelligence** right in the browser.

### ✨ Features

- 🤖 **Become an AI Character:** Upload a selfie/photo and convert it in real time into a GTA-style illustration (bold outlines, vibrant colors, and transparent background) powered by `Puter.js`.
- 🎮 **Character Selection:** Dynamic switching between **Lucia**, **Jason**, and **CJ**, updating the character artwork, name, and UI color palette on the fly.
- 🎨 **Stylized Interface:** Thematic typography (*Bangers*), responsive layout, and pure JavaScript DOM manipulation.

### 🛠️ Tech Stack

- **HTML5:** Semantic structure and file input capture.
- **CSS3:** Responsive layout, positioning, and custom visual themes.
- **JavaScript (ES6+):** `FileReader` API, `async/await`, and dynamic DOM manipulation.
- **Puter.js (`puter.ai.txt2img`):** Client-side AI image generation/editing without exposing API keys.

### 📂 Project Structure

```text
DEV_CITY/
├── img/               # Character sprites (lucia.png, jason.png, cj.png) & backgrounds
├── index.html         # Main page structure and Puter.js CDN integration
├── styles.css         # Styling, themes, and responsive layout
├── scripts.js         # Character selection logic & AI image generation
├── LICENSE            # MIT License
└── README.md          # Project documentation
```

### ⚙️ Running Locally

> ⚠️ **Important:** `Puter.js` requires a valid `HTTP/HTTPS` origin to authenticate AI image requests. Do **not** open `index.html` directly via `file://`.

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd DEV_CITY
   ```

2. **Start a local server:**
   - **Using VS Code:** Right-click `index.html` and select **"Open with Live Server"**.
   - **Using Python:**
     ```bash
     python -m http.server 8000
     ```
     Then open `http://localhost:8000` in your browser.

---

## 🇧🇷 Português

Aplicação web interativa inspirada no **universo GTA**, desenvolvida com **HTML5, CSS3 e JavaScript puro**. Alterne entre personagens icônicos (Lucia, Jason e CJ) ou envie uma selfie para transformar você mesmo em um personagem de videogame usando **Inteligência Artificial** diretamente no navegador.

### ✨ Funcionalidades

- 🤖 **Vire um Personagem com IA:** Faça upload de uma foto/selfie e converta em tempo real para o estilo de ilustração de GTA (contornos marcantes, cores vibrantes e fundo transparente) usando `Puter.js`.
- 🎮 **Seleção de Personagens:** Alternância dinâmica entre **Lucia**, **Jason** e **CJ**, atualizando personagem, nome e paleta de cores da interface automaticamente.
- 🎨 **Interface Estilizada:** Tipografia temática (*Bangers*), layout responsivo e manipulação direta do DOM.

### 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica e captura de arquivos.
- **CSS3:** Layout responsivo, posicionamento e estilização visual.
- **JavaScript (ES6+):** API `FileReader`, `async/await` e manipulação dinâmica do DOM.
- **Puter.js (`puter.ai.txt2img`):** Geração e edição de imagens com IA no navegador sem necessidade de expor chaves de API.

### 📂 Estrutura do Projeto

```text
DEV_CITY/
├── img/               # Imagens dos personagens (lucia.png, jason.png, cj.png) e cenários
├── index.html         # Estrutura da página e integração com Puter.js
├── styles.css         # Estilização, temas e layout responsivo
├── scripts.js         # Lógica de seleção de personagens e geração de imagem via IA
├── LICENSE            # Licença MIT
└── README.md          # Documentação do projeto
```

### ⚙️ Como Executar Localmente

> ⚠️ **Importante:** O `Puter.js` exige uma origem `HTTP/HTTPS` válida para autenticar a geração de imagens. **Não** abra o arquivo `index.html` diretamente clicando duas vezes nele (`file://`).

1. **Clone o repositório:**
   ```bash
   git clone https://github.com
   cd DEV_CITY
   ```

2. **Inicie um servidor local:**
   - **Com VS Code:** Clique com o botão direito em `index.html` e selecione **"Open with Live Server"**.
   - **Com Python:**
     ```bash
     python -m http.server 8000
     ```
     Em seguida, acesse `http://localhost:8000` no navegador.

---

## 📄 License / Licença

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.  
Este projeto está sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

<div align="center">
  Developed with 💻 by <a href="https://github.com"><strong>Gustavo Monteiro (GugaChali)</strong></a>
</div>
