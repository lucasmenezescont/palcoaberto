# 🎸 Palco Aberto

**Gerenciador de cifras e setlists open source, feito para a realidade do palco.**

O **Palco Aberto** nasceu para resolver uma dor comum de músicos de bar e eventos ao vivo: sites e aplicativos de cifras cheios de anúncios, pop-ups, cliques excessivos e dependência de internet. Aqui o foco é leitura limpa, velocidade e zero distrações na hora de tocar.

👉 **[Acessar o Palco Aberto agora](https://lucasmenezescont.github.io/palcoaberto/)**

---

## ✨ O que já funciona

* **Banco de Dados Local (`IndexedDB`):** todas as suas cifras, PDFs e setlists ficam salvos diretamente no seu dispositivo, sem necessidade de cadastro ou servidor.
* **Importação Híbrida:**
  * **Texto (Copia e Cola):** cola a cifra, o sistema identifica os acordes automaticamente e libera **transposição de tom em tempo real** (`-` / `+`).
  * **PDF Contínuo:** importa seus arquivos `.pdf` já baixados e renderiza todas as páginas emendadas em uma única coluna vertical, com opção de **Modo Noturno**.
* **Organização por Setlists:** monte listas personalizadas para cada show sem duplicar arquivos.
* **Tela de Leitura Limpa (*Abrir Cifra*):**
  * **Rolagem automática suave** com controle de velocidade salvo individualmente para cada música.
  * **Screen Wake Lock:** impede que a tela do celular ou tablet apague no meio da música.
  * **Suporte a Pedais Bluetooth:** controle a rolagem e a pausa usando teclas de atalho (`Espaço`, `PageUp`, `PageDown`, setas).
* **Visual Personalizável:** tema padrão minimalista em Preto & Branco, com opções de *OLED Puro*, *Noturno Suave*, *Dia/Claro* e escolha livre da **cor dos acordes**.
* **Backup Portátil:** exporte e restaure todo o seu repertório (incluindo os PDFs) em um único arquivo `.json`.

---

## 🗺️ Roadmap (Próximos Passos)

O projeto está em desenvolvimento ativo. Estas são as próximas prioridades:

- [ ] **PWA 100% Offline:** adicionar `manifest.json` e `Service Worker` para instalação na tela inicial (Android/iOS) e abertura sem internet.
- [ ] **Sincronização com Google Drive:** permitir que cada músico conecte sua própria conta do Google para sincronizar o repertório entre computador e tablet (*custo zero de servidor*).
- [ ] **Extrator Inteligente de PDF:** converter PDFs de cifras em texto estruturado mantendo o alinhamento original dos acordes.
- [ ] **Reordenação de Setlists:** arrastar e soltar (*drag and drop*) para mudar a ordem das músicas rapidamente.

---

## 🛠️ Tecnologias Utilizadas

Projeto pensado para ter barreira mínima de entrada — sem frameworks pesados ou etapas complexas de build:

* **HTML5 / CSS3** (Tailwind CSS)
* **JavaScript (Vanilla)**
* **IndexedDB** (armazenamento local de alta capacidade)
* **PDF.js** (renderização de documentos PDF no navegador)

---

## 🤝 Como Contribuir

Músicos e desenvolvedores são muito bem-vindos!

* **É músico?** Use o app nos ensaios ou shows e abra uma [Issue](https://github.com/lucasmenezescont/palcoaberto/issues) contando o que travou, o que incomodou ou o que facilitaria sua vida no palco.
* **É desenvolvedor?** Faça um *Fork* do repositório, crie uma branch com a sua melhoria (`git checkout -b feature/minha-melhoria`) e envie um *Pull Request*.

---

## 📄 Licença

Este projeto é distribuído sob a licença **MIT**. Sinta-se livre para usar, modificar e compartilhar.
