# Hackathon ONE G9 — Página Web

Página web para apresentação dos projetos do Hackathon do programa **Oracle Next Education (ONE)**, desenvolvida com HTML, CSS e JavaScript puros — pronta para deploy no **GitHub Pages**.

---

## 📁 Estrutura do Projeto

```
docs/
├── index.html          # Página principal
├── style.css           # Estilos (design dark premium)
├── script.js           # Animações e interatividade
├── .nojekyll           # Necessário para GitHub Pages
├── assets/             # Logos das empresas parceiras
│   ├── alura-logo.png
│   ├── oracle-logo.png
│   ├── one-logo.png
│   └── nocountry-logo.png
└── pdfs/               # Documentação PDF de cada projeto
    ├── projeto-1-contentai.pdf
    ├── projeto-2-financeai.pdf
    └── projeto-3-energiai.pdf
```

---

## 🖼️ Como Adicionar os Logos

Coloque os arquivos de logo na pasta `docs/assets/` com os seguintes nomes:

| Arquivo               | Descrição              |
|-----------------------|------------------------|
| `alura-logo.png`      | Logo da Alura          |
| `oracle-logo.png`     | Logo da Oracle         |
| `one-logo.png`        | Logo do programa ONE   |
| `nocountry-logo.png`  | Logo da NoCountry      |

> Os logos são exibidos em branco (filtro `invert`) sobre o fundo escuro. Qualquer formato PNG com fundo transparente funciona bem.

---

## 📄 Como Adicionar os PDFs

Coloque os arquivos PDF na pasta `docs/pdfs/` com os seguintes nomes:

| Arquivo                        | Projeto       |
|-------------------------------|---------------|
| `projeto-1-contentai.pdf`     | ContentAI     |
| `projeto-2-financeai.pdf`     | FinanceAI     |
| `projeto-3-energiai.pdf`      | EnergiAI      |

---

## 🚀 Deploy no GitHub Pages

1. Faça o push deste repositório para o GitHub
2. Vá em **Settings → Pages**
3. Em **Source**, selecione a branch `main` e a pasta `/docs`
4. Clique em **Save**
5. Aguarde alguns minutos — a URL será exibida automaticamente

---

## 🛠️ Tecnologias

- HTML5 semântico
- CSS3 com variáveis customizadas (design dark premium)
- JavaScript vanilla (sem dependências)
- Fontes: Inter + Space Grotesk (Google Fonts)
- Pronto para GitHub Pages (sem build step necessário)
