# 👑 Meu Querido Diamante — Site do Dia dos Namorados

> "De todas as verdades conhecidas pela alta sociedade, nenhuma é tão escandalosamente bela quanto o fato de que, mesmo separadas por milhas de distância, dois corações obstinados se recusam a bater fora de sincronia." 
> — *Lady Whistledown*

Este projeto é uma aplicação web interativa, responsiva e altamente personalizada, desenvolvida como um presente exclusivo de Dia dos Namorados. Inspirado na estética e na narrativa da série **Bridgerton**, o site combina crônicas românticas com funcionalidades dinâmicas para celebrar uma história de amor.

---

## ⚜️ Experiências Disponíveis na Corte

O site foi estruturado através de seções interativas, integradas por um menu de navegação flutuante ultra moderno e compacto:

*   **⏳ O Relógio da Corte:** Um cronômetro regressivo em tempo real programado para o grande momento (12 de Junho às 19:30).
*   **📰 O Termômetro de Escândalos:** Uma barra de progresso animada ilustrando que os níveis de afeição do casal atingiram a marca lendária de 100%.
*   **✉️ Cartas da Alta Sociedade:** Um mural interativo no estilo *"Abra Quando..."* onde cliques acionam modais com missivas secretas para momentos específicos (saudades, dias difíceis ou para sorrir).
*   **📸 Galeria de Memórias:** Um mural de fotos interativo utilizando o efeito *Flip Card* em 3D, revelando histórias e legendas ao passar o mouse.
*   **🎬 Convite ao Cinema:** Um sistema de votação assíncrona onde a escolha do filme para a noite é enviada diretamente para a pretendente.
*   **🧩 Divertimentos da Corte:** Uma seção de jogos (Caça-Palavras e Palavras Cruzadas) protegida por um validador de horário em JavaScript, liberando o acesso apenas no horário estipulado.
*   **✍️ O Livro de Confissões:** Um pergaminho digital (formulário) para o envio de promessas e desejos profundos de forma segura e direta.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias web fundamentais nativas, priorizando a performance e a estética:

*   **HTML5:** Estruturação semântica de todas as crônicas e seções.
*   **CSS3 Avançado:**
    *   Design baseado em **Glassmorphism** (efeito de vidro fosco com `backdrop-filter`).
    *   Animações fluidas (`@keyframes`) para o carregamento do termômetro e para a chuva constante de pétalas de flores/corações ao fundo.
    *   Estilização em formato de pílula para o menu compacto e carrossel de deslize horizontal responsivo para dispositivos móveis.
*   **JavaScript (Vanilla):**
    *   Lógica de contagem regressiva baseada no objeto `Date`.
    *   Validação em tempo real do fuso horário e bloqueio dos links de jogos.
    *   Manipulação de DOM para o controle do player de áudio integrado e gerenciamento de estados do Modal.
*   **Formspree API:** Integração assíncrona via `fetch()` para o recebimento das confissões e votos de cinema diretamente no e-mail sem recarregar a página.

---

## 📂 Estrutura de Arquivos

Para o perfeito funcionamento do ecossistema da corte, certifique-se de que a raiz do projeto contenha a seguinte disposição de mídias locais:

```text
├── index.html                   # Arquivo principal do site (antigo site_dia_dos_namorados_2.html)
├── love-letter.png              # Ícone da aba do navegador (Favicon)
├── mirrors.mp3                  # Trilha sonora tema do casal
├── foto1.jpg                    # Foto da memória "O Teu Reflexo"
├── foto3.jpeg                   # Foto da memória "Cumplicidade"
├── foto4.jpg                    # Foto da memória "O Começo de Tudo"
├── escola.mp4                   # Trailer do filme "A Escola do Bem e do Mal"
├── moana.mp4                    # Trailer do filme "Moana 2"
└── culpa.mp4                    # Trailer do filme "Minha Culpa"
