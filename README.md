# Manual Visual do Preparo Correto dos Chás — Página de Vendas

Landing page de vendas (single-page) para o ebook **Manual Visual do Preparo Correto dos Chás**, construída com HTML/CSS/JS puro e empacotada com [Vite](https://vitejs.dev/).

## Estrutura

```
.
├── index.html          # A página de vendas completa (HTML + CSS + JS inline)
├── assets/             # Imagens (header, fichas, bônus, carrossel, depoimentos)
│   ├── header.png
│   ├── bonus/          # Mockups dos bônus
│   ├── carrossel/      # Fichas do carrossel "Veja como é por dentro"
│   ├── depoimentos/    # Fotos das provas sociais
│   └── secao2/         # Fichas da vitrine + capa do ebook
├── package.json
├── vercel.json         # Configuração de deploy na Vercel
└── .gitignore
```

## Rodar localmente

```bash
npm install
npm run dev      # servidor de desenvolvimento
npm run build    # gera o dist/ de produção
npm run preview  # pré-visualiza o build
```

## Deploy na Vercel

O projeto já está pronto para a Vercel. Basta importar o repositório — a Vercel detecta o Vite automaticamente e usa as configurações do `vercel.json`:

- **Framework:** Vite
- **Build:** `npm run build`
- **Output:** `dist`

## Integrações

- **Pixel Utmify** para rastreamento de conversões.
- **Checkout** via links da Wiapy (oferta principal, básico e downsell).
