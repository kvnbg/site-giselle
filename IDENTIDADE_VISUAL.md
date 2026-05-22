# Identidade Visual — Giselle Torres · Neuropsicóloga

> Documento de identidade visual derivado do site oficial
> (`neuropsigiselletorres.com.br`). Usar como referência para posts no
> Instagram, materiais gráficos e qualquer comunicação visual da marca.

---

## 1. Essência da marca

| Item | Definição |
|---|---|
| **Marca** | Giselle Torres |
| **Especialidade** | Neuropsicologia Clínica · Avaliação Neuropsicológica |
| **CRP** | 11/18341 |
| **Localização** | Fortaleza – CE (unidades em Aldeota e Bairro de Fátima) |
| **Público-alvo** | Pais buscando avaliação para filhos (TDAH, TEA), adultos com queixas cognitivas, médicos encaminhadores |
| **Atributos** | Acolhimento · Ética · Sigilo · Técnica · Evidência científica · Clareza · Calma |
| **Promessa** | Avaliação neuropsicológica conduzida com rigor técnico, sigilo profissional e cuidado humano. |

**O que a marca NÃO é:** "milagre", "cura", "tratamento garantido", "diagnóstico em um clique".

---

## 2. Logo

Monograma **GT** com folha estilizada integrada à haste do "T", em azul ardósia.

- **Versão principal:** monograma `#3f5d7d` (royal-700) sobre fundo claro.
- **Versão reversa:** monograma branco sobre fundo escuro (`#0f172a` ou `#3f5d7d`).
- **Área de respiro mínima:** equivalente à altura da letra "G" em todos os lados.
- **Tamanho mínimo digital:** 32 px de altura.
- **Arquivos:** `/assets/logo.png` (site) · solicitar versões em SVG/branco para artes.

**Não fazer:**
- Distorcer, esticar ou aplicar perspectiva.
- Mudar a cor do logo para fora da paleta.
- Aplicar sombra dura, contorno ou efeitos 3D.
- Sobrepor a fotos com baixo contraste sem caixa/overlay.

---

## 3. Paleta de cores

### 3.1 Cor principal — Azul Ardósia (`royal`)

| Token | Hex | RGB | Uso |
|---|---|---|---|
| `royal-50` | `#f3f6f9` | 243, 246, 249 | Fundos suaves, badges, estado selecionado |
| `royal-100` | `#e6ebf1` | 230, 235, 241 | Blobs decorativos, fundos secundários |
| `royal-200` | `#cfdae4` | 207, 218, 228 | Bordas suaves |
| `royal-300` | `#b0c1d2` | 176, 193, 210 | Bordas em hover |
| `royal-600` | `#4d6e92` | 77, 110, 146 | Anéis de foco, detalhes |
| **`royal-700`** | **`#3f5d7d`** | **63, 93, 125** | **Cor principal** — CTAs, títulos de destaque, ícones |
| `royal-800` | `#354860` | 53, 72, 96 | Hover de CTAs |
| `royal-900` | `#2b3b4d` | 43, 59, 77 | Texto/destaques em fundo claro |

### 3.2 Neutros — Cinza-azulado (`slate`)

| Token | Hex | Uso |
|---|---|---|
| `slate-50` | `#f8fafc` | Fundo principal da página/post |
| `slate-100` | `#f1f5f9` | Bordas, separadores, cards secundários |
| `slate-200` | `#e2e8f0` | Bordas neutras |
| `slate-500` | `#64748b` | Texto de apoio, legendas |
| `slate-600` | `#475569` | **Corpo de texto** |
| `slate-700` | `#334155` | Texto secundário escuro |
| `slate-900` | `#0f172a` | Títulos em fundo claro, fundo do rodapé |
| `white` | `#ffffff` | Fundo de cards |

### 3.3 Regras de combinação

- **Texto escuro sobre fundo claro:** `slate-900` ou `royal-900` sobre `slate-50`/`white`/`royal-50`.
- **Texto branco sobre fundo escuro:** `white` sobre `royal-700` ou `slate-900`.
- **Contraste mínimo:** 4,5:1 para texto normal · 3:1 para títulos grandes/bold.
- **Cor principal nunca como fundo de blocos grandes de texto** — usar como destaque (botões, ícones, palavras-chave).
- **Verde NÃO faz parte da paleta** (mesmo sendo nicho de saúde mental — a escolha cromática evita o clichê).

---

## 4. Tipografia

**Fonte:** [Inter](https://fonts.google.com/specimen/Inter) (Google Fonts) — pesos 400, 500, 600, 700, 800.
**Fallback:** `system-ui, -apple-system, Segoe UI, sans-serif`.

| Função | Peso | Tamanho web | Tamanho em arte 1080×1080 |
|---|---|---|---|
| H1 / título de post | 800 (Extrabold) | 40–48 px | **80–110 px** |
| H2 / subtítulo | 700–800 | 28–36 px | 56–72 px |
| Eyebrow / categoria | 600 + UPPERCASE + tracking expandido | 12–14 px | 24–28 px |
| Corpo | 400 | 16–18 px | 32–36 px |
| Legenda / micro | 500 | 12 px | 22–24 px |

**Regras tipográficas:**
- **Line-height generoso** no corpo: ≥ 1,4.
- **Eyebrows e categorias em MAIÚSCULAS** com `tracking-wide` (+0,05em).
- **Títulos com `tracking-tight`** (−0,02em) — Inter Extrabold renderiza melhor levemente comprimido.
- **Nunca:** sombra de texto, contorno (outline), itálico para ênfase (use peso).

---

## 5. Elementos gráficos

### 5.1 Formas

- **Cantos arredondados:**
  - Cards e contêineres: `rounded-xl` (12 px) ou `rounded-2xl` (16 px).
  - Pills, dots, avatares: `rounded-full`.
  - Botões: `rounded-xl` (12 px).

### 5.2 Blobs decorativos

Círculos grandes em `slate-100` ou `royal-100` a 70% de opacidade, com **blur forte** (~32 px). Aparecem atrás de blocos de texto para dar respiração e profundidade. Nunca em primeiro plano.

### 5.3 Sombras

- Padrão suave: `shadow-sm` em cards.
- CTA primário: `shadow-lg shadow-royal-700/20` (sombra azulada, sutil).
- Evitar sombras pretas duras.

### 5.4 Ícones

- Estilo **linha fina** (stroke 2 px), cantos arredondados.
- Referência: [Lucide](https://lucide.dev/) / Heroicons (outline).
- Cor padrão: `royal-700` em fundo claro; branco em fundo escuro.
- **Não usar** ícones preenchidos coloridos ou em estilo desenhado.

### 5.5 Selo CRP

Pill com `bg-royal-50` + texto `royal-700`:

> **Neuropsicóloga · CRP 11/18341**

Deve aparecer em **todo post de teor técnico** (sobre TDAH, autismo, laudos, etc.).

### 5.6 A "folha"

A folha do monograma pode ser isolada como **motivo gráfico** em selos, divisores e detalhes. Sempre na cor `royal-700`.

---

## 6. Fotografia

### 6.1 Estilo

- **Retratos:** luz natural, ambiente neutro, expressão serena.
- **Cenários:** consultório, livros, materiais de avaliação, mãos escrevendo, mesa de testes.
- **Composição:** limpa, com áreas de respiro para sobreposição de texto.

### 6.2 Tratamento

- Tons **levemente frios** (temperatura puxando para o azul).
- Sem filtros saturados/vintage.
- Quando o post tiver overlay de texto, escurecer a foto com `royal-700` ou `slate-900` a **30–60% de opacidade**.

### 6.3 Evitar

- Clichês: mãos na cabeça, silhuetas tristes, cabeças explodindo, lâmpadas, cérebros desenhados.
- Stock photo genérico, sorrisos forçados, dramatização.
- Verde dominante na foto.

---

## 7. Voz e tom

**Tom geral:** acolhedor · técnico-claro · ético · sereno.

### Use:

- Frases curtas e diretas.
- **Termos técnicos corretos:** "avaliação" (não "exame"), "laudo", "investigação", "funções cognitivas", "psicodiagnóstico".
- Confirmar **sigilo** e **ética** em assuntos sensíveis.
- Falar em **segunda pessoa** ("você", "seu filho").
- **CRP visível** em afirmações técnicas.

### Evite:

- Promessas de cura, garantia de diagnóstico, "tratamento milagroso".
- Tom alarmista ("seu filho pode estar doente!").
- Excesso de emojis (**máximo 1–2 por post**, nunca em conteúdo técnico).
- Jargão sem explicação.

### Manchetes-exemplo

- *"TDAH ou só comportamento agitado? 7 sinais para observar."*
- *"Como funciona a avaliação neuropsicológica, do começo ao fim."*
- *"Laudo neuropsicológico: o que ele esclarece — e o que não esclarece."*

### Estrutura de legenda (caption)

```
[Hook em 1 linha — pergunta ou afirmação que prende]

[Explicação curta — 2 a 4 linhas, ideias simples]

[CTA — agendar, salvar, comentar, link na bio]

[5–10 hashtags da seção 10]
```

---

## 8. Aplicação no Instagram

### 8.1 Formatos

| Formato | Dimensões | Uso |
|---|---|---|
| Feed quadrado | 1080 × 1080 px | Citações, posts simples |
| **Feed retrato** | **1080 × 1350 px** | **Recomendado — ocupa mais tela** |
| Carrossel | 1080 × 1080 ou 1080 × 1350 | Conteúdo educativo, passo a passo, FAQ |
| Story / Reels capa | 1080 × 1920 px | Dicas rápidas, bastidores, CTAs |

Margem de segurança: **80 px** de cada borda no feed; **220 px no topo e 250 px na base** no story (UI do app).

### 8.2 Tipos de post (rotação sugerida)

| Tipo | Frequência | Exemplo |
|---|---|---|
| **Educativo** | ~60% | "3 sinais de TDAH na criança em idade escolar" |
| **Autoridade / institucional** | ~20% | "Conheça o consultório · CRP 11/18341" |
| **Conexão / acolhimento** | ~15% | "Pedir ajuda é um ato de coragem" |
| **CTA direto** | ~5% | "Agende sua avaliação · link na bio" |

### 8.3 Templates base

**Template A — Citação / pergunta de impacto**
- Fundo `slate-50` ou `royal-50`.
- Texto centralizado, Inter Extrabold, 80–110 px, cor `slate-900`.
- Eyebrow opcional no topo (`royal-700`, uppercase, 24 px).
- Logo discreto no topo central ou rodapé.
- Selo CRP no canto inferior.

**Template B — Carrossel educativo**
- **Capa:** pergunta em destaque + categoria.
- **Slides 2–N:** 1 ideia por slide. Layout: ícone à esquerda (`royal-700`) + título + 2–3 linhas de texto.
- **Slide final:** CTA + handle do Instagram + foto/logo + CRP.
- Numerar os slides discretamente (`1/6`, `2/6`...) em `slate-500`.

**Template C — Foto + sobreposição**
- Imagem em 100% do quadro.
- Overlay `royal-700` a ~40% (ou degradê de baixo para cima).
- Eyebrow `royal-100` UPPERCASE + título branco Extrabold.

### 8.4 Grade visual (feed)

- **Família visual a cada 3 posts:** evite que dois posts vizinhos sejam visualmente idênticos, mas mantenha a paleta.
- **Respiração:** alternar fundos `slate-50` ↔ `royal-50` ↔ foto.
- **Sem cores fora da paleta.** Sem fundos pretos puros (use `slate-900`).

---

## 9. CTAs padronizados

- *Agende sua avaliação*
- *Fale pelo WhatsApp*
- *Saiba mais no site*
- *Link na bio*
- *Salve para depois*
- *Marque alguém que precisa ver isso*

**Botão visual em arte:** retângulo `rounded-xl`, fundo `royal-700`, texto branco Extrabold. Em fundo escuro, inverter (fundo branco, texto `royal-900`).

---

## 10. Hashtags sugeridas

Sempre incluir **5 a 10** por post. Misturar **nicho + público + local**.

**Nicho:**
`#neuropsicologia` `#avaliacaoneuropsicologica` `#neuropsicologiaclinica` `#psicodiagnostico` `#neuropsicologainfantil`

**Público / temas:**
`#tdah` `#tdahinfantil` `#tea` `#autismo` `#dificuldadesdeaprendizagem` `#funcoesexecutivas` `#memoria` `#atencao`

**Local:**
`#fortaleza` `#fortalezaceara` `#psicologafortaleza` `#aldeota` `#bairrodefatima` `#nordeste`

**Apoio:**
`#saudemental` `#cuidadocomamente` `#desenvolvimentoinfantil`

> **Evitar** hashtags genéricas demais como `#amor`, `#instagood`, `#vida` — não convertem e diluem o nicho.

---

## 11. Checklist antes de publicar

- [ ] **Logo** presente (canto superior ou rodapé do post).
- [ ] **CRP** visível em qualquer afirmação técnica.
- [ ] **Contraste** de texto ≥ 4,5:1.
- [ ] Cores **dentro da paleta** (sem verde, sem cores fora do `royal`/`slate`).
- [ ] Tipografia **Inter** com hierarquia clara.
- [ ] Cantos arredondados consistentes.
- [ ] Sem clichês visuais de "doença mental".
- [ ] Copy revisada: **nada promete cura ou diagnóstico instantâneo**.
- [ ] **Hashtags** da seção 10 (5–10).
- [ ] **CTA** claro (mesmo que sutil).
- [ ] Próximo do feed: combina com os 2 posts vizinhos?

---

## 12. NAP institucional (Nome · Endereço · Telefone)

Usar em formato **idêntico** em qualquer arte, legenda, bio ou citação externa.

- **Nome:** Giselle Torres — Neuropsicóloga
- **CRP:** 11/18341
- **Endereços:**
  - **Unidade Aldeota** — R. Monsenhor Bruno, 1153 · Fortaleza – CE · 60115-191
  - **Unidade Bairro de Fátima** — Rua Martinho Rodrigues, 129 · Fortaleza – CE · 60411-280
- **WhatsApp:** +55 (85) 98713-5017
- **Site:** [neuropsigiselletorres.com.br](https://neuropsigiselletorres.com.br/)

---

## 13. Referências rápidas (cola visual)

```
COR PRINCIPAL   #3f5d7d   (royal-700)
COR DE TEXTO    #0f172a   (slate-900)
FUNDO PADRÃO    #f8fafc   (slate-50)
BRANCO          #ffffff
FONTE           Inter (400, 600, 700, 800)
RAIO            12 px (rounded-xl) / 16 px (rounded-2xl)
SOMBRA CTA      0 10px 15px -3px rgba(63,93,125,0.20)
```
