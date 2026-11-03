---
name: usami-brand-identity
description: Fonte única da identidade da Usami (empresa independente de IA e sua companion Usami). Use SEMPRE que for decidir cor, tipografia, personagem, layout, voz, motivos visuais ou qualquer elemento de interface.
---

# Usami — Identidade de marca (USAMI® Design System v1.0)

Esta skill é a **fonte única de verdade** da marca Usami. Outras skills e implementações referenciam os tokens e regras definidos aqui.

---

## 1. Visão Geral da Marca

- **Nome da marca:** Usami
- **Indústria:** Tecnologia, Inteligência Artificial, Inovação Digital
- **Produto principal:** Usami AI Companion
- **Conceito central:** *Intelligence with a presence.* (Inteligência com presença).
- **Personalidade da marca:** Inteligente, Expressiva, Curiosa, Elegante, Futurista, Acolhedora (Warm), Independente, Experimental.
- **Posicionamento:** Não é uma startup genérica de IA. É uma empresa independente construindo sistemas inteligentes e experiências digitais com forte identidade criativa. Ambição técnica com presença e estética autoral.

### Estética desejada
Combinação sofisticada de:
- Cyber-orgânico
- Fantasia digital
- Tecnologia contemporânea
- Detalhes visuais de inspiração japonesa (geometria, ornamentos dourados)
- Design editorial experimental

---

## 2. Paleta de Cores (Tokens Oficiais)

Inspirada no esquema de cores da personagem Usami: café, caramelo, preto, rosa e ouro.

| Token CSS | Nome | Hex | Papel / Uso |
|---|---|---|---|
| `--color-coffee` | Coffee | `#39271F` | Cor primária da marca |
| `--color-dark-coffee` | Dark Coffee | `#211713` | Fundos profundos |
| `--color-caramel` | Caramel | `#B98252` | Acento primário, estados interativos, ênfases |
| `--color-warm-caramel` | Warm Caramel | `#D4A477` | Acento secundário |
| `--color-soft-pink` | Soft Pink | `#F0D6D0` | Destaque inspirado na personagem (cabelo/pele) |
| `--color-pale-rose` | Pale Rose | `#E7B8BC` | Acento decorativo |
| `--color-gold` | Ornamental Gold | `#D9B778` | Detalhes nobres e ornamentais (uso contido) |
| `--color-ink-black` | Ink Black | `#100D0C` | Fundo principal de interface escura |
| `--color-warm-white` | Warm White | `#F8F2EB` | Fundo claro primário, contraste e leitura |
| `--color-muted-cream` | Muted Cream | `#E6D9CA` | Superfície secundária clara |

### Diretrizes de uso de cor
- **Base:** Coffee e Ink Black estabelecem a identidade base dominante.
- **Interatividade:** Caramel é a cor de foco, ação e destaque interativo.
- **Calor:** Soft Pink e Pale Rose trazem organicidade e referência sutil à personagem.
- **Nobreza:** Ornamental Gold deve ser usado com moderação em filetes, marcadores e detalhes geométricos.
- **Proibido:** Gradientes roxo/azul clichês de IA generativa, neon excessivo, gradientes arco-íris e glassmorphism exagerado.

---

## 3. Tipografia

Combinação de tecnologia contemporânea com design editorial elegante.

| Papel | Família | Uso |
|---|---|---|
| **Display** | **Cormorant Garamond** (serif) | Manchetes expressivas, declarações conceituais, momentos editoriais artísticos |
| **Primária** | **Space Grotesk** (sans-serif) | Títulos de seção, corpo de texto, botões, navegação e elementos de interface. *(Alternativas aceitas: Manrope, Inter)* |
| **Técnica** | **IBM Plex Mono** (monospace) | Rótulos técnicos, metadados de produto, identificadores de seção, telemetria e anotações |

### Regras de tipografia:
- Hierarquia forte e deliberada.
- Manchetes podem ser superdimensionadas e expressivas.
- Usar serifa de forma seletiva para impacto emocional e editorial.
- Manter alta legibilidade e evitar caixa alta excessiva.

---

## 4. Identidade da Personagem (Usami)

A Usami é a personagem central da marca e o produto AI companion.
- **Aparência:** Cabelo branco e rosa pálido, olhos cor-de-rosa, orelhas de gato, traje preto, detalhes ornamentais dourados, silhueta elegante e delicada com styling de fantasia japonesa.
- **Papel:** É tratada como **ativo central da marca**, não como mero mascote decorativo.
- **Presença:** Hero da homepage, apresentação de produto, experiências interativas 3D/2D, ilustrações autorais e narrativa da marca.
- **Regras:** Preservar rigorosamente a aparência e silhueta originais. Não transformar em personagem de anime genérica nem substituir por imagens geradas aleatórias de IA.
- **Distinção Marca x Companion:** A empresa Usami mantém postura tecnológica de alto calibre; a companion Usami traz a dimensão expressiva e acolhedora. A personagem não deve sobrecarregar seções puramente corporativas ou de documentação técnica.

---

## 5. Grid e Espaçamento

### Grid
- **Desktop:** 12 colunas
- **Tablet:** 8 colunas
- **Mobile:** 4 colunas

### Escala de Espaçamento
`4px`, `8px`, `12px`, `16px`, `24px`, `32px`, `48px`, `64px`, `96px`, `128px`, `160px`.

---

## 6. Movimento e Interatividade

- **Princípios:** Movimento com propósito, naturalidade, respeito estrito a `prefers-reduced-motion`.
- **Interação da Personagem:** Animação de idle sutil; cabeça e olhos podem reagir de forma refinada ao cursor do mouse sem obstruir a leitura ou navegação.
- **Tecnologias de animação:** CSS Transitions/Animations, GSAP para transições fluidas e coordenadas, Three.js quando houver valor visual imersivo justificado.

---

## 7. Diretrizes Técnicas

- **Stack Preferencial:** Ruby on Rails, HTML, CSS, JavaScript, Hotwire, Stimulus, Tailwind CSS, GSAP, Three.js (quando apropriado), ícones Lucide.
- **Regra Rígida:** **Sem TypeScript, Sem React, Sem Next.js.**
