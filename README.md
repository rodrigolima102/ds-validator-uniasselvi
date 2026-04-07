# DS Validator — Uniasselvi

Validador de aderência ao Design System da Uniasselvi.

Analisa: componentes, cores, tipografia (Titillium Web · Roboto), espaçamentos, radius, variáveis e acessibilidade (WCAG 2.2).

## Estrutura

```
├── api/
│   └── figma.js        # Serverless function (proxy Figma API)
├── public/
│   └── index.html      # Interface do validador
├── vercel.json
└── package.json
```

## Deploy

```bash
git init
git add .
git commit -m "feat: ds validator uniasselvi"
git remote add origin https://github.com/SEU_USUARIO/ds-validator-uniasselvi.git
git push -u origin main
```

Deploy na Vercel: importe o repositório e clique em Deploy.
