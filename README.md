# CloudyArc Games website

Site estático em Astro para apresentar o estúdio e seus jogos. O projeto mantém os Termos do Matchzada e o arquivo de verificação do Search Console em `public/`, para que sejam publicados em `/termos.html` e `/googlec0db494cbfcb2402.html`.

## Requisitos
- Node.js 22.23.4 ou superior.
- Dependências travadas em `package-lock.json`.

## Comandos
- `npm run dev` inicia o preview local.
- `npm run build` gera o site em `dist/`.
- `npm run preview` serve a última build localmente.

## Stack
Astro sem integração de interface: HTML semântico, CSS e saída estática. O workflow em `.github/workflows/deploy.yml` publica `dist/` no GitHub Pages a cada push para `main` e também permite execução manual.
