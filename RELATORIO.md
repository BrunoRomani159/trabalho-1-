Links: site https://brunoromani159.github.io/trabalho-1-/ e repositório https://github.com/BrunoRomani159/trabalho-1-.

## 2. Passo a passo do que fiz

1. **Pesquisa inicial.** Li a documentação oficial do GitHub Pages (docs.github.com/pages) e entendi que ele publica arquivos estáticos que estão em um repositório. 
2. **Planejamento.** Defini as seções da página e a ideia visual: uma "descida" ao fundo do mar, com o fundo escurecendo conforme a página rola. 
3. **Escrita do HTML.** Montei o `index.html` com tags semânticas (`header`, `main`, `section`, `footer`), listas, `details` e `summary` para o glossário, que funciona sem JavaScript.
4. **Escrita do CSS.** Criei `css/style.css` com variáveis (`:root`), gradiente no fundo, CSS Grid para os layouts, `position: sticky` para os marcadores de profundidade e `@media` para o celular.
5. **Teste local.** Abri o `index.html` no navegador e testei em tela pequena usando as ferramentas do desenvolvedor (F12).
6. **Git.** Iniciei o repositório e fiz commits separados por assunto (HTML, CSS, documentação).
7. **GitHub.** Criei o repositório público, conectei com `git remote add` e enviei com `git push`.
8. **Ativação do GitHub Pages.** Em Settings > Pages, escolhi a branch `main` e a pasta raiz. Depois de alguns minutos, o site abriu. Testei em aba anônima.

## 3. Ferramentas e por que escolhi cada uma

| Ferramenta | Por que usei |
|---|---|
| HTML e CSS | Exigência do trabalho e base da web, vistos nos Encontros 1 e 2 |
| Git | Controla as versões do código e registra o histórico |
| GitHub | Hospeda o repositório e serve como base para o Pages |
| GitHub Pages | Publica a página de graça, com um endereço público |
| Editor de código vscode | mais pratico |
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



## 6. Conclusão

Este trabalho me mostrou que publicar um site não é tão complicado quanto parece, desde que se entenda o caminho: escrever os arquivos, versionar com Git, enviar ao GitHub e ativar o GitHub Pages. Ver a página aberta em uma aba anônima, com um endereço que qualquer pessoa pode acessar, foi a parte mais satisfatória do processo.

Ao longo do projeto, apliquei o que vimos em sala de HTML e CSS e fui além: usei Grid, variáveis CSS, @media e animações com @keyframes, tudo sem JavaScript. Também percebi que o CSS consegue fazer mais do que eu imaginava, como a demonstração do parry, que mostra a ideia do combate apenas com animação. Por outro lado, aprendi seu limite: sem JavaScript, ela não consegue avaliar o timing de quem clica, então ficou só como ilustração.

Com o Git, entendi na prática por que commits pequenos e com mensagens claras importam: eles contam a história do projeto e facilitam voltar atrás se algo der errado. [Cite um momento em que isso foi útil para você, ou um erro que aconteceu.]

Escolhi o Deepwoken porque queria explicar para quem nunca jogou algo que eu gosto. Isso me obrigou a organizar as informações de forma simples e a conferir os dados na wiki da comunidade em vez de confiar só na memória.

## 7. Fontes consultadas

- https://docs.github.com/pages
- https://developer.mozilla.org/