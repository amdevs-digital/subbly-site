# Subbly — Site público

Páginas estáticas para a submissão do app na Shopify. Cada arquivo é
autossuficiente (HTML único com CSS, fontes, imagens e lógica embutidos),
não precisa de servidor, build nem dependências.

## Arquivos

- `index.html` — Landing page (PT/EN)
- `termos.html` — Termos de Serviço (PT/EN)
- `privacidade.html` — Política de Privacidade (PT/EN)

Os links entre as páginas e o seletor de idioma já funcionam.

## Testar localmente

Abra `index.html` no navegador (duplo clique). Só isso.

## Publicar com GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `subbly-site`).
2. Arraste **todo o conteúdo desta pasta** para o repositório
   (ou `git add . && git commit -m "site" && git push`).
3. No GitHub: **Settings → Pages**.
4. Em **Source**, escolha a branch `main` e a pasta `/ (root)`. Salve.
5. Em ~1 minuto o site fica no ar em
   `https://SEU-USUARIO.github.io/subbly-site/`.

### Domínio próprio (ex.: trysubbly.com)

- Em **Settings → Pages → Custom domain**, informe seu domínio.
- No seu provedor de DNS, aponte um registro `CNAME` para
  `SEU-USUARIO.github.io` (ou registros `A` para os IPs do GitHub Pages).

## Alternativas (arraste-e-solte, sem Git)

- **Netlify Drop** (app.netlify.com/drop) — arraste a pasta, site no ar.
- **Vercel** (vercel.com) — importe o repositório.

## Observação

Estas são as páginas **institucionais**. O aplicativo de assinaturas em si
(cobrança em cartão, criação de planos, portal do assinante) é um software
à parte, a ser desenvolvido por uma equipe de engenharia.
