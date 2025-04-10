# Padrões e Nomenclaturas Git da UnBall
Guia para padronizar as nomenclaturas de commits, issues e branches dos repositórios UnBall.

### Lista de prefixos
Os prefixos a seguir se aplicam tanto a commits quanto a issues e branches.
<table>
  <thead>
    <tr>
      <th>Prefixo</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>docs</code></td>
      <td>Indica que houveram mudanças na documentação, como por exemplo no README.md do seu repositório. (Não inclui alterações em código)</td>
    </tr>
    <tr>
      <td><code>feat</code></td>
      <td>Um novo recurso (feature/funcionalidade, componentes, etc) será adicionado ao repositório.</td>
    </tr>
    <tr>
      <td><code>fix</code></td>
      <td>Correção de um bug, solução de um problema no código.</td>
    </tr>
    <tr>
      <td><code>refac</code></td>
      <td>Mudança no código que não adiciona uma funcionalidade e também não corrige bug.</td>
    </tr>
    <tr>
      <td><code>style</code></td>
      <td>Mudança no código que não afeta seu significado (espaço em branco, formatação, ponto e vírgula, etc).</td>
    </tr>
    <tr>
      <td><code>improv</code></td>
      <td>Improvement. Uma melhoria em algo já existente, seja de performance, de escrita, de layout, etc.</td>
    </tr>
    <tr>
      <td><code>test</code></td>
      <td>Adicionar ou corrigir testes.</td>
    </tr>
  </tbody>
</table>


## Branches
### Estrutura do nome de um branch
> prefixo/nome-da-branch
- Espaços entre palavras substituídos por um hífen.
- Evitar acentuação e caracteres especiais.
  - Mesmo em português
### Exemplos
`feat/lei-de-controle`
`fix/constantes-do-controle`
`refac/cria-ambiente-docker`

## Issues
### Estrutura do nome de uma issue
> prefixo: Nome da Issue
- Primeira letra do nome da issue maiúscula.
- Colocar verbos no infinitivo
  - Responda mentalmente a pergunta: o que deve ser feito nessa issue?

### Exemplos
`feat: Implementar comunicação com o rádio`

`fix: Tirar prints de debug`

`test: Criar testes unitários para validação de entrada`

`docs: Atualizar README.md`

## Commits
### Estrutura de uma mensagem de commit
> `prefixo`: mensagem de commit
- Deve ser curta, clara e direta.
- Priorizar linguagem em terceira pessoa do singular (pode ser gerúndio também):
  - Responda mentalmente a pergunta: o que esse commit *faz*? E escreva a resposta como a mensagem do commit
  - Em caso de gerúndio: o que esse commit *está* fazendo?
- Para descrever com detalhes, usar a descrição do commit.
- Usar um prefixo no início da mensagem de commit representando o objetivo do commit

### Exemplos
`feat: cria esboço inicial das classes da interface`

`refac: cria arquivo de constantes para nomes de cores`

`feat: implementando o sistema de chute`

`fix: consertando spin do robô atacante`
