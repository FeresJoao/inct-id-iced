# Site do INCT ID-ICED — protótipo v1 (outubro de 2026)

Pacote offline-first: abre por duplo clique em `index.html` (funciona sem internet — fontes e logos são locais).
`robots noindex` ativo enquanto protótipo.

## Arquivos
- `index.html` — página única (8 seções + painel de pendências no topo)
- `styles.css` · `app.js` · `tokens.json`
- `assets/` — fontes OFL (Manrope, Source Sans 3), logos oficiais do kit INCT ID-ICED v1.0, favicon, logo IESP

## Fonte do conteúdo
Tudo ancorado nos documentos do projeto: "Projeto ID-ICED enviado.pdf" (submissão CNPq, Chamada 46/2024), "Resumo do projeto_INCT ID.docx" e "Equipe_INCT_ID-ICED.xlsx" (pasta INCT_ID_ICED). Nenhum dado inventado; o que depende de decisão editorial está marcado no painel de pendências.

## Painel de pendências (topo)
4 pendências em aberto + 18 rascunhos em revisão (chips laranja "rascunho · revisão"). Cada item é clicável e leva ao bloco correspondente. Pendências principais:
- **LAProtesta** — escopo/descrição a definir
- **Contato** — e-mail institucional dedicado + redes oficiais
- **Logos oficiais** dos financiadores (CNPq, CAPES, FAPERJ, MCTI) — hoje como chips tipográficos
- **Domínio/hospedagem** — decisão de publicação

## Para publicar (quando aprovado)
1. GitHub Pages (repo novo, branch main, root) — ou hospedagem própria no servidor (nginx, mesmo rito do OBSERVA-RJ)
2. Remover `noindex` apenas na versão definitiva
3. Trocar os chips dos financiadores pelos logos oficiais quando chegarem