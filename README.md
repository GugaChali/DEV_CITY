# 🌆 DEV_CITY

> *"Não é só um jogo. Escolha uma lenda de Dev City. Ou tire uma selfie e vire uma."*

Aplicação web interativa inspirada no universo **GTA**, desenvolvida com **HTML5, CSS3 e JavaScript**, que permite alternar entre personagens icônicos (Lucia, Jason e CJ) e **transformar uma foto sua em um personagem de videogame com Inteligência Artificial** diretamente no navegador.

## 🚀 Funcionalidades
- **Vire um Personagem com IA:** Upload de foto/selfie convertido em tempo real para o estilo de ilustração de GTA (contornos marcantes, cores vibrantes e fundo transparente) usando **Puter.js**.
- **Seleção de Personagens:** Alternância dinâmica entre **Lucia**, **Jason** e **CJ**, atualizando personagem, nome e paleta de cores na tela.
- **Interface Estilizada:** Tipografia temática (`Bangers`), layout responsivo e manipulação direta do DOM com JavaScript puro.

## 🛠️ Tecnologias Utilizadas
- **HTML5** (Estrutura semântica e captura de arquivos)
- **CSS3** (Layout, posicionamento e estilização visual)
- **JavaScript (ES6+)** (`FileReader`, `async/await` e manipulação do DOM)
- **[Puter.js](https://developer.puter.com/)** (`puter.ai.txt2img` para geração e edição de imagens com IA sem necessidade de expor chaves de API)

## 📂 Estrutura do Projeto

```text
DEV_CITY/
├── img/               # Imagens dos personagens (lucia.png, jason.png, cj.png) e cenários
├── index.html         # Estrutura da página e integração com Puter.js
├── styles.css         # Estilização e layout da interface
├── scripts.js         # Lógica de seleção de personagens e geração de imagem via IA
├── LICENSE            # Licença MIT
└── README.md          # Documentação do projeto
```

## ⚙️ Como executar localmente

> ⚠️ **Importante:** Como o **Puter.js** exige uma origem HTTP/HTTPS válida para autenticar a geração de imagens, abra o projeto através de um servidor local (e não clicando duas vezes no arquivo).

1. Clone o repositório:
   ```bash
   git clone https://github.com
   cd DEV_CITY
   ```
2. Inicie um servidor local:
   * **Com VS Code:** Clique com o botão direito no `index.html` e selecione **"Open with Live Server"**.
   * **Com Python:** Execute `python -m http.server 8000` e acesse `http://localhost:8000`.

## 📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
