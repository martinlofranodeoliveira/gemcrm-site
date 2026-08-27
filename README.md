# Site institucional do GemCRM

Landing page estática publicada em GitHub Pages. Este diretório contém somente a presença pública do produto e pode ser espelhado em um repositório público sem expor o monorepo privado.

## Desenvolvimento local

Não há etapa de build nem dependências de aplicação:

```bash
cd website
python3 -m http.server 4173
```

Abra `http://localhost:4173`.

## Estrutura

- `index.html`: landing page principal
- `styles.css`: identidade visual e responsividade
- `script.js`: menu móvel, header e animações progressivas
- `privacy/`, `terms/` e `changelog/`: páginas institucionais
- `robots.txt` e `sitemap.xml`: descoberta por mecanismos de busca
- `social-card.png`: imagem Open Graph

## Publicação

O conteúdo deste diretório é publicado no repositório público `martinlofranodeoliveira/gemcrm-site`. O domínio canônico é `https://gemcrm.io`.
