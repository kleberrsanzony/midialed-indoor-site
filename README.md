# MídiaLed Indoor — Site comercial

Site estático, responsivo e independente do MMI TV.

## Executar

Abra `index.html` ou execute `python3 -m http.server 8000` na pasta do projeto.

## Publicar

Na Vercel: importe este repositório GitHub, Framework Preset: Other, Root Directory: `/`, Build Command vazio e Output Directory vazio.

## Identidade

Usa **apenas** a marca extraída do storyboard aprovado `assets/marca-aprovada.webp`. Paleta: #00E5FF, #4B0082, #000000 e #FFFFFF.

## Fotos

Imagens de produto fornecidas pelo cliente e otimizadas para WebP. Características técnicas reproduzidas dos dados fornecidos, com ressalvas de validação junto ao fabricante.

## Contato

Botões de contato abrem o WhatsApp (81) 98183-0554 com mensagem pronta; e-mail midiamares@gmail.com. Link para o Grupo MídiaMares mantido.

## Visual e animações

- Hero: painel de LED interativo em tela cheia (canvas em baixa resolução + máscara de pontos em CSS), com 4 cenas (ondas, mensagem rolando, campanha, equalizador), luz que segue o mouse e ondas ao tocar. Pausa fora da tela.
- Estrutura: faixa de letreiro, bento de recursos, totem que troca a tela conforme a rolagem (4 capítulos), painéis de aplicações que expandem, fotos reais + ficha em blocos, linha do tempo que acende, FAQ com lateral fixa e letreiro de contato.
- Títulos acendem como LED (efeito diferente por seção). Tema claro/escuro (`mli-theme`). Suporte a `prefers-reduced-motion`.
