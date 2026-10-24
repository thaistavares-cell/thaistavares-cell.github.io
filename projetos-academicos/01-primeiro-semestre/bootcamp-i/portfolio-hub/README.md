# Portfolio Hub: vitrine acadêmica

Projeto da disciplina Bootcamp I, Ciência da Computação (UniCEUB).

## Objetivo

Construir um repositório público que organize minha produção acadêmica e
publicá-lo como site com o GitHub Pages.

## O que foi feito

- Estrutura do repositório separando projetos acadêmicos e projetos pessoais,
  com uma pasta própria para os arquivos do site:

  ```
  thaistavares-cell.github.io/
  ├── index.html            → página do site
  ├── README.md             → apresentação do repositório
  ├── assets/               → CSS e imagens do site
  ├── projetos-academicos/  → trabalhos do curso
  └── projetos-pessoais/    → iniciativas próprias
  ```

- Site publicado com GitHub Pages: https://thaistavares-cell.github.io
- Layout responsivo, ajustado para computador e celular
- Fluxo de trabalho com Git: clone, commit e push a partir do VS Code

## Como este site foi feito

- **HTML, CSS e um pouco de JavaScript, sem framework.** Um site deste tamanho
  não precisa de framework: carrega mais rápido e eu entendo cada linha do código.
- **GitHub Pages.** A hospedagem sai direto do repositório. Cada envio para o
  GitHub publica a nova versão automaticamente.
- **HTML semântico.** Tags como `header`, `main`, `section` e `footer` descrevem a
  função de cada parte da página, o que ajuda leitores de tela e mecanismos de busca.
- **Open Graph.** Tags que definem o título, a descrição e a imagem do cartão que
  aparece quando o link é compartilhado no WhatsApp ou no LinkedIn.
- **Acessibilidade.** A animação da abertura respeita a preferência de movimento
  reduzido do sistema operacional.
- **Commits convencionais.** As mensagens seguem o padrão `tipo(escopo): descrição`,
  para o histórico ser fácil de ler.

## O que aprendi

- Como o GitHub Pages publica um site direto de um repositório
- A diferença entre configuração global e local do Git, e como proteger o
  e-mail nos commits públicos
- Como reescrever o histórico do Git (amend, rebase) e quando isso é seguro
- Como imagens se comportam no versionamento e na tela do celular

## Entregas

- Site: https://thaistavares-cell.github.io
