
# Fernando Garcia — Desenvolvedor Web

<div align="center">
  <a href="https://github.com/fernandognu">
    <img height="160px" src="https://github-readme-stats.vercel.app/api?username=fernandognu&show_icons=true&theme=dracula&include_all_commits=true&count_private=true" alt="GitHub stats"/>
    <img height="160px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fernandognu&layout=compact&langs_count=7&theme=dracula" alt="Top languages"/>
  </a>

  <p>
    <a href="https://instagram.com/nandu_garcia" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
    <a href="mailto:fernandogdac@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white"></a>
    <a href="https://www.linkedin.com/in/fernandognu/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  </p>

  <p>
    ![Snake animation](https://github.com/fernandognu/fernandognu/blob/output/github-contribution-grid-snake.svg)
  </p>
</div>

---

**Sobre mim**

- Sou Fernando Garcia, desenvolvedor web com foco em criação de aplicações responsivas e escaláveis.
- Gosto de trabalhar com JavaScript/TypeScript, frameworks modernos e boas práticas de arquitetura.

**Tecnologias & Ferramentas**

- JavaScript / TypeScript
- Node.js
- React / Next.js
- HTML, CSS, SASS
- Git & GitHub
- Bancos de dados (MySQL, PostgreSQL, MongoDB)

**Projetos em destaque**

- Projeto A — curta descrição e link: `https://github.com/fernandognu/projeto-a`
- Projeto B — curta descrição e link: `https://github.com/fernandognu/projeto-b`

Substitua os itens acima pelos repositórios que você deseja destacar.

**Como executar um projeto (exemplo genérico)**

1. Clone o repositório: `git clone https://github.com/fernandognu/<repo>.git`
2. Entre na pasta: `cd <repo>`
3. Instale dependências: `npm install` ou `yarn`
4. Rode em desenvolvimento: `npm start` ou `npm run dev`

Adapte os comandos conforme cada projeto.

**Contribuições**

- Pull requests são bem-vindas. Abra uma issue antes de começar mudanças grandes.

**Contato**

- Email: `fernandogdac@gmail.com`
- LinkedIn: https://www.linkedin.com/in/fernandognu/
- Instagram: https://instagram.com/nandu_garcia

---

**Licença**

Este repositório está coberto pela licença presente no arquivo `LICENSE`.

---

**Deploy**

- Este repositório contém um workflow (`.github/workflows/cobrinha.yml`) que gera um SVG de contribuição e publica a pasta `dist` na branch `output` automaticamente (agendamento + `workflow_dispatch`).
- Para servir como site via GitHub Pages, ative nas configurações do repositório: `Settings > Pages` e selecione a branch `output` como fonte (pasta `/`).

Comandos manuais de exemplo (projeto front-end estático):

1. Build (exemplo):

```bash
npm run build
```

2. Publicar a pasta `dist` na branch `output` (duas opções):

- Usando `gh-pages` (instale se necessário):

```bash
npx gh-pages -d dist -b output
```

- Usando `git subtree`:

```bash
git add dist -f
git commit -m "build: deploy dist"
git subtree push --prefix dist origin output
```

Observações:

- O workflow já utilizado neste repositório publica `dist` automaticamente com o `GITHUB_TOKEN` (ver `.github/workflows/cobrinha.yml`).
- Se preferir outro fluxo de deploy (Netlify, Vercel, Docker, servidor próprio), diga qual e eu adapto as instruções.

