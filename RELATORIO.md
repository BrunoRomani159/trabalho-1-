# Relatório de aprendizagem — Publicando uma página no GitHub Pages

**Aluno(a):** [SEU NOME COMPLETO] | **Turma:** [TURMA] | **Disciplina:** Desenvolvimento Web I

> Os trechos entre [colchetes] são para você preencher com a sua experiência real. Este relatório vale 5,0 pontos e deve contar o SEU caminho, com os erros que você teve de verdade.

## 1. O projeto

Criei uma página sobre o jogo **Deepwoken**, pensada para quem nunca jogou. Escolhi esse tema porque [por que você gosta do jogo]. A página explica o que é o jogo, o combate, os atributos, os Oaths, os primeiros passos e um glossário.

Links: site [LINK DO SITE] e repositório [LINK DO REPOSITÓRIO].

## 2. Passo a passo do que fiz

1. **Pesquisa inicial.** Li a documentação oficial do GitHub Pages (docs.github.com/pages) e entendi que ele publica arquivos estáticos que estão em um repositório. [Conte o que você achou mais difícil de entender.]
2. **Planejamento.** Defini as seções da página e a ideia visual: uma "descida" ao fundo do mar, com o fundo escurecendo conforme a página rola. [Conte se mudou de ideia durante o trabalho.]
3. **Escrita do HTML.** Montei o `index.html` com tags semânticas (`header`, `main`, `section`, `footer`), listas, `details` e `summary` para o glossário, que funciona sem JavaScript.
4. **Escrita do CSS.** Criei `css/style.css` com variáveis (`:root`), gradiente no fundo, CSS Grid para os layouts, `position: sticky` para os marcadores de profundidade e `@media` para o celular. [Descreva um problema de layout que você teve e como resolveu.]
5. **Teste local.** Abri o `index.html` no navegador e testei em tela pequena usando as ferramentas do desenvolvedor (F12).
6. **Git.** Iniciei o repositório e fiz commits separados por assunto (HTML, CSS, documentação).
7. **GitHub.** Criei o repositório público, conectei com `git remote add` e enviei com `git push`. [Cite erros, como de autenticação, e como resolveu.]
8. **Ativação do GitHub Pages.** Em Settings > Pages, escolhi a branch `main` e a pasta raiz. Depois de alguns minutos, o site abriu. Testei em aba anônima.

## 3. Ferramentas e por que escolhi cada uma

| Ferramenta | Por que usei |
|---|---|
| HTML e CSS | Exigência do trabalho e base da web, vistos nos Encontros 1 e 2 |
| Git | Controla as versões do código e registra o histórico |
| GitHub | Hospeda o repositório e serve como base para o Pages |
| GitHub Pages | Publica a página de graça, com um endereço público |
| Editor de código [qual?] | [motivo] |
| MDN Web Docs | Consultar propriedades de CSS, como `grid` e `sticky` |
| Google Fonts | Fontes Cormorant Garamond e Karla, para dar identidade ao texto |

## 4. Conceitos novos que aprendi

- **Site estático:** arquivos prontos que o servidor só entrega ao navegador, sem processar nada.
- **GitHub Pages:** serviço que transforma um repositório em site.
- **Git:** `init` cria o repositório, `add` escolhe o que entra no próximo commit, `commit` grava uma versão, `push` envia para o GitHub.
- **Commits organizados:** uma mudança por commit, com mensagem clara.
- **Markdown:** sintaxe simples de texto usada em README.md.
- **`details`/`summary`:** elemento HTML que abre e fecha conteúdo sem JavaScript.
- **Variáveis CSS e `@media`:** reaproveitar cores e adaptar a página a telas diferentes.
- [Adicione o que mais você aprendeu.]

## 5. Dificuldades e erros

- [Erro 1: o que apareceu, o que pesquisou, como resolveu.]
- [Erro 2: ...]

## 6. Conclusão

[Em poucas linhas: o que você achou do processo e o que faria diferente.]

## 7. Fontes consultadas

- https://docs.github.com/pages
- https://developer.mozilla.org/
