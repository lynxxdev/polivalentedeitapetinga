<div align="center">

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Cinzel&weight=700&size=13&letterSpacing=8px&duration=4000&pause=2000&color=C8993A&center=true&vCenter=true&width=600&lines=COLÉGIO+POLIVALENTE+DE+ITAPETINGA;FUNDADO+EM+1974;MAIS+DE+50+ANOS+DE+HISTÓRIA" alt="Typing SVG"/>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,5&height=140&section=header&text=C.P.I&fontSize=72&fontColor=c8993a&fontAlignY=65&animation=fadeIn&fontFamily=Cinzel"/>
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,5&height=140&section=header&text=C.P.I&fontSize=72&fontColor=c8993a&fontAlignY=65&animation=fadeIn&fontFamily=Cinzel"/>
</picture>

<br/>

<h3>
  <samp>✦ &nbsp; Colégio Polivalente de Itapetinga &nbsp; ✦</samp>
</h3>

<p>
  <em>Educando gerações com dedicação, tradição e carinho.</em>
</p>

<br/>

<br/><br/>

</div>


<br/>

## ❖ &nbsp;Sobre o Projeto

O **Colégio Polivalente de Itapetinga** é uma das instituições de ensino mais tradicionais da cidade — com mais de **50 anos de história** formando cidadãos, cultivando sonhos e transformando vidas no interior da Bahia.

Este repositório contém o **site oficial da escola**, construído do zero para refletir com fidelidade a identidade, os valores e o legado de uma instituição que marcou gerações. O projeto foi desenvolvido com atenção obsessiva aos detalhes: tipografia de serifas clássicas, paleta dourada sobre azul-marinho profundo, animações refinadas e uma experiência de navegação que honra a tradição sem abrir mão da modernidade.

<br/>

> *"Formando gerações com dedicação, tradição e compromisso com a educação."*

<br/>

---

<br/>

## ❖ &nbsp;Preview

<div align="center">

| Loader | Site Principal |
|:---:|:---:|
| Anel de progresso dourado com partículas | Navegação por abas com animações suaves |
| Partículas flutuantes e estrelas cadentes | Design dark navy + gold com glassmorphism |
| Emblema C.P.I com shimmer animado | Seções: Sobre · Cursos · Projetos · Grêmio · Biblioteca · Contato |

</div>

<br/>

---

<br/>

## ❖ &nbsp;Tecnologias

<div align="center">

<br/>

| &nbsp; | Tecnologia | Função |
|:---:|:---|:---|
| <img src="https://skillicons.dev/icons?i=html" width="20"/> | **HTML5** | Estrutura semântica e acessível |
| <img src="https://skillicons.dev/icons?i=css" width="20"/> | **CSS3** | Animações, glassmorphism e layout responsivo |
| <img src="https://skillicons.dev/icons?i=js" width="20"/> | **JavaScript Vanilla** | Interatividade, sliders, partículas e lógica do loader |
| <img src="https://skillicons.dev/icons?i=github" width="20"/> | **GitHub** | Versionamento e repositório central |
| 🔤 | **Cinzel + Cormorant Garamond** | Tipografia serif clássica via Google Fonts |
| 🎨 | **Font Awesome 6** | Iconografia consistente em todo o site |

<br/>

</div>

---

<br/>

## ❖ &nbsp;Funcionalidades

<br/>

**🎬 &nbsp;Loader**
- Anel de progresso SVG multicamada com gradiente dourado animado
- Faísca luminosa que percorre a ponta do arco em tempo real
- 72 ticks decorativos no anel externo (estilo mostrador de relógio)
- Campo de partículas flutuantes com linhas de conexão e estrelas cadentes no canvas
- Emblema C.P.I centralizado com shimmer animado e ornamentos tipográficos
- Transição de saída suave: encolhe + blur + fade ao atingir 100%
- `polivalente.html` carrega em background — zero delay após o loader

**🖥️ &nbsp;Site Principal**
- Navegação por abas com animação `fadeUp` e scroll automático ao topo
- Hero com grid de linhas sutis em máscara radial, estrelas cadentes no canvas e contadores animados
- Seções completas: **Sobre / Cursos / Projetos & Programas / Grêmio Estudantil / Biblioteca / Contato**
- Sliders de imagens com autoplay, dots e botões de navegação
- Lightbox de galeria com navegação por teclado (← →  Esc)
- Overlay de redirecionamento com contagem regressiva (WhatsApp, Instagram, E-mail)
- Mapa do Google Maps embutido na seção de Contato
- Scrollbar customizado e botão scroll-to-top animado

**🎨 &nbsp;Design**
- Paleta `navy #060b18` + `gold #c8993a` com variáveis CSS
- Glassmorphism nos cards com `backdrop-filter` e bordas translúcidas
- Gradientes em camadas nos backgrounds de seção
- Animações `reveal` ativadas por scroll
- Fontes: Cinzel (títulos) · Cormorant Garamond (subtítulos) · Lato (corpo)
- Totalmente responsivo — mobile, tablet e desktop

**🔒 &nbsp;Segurança**
- Bloqueio de `Ctrl+U`, `Ctrl+S`, `F12` e atalhos de DevTools
- Desativação do menu de contexto (`contextmenu`)
- Proteção contra drag de imagens e seleção de texto em elementos sensíveis

<br/>

---

<br/>

## ❖ &nbsp;Estrutura do Repositório

```
📁 polivalentedeitapetinga/
│
├── 📄 index.html                          ← Loader animado (entrada do site)
├── 📄 polivalente.html                    ← Site completo (carregado pelo loader)
├── 📄 google14688906d0de8c5c.html         ← Verificação Google Search Console
└── 📄 README.md                           ← Este arquivo
```

<br/>

---

<br/>

## ❖ &nbsp;Fluxo de Navegação

```
Usuário acessa o site
        │
        ▼
  ┌─────────────────────────────────────┐
  │           index.html                │
  │  ┌───────────────────────────────┐  │
  │  │  Loader anima (0% → 100%)     │  │  ← polivalente.html carrega em bg
  │  │  Anel · Partículas · Emblema  │  │
  │  └───────────────────────────────┘  │
  │  Ao atingir 100%:                   │
  │  loader encolhe + fade → iframe     │
  └─────────────────────────────────────┘
        │
        ▼
  ┌─────────────────────────────────────┐
  │         polivalente.html            │
  │  Sobre · Cursos · Projetos          │
  │  Grêmio · Biblioteca · Contato      │
  └─────────────────────────────────────┘
```

<br/>

---

<br/>

## ❖ &nbsp;Contribuições

Este é um **projeto institucional privado**. Não estão sendo aceitas contribuições externas.

Para reportar problemas, sugerir melhorias ou solicitar alterações, entre em contato diretamente com o desenvolvedor responsável:

<div align="center">

<br/>

[![Instagram](https://img.shields.io/badge/@thanzin.vx-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=070c1a)](https://www.instagram.com/thanzin.vx)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=070c1a)](https://wa.me/557791918491)

<br/>

</div>

---

<br/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,5&height=100&section=footer&animation=fadeIn"/>
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,5&height=100&section=footer&animation=fadeIn"/>
</picture>

<br/>

```
E s t .   1 9 7 4   ·   C . P . I   ·   I t a p e t i n g a ,   B a h i a
```

<br/>

*© 2026 Colégio Polivalente de Itapetinga — Todos os direitos reservados.*<br/>
*A reprodução, modificação ou distribuição sem autorização é **PROIBIDA**.*

<br/>

**Desenvolvido com ♥ por [@thanzin.vx](https://www.instagram.com/thanzin.vx)**<br/>
*para o Colégio Polivalente de Itapetinga*

<br/>

</div>
