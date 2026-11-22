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

Hero com parede 3D de painéis LED (`assets/telas/`, recortes das fotos e do storyboard) e totem recortado (`assets/totem-recorte.webp`), palavra giratória, cards com borda em degradê e números vazados, vitrine com filtros e troca de foto pré-carregada, uma animação de entrada por seção, abertura "painel ligando" (uma vez por sessão), modo claro/escuro (segue o aparelho e lembra a escolha em `mli-theme`) e suporte a `prefers-reduced-motion`.
