# 🎸 Palco Aberto

**Gerenciador de cifras e setlists open source, feito para a realidade do palco.**

O **Palco Aberto** nasceu para resolver uma dor comum de músicos de bar e eventos ao vivo: sites e aplicativos de cifras cheios de anúncios, pop-ups, cliques excessivos e dependência de internet. Aqui o foco é leitura limpa, velocidade e zero distrações na hora de tocar.

👉 **[Acessar o Palco Aberto agora](https://lucasmenezescont.github.io/palcoaberto/)**

---

## ✨ O que já funciona

* **PWA Instalável e 100% Offline:** pode ser instalado na tela inicial do celular ou tablet (Android, iOS e Desktop) em tela cheia e abre normalmente mesmo em Modo Avião.
* **Banco de Dados Local (`IndexedDB`):** todas as suas cifras, PDFs e setlists ficam salvos diretamente no seu dispositivo, sem precisar de conta para usar.
* **Sincronização com Google Drive *(Beta)*:** conecte sua própria conta Google para sincronizar repertório, PDFs e setlists entre computador, celular e tablet. O app cria uma pasta visível **`Palco Aberto`** no seu Drive e só acessa os arquivos criados por ele mesmo (`drive.file`).
* **Importação Híbrida:**
  * **Texto (Smart Paste):** cole a cifra, o sistema identifica os acordes automaticamente e libera **transposição de tom em tempo real** (`Tom -` / `Tom +`).
  * **PDF Contínuo:** importe seus arquivos `.pdf` já baixados e leia todas as páginas emendadas em uma única coluna vertical, com opção de **Modo Noturno**.
* **Organização por Setlists:** monte listas personalizadas para cada show sem duplicar arquivos e navegue entre a música anterior e a próxima com um toque.
* **Tela de Leitura Limpa (*Abrir Cifra*):**
  * **Rolagem automática suave** (`0.5x` a `10.0x`) com velocidade e tamanho da fonte salvos individualmente por música.
  * **Screen Wake Lock:** impede que a tela do aparelho apague no meio da música.
  * **Suporte a Pedais Bluetooth:** controle a rolagem e a pausa usando atalhos (`Espaço`, `PageUp`, `PageDown`, setas).
* **Visual Personalizável:** tema padrão minimalista em Preto & Branco, com opções de *OLED Puro*, *Noturno Suave*, *Dia / Claro* e escolha livre da **cor dos acordes**.
* **Backup Local Portátil:** exporte e restaure todo o seu repertório (incluindo os PDFs) em um único arquivo `.json`.

---

## 🧪 Acesso Beta à Sincronização (Google Drive)

O aplicativo funciona **100% grátis e sem login** usando o armazenamento offline do seu aparelho.

A integração com o **Google Drive** está atualmente em **fase de testes (Beta)**. Enquanto o app não passa pela verificação pública do Google, apenas e-mails autorizados manualmente conseguem fazer login na nuvem.

**Quer testar a sincronização com o Google Drive?**
1. Abra uma [Issue](https://github.com/lucasmenezescont/palcoaberto/issues) solicitando acesso ao Beta (ou envie seu e-mail Gmail diretamente para o mantenedor).
2. Assim que seu e-mail for adicionado à lista de testadores, basta clicar em **Nuvem > Entrar com Google** no app.
3. No primeiro login, caso o Google exiba o aviso de app em teste, clique em **Avançado > Acessar lucasmenezescont.github.io**.

---

## 🗺️ Roadmap

- [x] **PWA 100% Offline:** `manifest.json` e `Service Worker` para instalação na tela inicial e uso sem internet.
- [x] **Sincronização com Google Drive (Beta):** backup e restauração transparentes na pasta visível `Meu Drive / Palco Aberto` (*custo zero de servidor*).
- [ ] **Verificação pública no Google Cloud:** liberar o login com Google Drive para qualquer usuário sem aprovação manual de e-mail.
- [ ] **Extrator Inteligente de PDF:** converter PDFs de cifras em texto estruturado mantendo o alinhamento original dos acordes.
- [ ] **Reordenação por Arrastar e Soltar:** *drag and drop* para reorganizar músicas nos setlists rapidamente.
- [ ] **Identidade Visual PWA:** novo ícone oficial e capturas de tela para a janela de instalação.

---

## 🛠️ Tecnologias Utilizadas

Projeto pensado para ter barreira mínima de entrada — sem frameworks pesados ou etapas complexas de build:

* **HTML5 / CSS3** (Tailwind CSS)
* **JavaScript (Vanilla)**
* **IndexedDB** (armazenamento local offline)
* **PDF.js** (renderização contínua de PDFs no navegador)
* **Google Identity Services & Drive API v3** (sincronização opcional *Bring Your Own Cloud*)

---

## 🤝 Como Contribuir

Músicos e desenvolvedores são muito bem-vindos!

* **É músico?** Use o app nos ensaios ou shows e abra uma [Issue](https://github.com/lucasmenezescont/palcoaberto/issues) contando o que travou, o que incomodou ou o que facilitaria sua vida no palco.
* **É desenvolvedor?** Faça um *Fork* do repositório, crie uma branch com a sua melhoria (`git checkout -b feature/minha-melhoria`) e envie um *Pull Request*.

---

## 📄 Licença

Este projeto é distribuído sob a licença **MIT**. Sinta-se livre para usar, modificar e compartilhar.
