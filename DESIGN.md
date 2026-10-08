---
version: alpha
name: Molécula Café
description: "O ponto da sua xícara. Portal de notícias premium sobre café — do grão à cultura — que evoluiu para uma comunidade social de entusiastas."
colors:
  primary: "#4A3222"
  secondary: "#A9714B"
  tertiary: "#C98A4B"
  neutral: "#F6F0E4"
  ink: "#2E2118"
  surface: "#FBF7EE"
  muted: "#7A6A5C"
  line: "#E5DAC8"
  onDark: "#F3EAD9"
  onDarkMuted: "#D9CBB8"
  onDarkAccent: "#D8B48C"
typography:
  display:
    fontFamily: Fraunces
    fontSize: 2.875rem
    fontWeight: 500
    lineHeight: 1.14
    letterSpacing: "-0.5px"
  h1:
    fontFamily: Fraunces
    fontSize: 2.625rem
    fontWeight: 500
    lineHeight: 1.15
    letterSpacing: "-0.4px"
  h2:
    fontFamily: Fraunces
    fontSize: 1.625rem
    fontWeight: 500
    lineHeight: 1.3
  h3:
    fontFamily: Fraunces
    fontSize: 1.1875rem
    fontWeight: 500
    lineHeight: 1.3
  body-lg:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.6
  body-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: Inter
    fontSize: 0.8125rem
    fontWeight: 400
    lineHeight: 1.6
  overline:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: "2.5px"
  button:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: 500
rounded:
  sm: 3px
  md: 4px
  lg: 16px
  pill: 999px
spacing:
  xs: 8px
  sm: 14px
  md: 18px
  lg: 24px
  xl: 32px
  hero: 48px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    rounded: "{rounded.pill}"
    padding: 10px 22px
    typography: "{typography.button}"
  button-primary-hover:
    backgroundColor: "{colors.secondary}"
  button-accent:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: 12px 24px
    typography: "{typography.button}"
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
  hero:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.onDark}"
  overline-label:
    textColor: "{colors.onDarkAccent}"
    typography: "{typography.overline}"
  section-label:
    textColor: "{colors.secondary}"
    typography: "{typography.overline}"
  body-text:
    textColor: "{colors.ink}"
    typography: "{typography.body-lg}"
  body-text-on-dark:
    textColor: "{colors.onDarkMuted}"
    typography: "{typography.body-md}"
  muted-text:
    textColor: "{colors.muted}"
    typography: "{typography.body-sm}"
  link:
    textColor: "{colors.secondary}"
---

# Molécula Café — Design System

## Overview

Portal de notícias sobre café com identidade **acolhedora, artesanal e humana**,
com um toque de ciência. A metáfora central é *"a química do aconchego":* o café
como um momento que acolhe, coloca a pessoa no centro e resolve o dia. O design
conversa como um barista que conhece você — "senta, fica à vontade". Estética
editorial artesanal (inspirada em revistas de café de especialidade) com
navegação por seções como caminho principal para a descoberta de conteúdo.

## Colors

- **Primary (#4A3222, "espresso"):** a identidade — usada no hero, no brand
  primary button e como fundo escuro. Transmite a profundidade do café.
- **Secondary (#A9714B, "caramel"):** acento principal para links e detalhes;
  derivada do tom da bebida.
- **Tertiary (#C98A4B, "amber"):** ação e calor — CTA de destaque (ex:
  botão da newsletter). Traz o tom de "quente" e convidativo.
- **Neutral (#F6F0E4, "cream"):** fundo da página — suave, tátil, papel.
- **Surface (#FBF7EE, "paper"):** superfícies elevadas (cards).
- **Ink (#2E2118):** texto principal — marrom escuro quase preto, mais quente
  que o preto puro.
- **Muted (#7A6A5C):** texto secundário / data e metadados.
- **Line (#E5DAC8):** bordas e separadores sutis.
- **OnDark (#F3EAD9):** texto sobre fundos espresso; **OnDarkMuted**
  (#D9CBB8) para parágrafos; **OnDarkAccent** (#D8B48C) para overlines.

## Typography

- **Fraunces** (serifada): títulos — sensação editorial feita à mão.
- **Inter** (sans humana): corpo e UI — leitura confortável e moderna.
- **Overline:** pequenas etiquetas em caixa alta, espaçadas (2.5px) e
  ampliadas, para seções e categorias.

## Layout & Spacing

- Conteúdo em coluna central com max-width de 1200px e padding lateral de 24px.
- Grid de notícias em 3 colunas (desktop) → 2 (tablet) → 1 (mobile).
- Hero em banner grande com 2 cards laterais (destaque editorial + leitura rápida).
- Espaçamento generoso; ritmo calmo, sem poluição visual.

## Elevation

- Elevação mínima: superfícies separadas por cor (surface sobre neutral) e
  bordas sutis (line), seguindo o estilo plano editorial.
- Cards levemente elevados sobre hover (translateY + borda caramel); nada de
  sombras profundas — mantém o clima artesanal.

## Shapes

- Cantos **discretos** (3–4px) para cards e superfícies — editorial, não infantil.
- Botões em **pill** (999px) — o único elemento com cantos totalmente redondos,
  criando contraste aconchegante.

## Components

- **button-primary:** a ação principal de cada tela (ex: "Assinar") — espresso
  com texto creme.
- **button-accent:** CTA de destaque (newsletter) — âmbar com texto espresso.
- **card:** superfície elevada para artigos e seções.
- **hero:** banner escuro espresso com texto onDark + overline accent.
- **overline-label / section-label:** etiquetas de seção em caixa alta espaçada.
- **body-text / muted-text / link:** hierarquia de texto; links em caramel.

## Do's and Don'ts

- **Faça:** tom acolhedor e frases amigáveis ("senta, fica à vontade").
- **Faça:** serifada nos títulos, sans no corpo; cantos discretos com pills só
  nos botões; fundo creme com céu espresso.
- **Não faça:** preto puro, neon, sombras pesadas ou cantos muito arredondados
  em cards — quebram o clima artesanal.
- **Não faça:** tons frios/cinza como base — o design é quente.