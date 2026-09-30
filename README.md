# NBX Projects — Identidade Visual

[![GitHub Pages](https://img.shields.io/badge/Brand%20Hub-GitHub%20Pages-302B28?style=flat-square&logo=github)](https://nbx-projects.github.io/brand-identity/)
[![Assets](https://img.shields.io/badge/Assets-SVG%20%26%20PNG-57483F?style=flat-square)](https://nbx-projects.github.io/brand-identity/#assets)

Este repositório reúne os arquivos-mestre, orientações, tokens de design e materiais oficiais da identidade visual da **NBX Projects**.

> **Ideia da marca:** software feito com clareza e cuidado, representado por um macaco simpático de formas arredondadas e simples.

🌐 **Central Interativa de Marca & Download:** [nbx-projects.github.io/brand-identity](https://nbx-projects.github.io/brand-identity/)

---

## 🚀 Central de Marca (GitHub Pages)

Acesse a [página oficial do GitHub Pages](https://nbx-projects.github.io/brand-identity/) para:
- 📥 **Baixar o Brand Kit completo (.ZIP)** com um único clique.
- 🎨 **Visualizar e baixar ativos individuais** em SVG vetorial e PNG em alta definição (com fundo transparente).
- 📋 **Copiar código XML SVG** ou código de cores diretamente para o clipboard.
- 🌓 **Testar contraste** dos logos trocando os fundos em tempo real.
- ✍️ **Playground tipográfico** interativo com a família *Nunito Sans*.

---

## 📁 Estrutura do Repositório

```text
brand-identity/
├── .github/workflows/
│   └── deploy-pages.yml             # Workflow de deploy contínuo no GitHub Pages
├── assets/
│   ├── logos/                       # Logotipos e símbolos vetoriais
│   │   ├── logo-horizontal.svg      # Assinatura horizontal principal
│   │   ├── logo-empilhado.svg       # Assinatura vertical / empilhada
│   │   ├── logo-horizontal-reverso.svg # Assinatura para fundos escuros
│   │   ├── logo-horizontal-monocromatico.svg # Versão em uma única cor
│   │   ├── logo-simbolo.svg         # Mascote completo isolado
│   │   ├── logo-simbolo-pequeno.svg # Símbolo simplificado para < 24px
│   │   ├── avatar.svg               # Avatar quadrado/redondo para redes sociais
│   │   └── favicon.svg              # Ícone para navegadores e web apps
│   ├── patterns/
│   │   └── padrao-cauda.svg         # Elemento gráfico e padronagem da curva da cauda
│   └── github/
│       ├── nbx-header.svg           # Cabeçalho para o README de perfil do GitHub
│       └── profile/                 # Assets do perfil da organização
├── docs/
│   ├── visao-geral.html             # Prancha com exemplos de aplicação digital e física
│   └── guia-identidade.html         # Manual com regras de proporção e tom de voz
├── brand.json                       # Design tokens oficiais em JSON
└── index.html                       # Aplicação web do Brand Hub para o GitHub Pages
```

---

## 🎨 Paleta de Cores (Design Tokens)

| Cor | HEX | Função |
| :--- | :--- | :--- |
| **Grafite macio** | `#302B28` | Cor principal institucional, texto e silhueta |
| **Casca** | `#57483F` | Apoio, contraste e elementos secundários |
| **Aveia** | `#E7D9C9` | Rosto do mascote, fundos acolhedores e padrão |
| **Papel** | `#F8F4EC` | Fundo institucional padrão claro |
| **Argila clara** | `#B3A393` | Detalhes secundários, bordas e divisores |

---

## 🔤 Tipografia

- **Logotipo:** Letras convertidas em contornos vetoriais; não requer instalação de fontes externas para exibição fiel.
- **Títulos:** [Nunito Sans](https://fonts.google.com/specimen/Nunito+Sans) (pesos 700 a 900). Alternativa: *Segoe UI*.
- **Texto e Interface:** *Segoe UI* (pesos 400 a 600). Alternativa: *Arial, sans-serif*.

---

## 📌 Uso da Marca

1. **Fundos:** Utilize a versão colorida preferencialmente sobre papel (`#F8F4EC`), branco ou aveia (`#E7D9C9`). Para fundos grafite (`#302B28`) ou escuros, utilize a versão **horizontal reversa**.
2. **Respiro:** Mantenha um respiro mínimo ao redor do símbolo equivalente à altura dos olhos do macaco.
3. **Escala:** Para tamanhos inferiores a 24 px, utilize sempre o arquivo `logo-simbolo-pequeno.svg`.
4. **Integridade:** Não rotacione, não estique, não aplique sombras, relevos ou troque as cores da marca.
