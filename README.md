# .github

Arquivos de comunidade da org G30AI. Este repo é público: não ponha nada sensível aqui.

## Template de PR

O `pull_request_template.md` vale para todo repo da org que não tem template próprio. As seções seguem a decisão G30AI/g30-dev#67:

- A primeira linha é `Closes G30AI/<repo>#<n>`. A automação de Status do board acha a issue por ela.
- `## O que muda` e `## Verificação` são obrigatórias. O check de estrutura do `G30AI/g30-ci` reprova o PR sem elas.
- As outras seções são opcionais.

Um repo só cria template próprio se precisar de uma seção a mais. Um template próprio substitui este inteiro, então ele tem de manter a linha `Closes` e as 2 seções obrigatórias.

Este repo não guarda workflow. Os workflows reusáveis ficam no repo privado `G30AI/g30-ci` (decisão G30AI/g30-dev#66).
