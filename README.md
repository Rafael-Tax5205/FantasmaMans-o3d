# 👻 O Fantasma da Mansão — Edição 2D Clássica & Nova Edição 3D

Jogo multiplayer assimétrico **3 Caçadores vs 1 Fantasma**, desenvolvido para rodar **100% direto no navegador** (PC, Mac, iPhone, iPad e celulares Android), sem precisar instalar executáveis, sem dependência de servidores complexos e sem bloqueios de firewall.

---

## 🌟 Versões Disponíveis no Repositório

### 1. 🎮 Edição 3D Imersiva (`O_Fantasma_da_Mansao_3D.html`)
* **Gráficos 3D WebGL (Three.js r128)** com iluminação dinâmica, sombras suaves e tochas nas paredes.
* **Câmeras em 3ª Pessoa (TPS) e 1ª Pessoa (FPS)** alternáveis em tempo real (tecla `C`).
* **Facho Volumétrico da Lanterna** cortando a escuridão da mansão.
* **3 Fases 3D Completas**:
  1. 🏰 *Mansão Gótica 3D*
  2. 🏥 *Hospital Sombrio 3D*
  3. ⚰️ *Catacumbas & Criptas 3D*
* **Multiplayer P2P WebRTC** por código de 4 dígitos entre PC e Celulares.
* **Controles Dual-Touch nos Celulares** (Analógico Esquerdo para Andar + Analógico Direito para Mirar Lanterna/Câmera de forma totalmente independente) e **WASD + Mouse no PC**.
* **Bots com IA**: patrulham as salas, recolhem relíquias e reagem à presença do Fantasma.

### 2. 🕹️ Edição Clássica 2D (`index.html` / `O_Fantasma_da_Mansao.html`)
* Visão tática superior 2D com algoritmo de oclusão de visão (Fog of War e Raycasting).
* Suporte a 3 fases sorteadas, 3 cargas de trava por caçador, feedback tátil por vibração nos celulares e client-side prediction a 60 FPS.

---

## 🚀 Como Publicar no GitHub Pages (Para Jogar Online com Todo Mundo)

1. Crie um novo repositório no seu GitHub (exemplo: `o-fantasma-da-mansao`).
2. Faça o upload de todos os arquivos deste projeto:
   * `index.html` (ou copie `O_Fantasma_da_Mansao_3D.html` como `index.html` se quiser que a versão 3D abra direto na raiz)
   * `O_Fantasma_da_Mansao_3D.html`
   * `O_Fantasma_da_Mansao.html`
   * `three.min.js`
3. No GitHub, vá em **Settings** ➔ **Pages**.
4. Em **Build and deployment** / **Branch**, selecione `main` (ou `master`) e pasta `/ (root)`, depois clique em **Save**.
5. Pronto! Em 1 minuto seu jogo estará online gratuitamente na URL:
   `https://SEU_USUARIO.github.io/o-fantasma-da-mansao/O_Fantasma_da_Mansao_3D.html`

---

## 📱 Como Jogar Juntos (PC + Celulares)

1. O jogador que estiver no **PC ou Notebook** abre o jogo e clica em **💻 Criar Código da Sala neste PC (Host)**.
2. Um código de 4 dígitos será gerado (ex: `4821`).
3. Os outros jogadores abrem o link nos **celulares**, digitam o código de 4 dígitos no campo e tocam em **Entrar**.
4. Todos entram na mesma sala instantaneamente via WebRTC P2P (conexão direta ponto a ponto).
5. O Host clica em **▶ INICIAR PARTIDA 3D** e o jogo começa sincronizado para todos!
