# Coup Master - Protótipo Online

Este é um protótipo funcional de um jogo de cartas multiplayer em tempo real, baseado no jogo de tabuleiro "Coup". O projeto foi desenvolvido como um aplicativo web estático (HTML, CSS, JS) que utiliza o Firebase Realtime Database para sincronizar o estado do jogo entre todos os jogadores.

![Interface do Jogo](httpsimg/game-screenshot.png)
*(Substitua o link acima por uma captura de tela real do seu jogo!)*

---

## ✨ Funcionalidades

* **Multiplayer em Tempo Real:** Jogue com até 8 jogadores simultaneamente.
* **Sincronização com Firebase:** O estado do jogo (cartas na mão, moedas, jogadores online) é sincronizado em tempo real para todos os clientes.
* **Interface Dinâmica:** Os slots de jogador só aparecem na tela à medida que os jogadores entram na sala.
* **Mecânica de Cartas:** Compre cartas do baralho e arraste-as para diferentes áreas do tabuleiro.
* **Layout Responsivo:** A interface se adapta a layouts de desktop e mobile.
* **Ajuda Interativa:** Um modal "flip-card" exibe as ações de personagens e regras básicas.

---

## 🚀 Tecnologias Utilizadas

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Backend & Database:** Firebase (Realtime Database)
* **Hospedagem:** GitHub Pages

---

## ⚙️ Como Rodar (Instalação)

Este projeto é estático, mas **requer o Firebase** para funcionar.

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    ```

2.  **Crie um Projeto no Firebase:**
    * Vá até o [console do Firebase](https://console.firebase.google.com/).
    * Crie um novo projeto.
    * Adicione um novo "Aplicativo Web" (clicando no ícone `</>`).
    * Copie o objeto `firebaseConfig` que será fornecido.

3.  **Configure o Realtime Database:**
    * No menu do Firebase, vá em **Build > Realtime Database**.
    * Crie um banco de dados.
    * **IMPORTANTE:** Inicie em **modo de teste** (`test mode`) para permitir leitura e escrita durante o desenvolvimento.

4.  **Configure o `index.html`:**
    * Abra o arquivo `index.html`.
    * Encontre o comentário `// 1. INICIALIZAÇÃO E CONFIGURAÇÃO DO FIREBASE`.
    * Cole o seu objeto `firebaseConfig` no local indicado.

5.  **Hospede o Projeto:**
    * Envie seus arquivos (com o `firebaseConfig` preenchido) para o seu repositório do GitHub.
    * Ative o **GitHub Pages** nas configurações do seu repositório e aponte para a branch principal.

Pronto! Agora, qualquer pessoa que acessar o link do seu GitHub Pages entrará na mesma sala de jogo.

---

## 📄 Licença

Este projeto é distribuído sob a licença MIT.