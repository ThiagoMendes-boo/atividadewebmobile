# Painel de Notas - Cálculo 2

**Tema:** painel de notas de uma universidade, na disciplina de Matemática - Cálculo 2.

## Interface

A tela mostra uma navbar com o nome do projeto, uma seção inicial com título e descrição, três cards (Nota 1, Nota 2 e Média final), um alert com o resultado e um footer. O layout é responsivo com `container`, `row` e `col`: os cards ficam lado a lado em telas médias e empilhados no celular.

## Componentes Bootstrap utilizados

`container`, `row`, `col`, `navbar`, `card`, `button`, `badge`, `alert` e `footer`. O Bootstrap é carregado via CDN, sem CSS próprio.

## let, const e var

- `const`: valor que não muda. Usei em `nomeAluno`, `curso`, `disciplina` e `notaMinima`.
- `let`: valor que pode mudar. Usei em `nota1`, `nota2` e `tarefasEntregues`.
- `var`: forma antiga de declarar variáveis, com escopo de função e hoisting, o que causa erros difíceis de achar. Hoje se prefere `let` e `const` por terem escopo de bloco e serem mais previsíveis. Usei `var` apenas em `exemploAntigo`, para demonstração.

## Tipos de dados

- string: `"Thiago"`, `"Painel de notas"`
- number: `10`, `8`, `7`
- boolean: `true` (matrícula ativa) e o resultado de `media >= notaMinima`
- null: `observacao`, sem valor definido

## Condição if/else

js
if (media >= notaMinima) {
  console.log("Aprovado");
} else {
  console.log("Precisa revisar");
}


Se a média for maior ou igual à nota mínima (7), o aluno está aprovado. Testei os dois caminhos trocando `nota2` para um valor baixo e voltando ao original.


## Maior dificuldade
Entender a diferença entre let, const e var, e montar o layout responsivo com row e col.

## Como foi resolvida
Pesquisei na documentação do Bootstrap e testei no Console do navegador, alterando os valores das variáveis até entender o comportamento.