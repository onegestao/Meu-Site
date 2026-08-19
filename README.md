[README.md](https://github.com/user-attachments/files/31240296/README.md)
# One Way Administradora — Site Institucional

Site institucional de página única da **ONE WAY ADMINISTRADORA DE MÃO DE OBRA LTDA**.

## Sobre

Empresa especializada em gestão administrativa e operacional com mão de obra
terceirizada, oferecendo equipes qualificadas para logística, e-commerce,
atendimento, monitoramento e facilities.

- **CNPJ:** 63.004.633/0001-98
- **Sede:** Alameda Rio Negro, 503, Sala 2020 — Alphaville, Barueri / SP
- **WhatsApp:** (11) 9 6571-7829
- **E-mail:** dp@onewayadministradora.com | rh@onewayadministradora.com (vagas)

## Tecnologia

Página única, sem build step. Tudo carregado via CDN:

- [Tailwind CSS](https://tailwindcss.com/) (Play CDN)
- [Font Awesome 6](https://fontawesome.com/)
- [Inter](https://fonts.google.com/specimen/Inter) (Google Fonts)

## Como rodar localmente

Basta abrir o `index.html` no navegador. Ou, para servir via HTTP:

```bash
python3 -m http.server 8000
```

E acessar http://localhost:8000

## Publicação

Publicado via **GitHub Pages** a partir da branch `main`.

## Estrutura

```
.
├── index.html   # site completo (HTML + CSS + config do Tailwind)
├── .nojekyll    # desativa o processamento Jekyll do GitHub Pages
└── README.md
```
