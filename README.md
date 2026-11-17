![CI](https://github.com/SEU_USUARIO/SEU_REPOSITORIO/actions/workflows/ci.yml/badge.svg)

# Portfólio Profissional - CI/CD

Site estático com validações em Pull Requests para a branch `main` e publicação automática no GitHub Pages após o merge.

## Estrutura
- `index.html`: conteúdo do portfólio
- `style.css`: identidade visual responsiva
- `imagens/`: pasta reservada para imagens otimizadas
- `.github/workflows/ci.yml`: qualidade e integridade
- `.github/workflows/deploy.yml`: publicação automatizada

## Uso local
Execute `npm install`, `npm run lint` e `npm run links`.

## Configurações necessárias
1. Substitua `nandazzq/portifolio-devops` na URL do badge.
2. Em Settings > Pages, defina **GitHub Actions** como fonte de publicação.
3. Proteja `main` em Settings > Rules > Rulesets, exigindo sucesso das duas verificações de CI.
4. Opcional: crie o secret `DISCORD_WEBHOOK_URL` para receber alertas de falha no deploy.
5. Convide `09116428-collab` como colaboradora em Settings > Collaborators.

## Link do projeto publicado
Preencha após publicar: `https://SEU_USUARIO.github.io/SEU_REPOSITORIO/`.
