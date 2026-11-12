# Site de estatísticas do futebol brasileiro

Páginas de clube no estilo das fichas de pré-jogo: elenco por competição, pré-jogo e notícias.

## Estrutura
- `index.html`: lista dos clubes da Série A 2026
- `<clube>.html`: página de cada clube (visual e lógica; não precisa mexer para atualizar números)
- `dados/<clube>.json`: todos os dados do clube (elenco, jogos, notícias, pré-jogo)

## Atualizar depois de um jogo
Substitua `dados/<clube>.json` pela versão nova (Add file → Upload files, mesmo nome) e faça o commit.

## Clube novo
Envie `<clube>.html` e `dados/<clube>.json` e preencha o `url` do clube na lista `CLUBES` do `index.html` com `<clube>.html`.

Abrir os arquivos direto do computador não carrega os dados (o navegador bloqueia). Teste pelo site publicado ou com `python3 -m http.server`.
