# Padrões e Nomenclaturas Git da UnBall
Guia para padronizar as nomenclaturas de commits, issues e branches dos repositórios UnBall.

### Lista de prefixos
Os prefixos a seguir se aplicam tanto a commits quanto a issues e branches.
<table>
  <thead>
    <tr>
      <th>Prefixo</th>
      <th>Descrição</th>
      <th>Emoji</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>docs</code></td>
      <td>Indica que houveram mudanças na documentação, como por exemplo no README.md do seu repositório. (Não inclui alterações em código)</td>
      <td>📘<code>:book_blue:</code></td>
    </tr>
    <tr>
      <td><code>feat</code></td>
      <td>Um novo recurso (feature/funcionalidade, componentes, etc) será adicionado ao repositório.</td>
      <td>✨<code>:sparkles:</code></td>
    </tr>
    <tr>
      <td><code>fix</code></td>
      <td>Correção de um bug, solução de um problema no código.</td>
      <td>⚙️<code>:gear:</code></td>
    </tr>
    <tr>
      <td><code>refac</code></td>
      <td>Mudança no código que não adiciona uma funcionalidade e também não corrige bug.</td>
      <td>♻️<code>:recycle:</code></td>
    </tr>
    <tr>
      <td><code>style</code></td>
      <td>Mudança no código que não afeta seu significado (espaço em branco, formatação, ponto e vírgula, etc).</td>
      <td>🎨<code>:art:</code></td>
    </tr>
    <tr>
      <td><code>improv</code></td>
      <td>Improvement. Uma melhoria em algo já existente, seja de performance, de escrita, de layout, etc.</td>
      <td>🚀<code>:rocket:</code></td>
    </tr>
    <tr>
      <td><code>test</code></td>
      <td>Adicionar ou corrigir testes.</td>
      <td>☘️<code>:shamrock:</code></td>
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
> `emoji`prefixo: Nome da Issue
- Colocar o emoji do prefixo correspondente na frente.
- Primeira letra do nome da issue maiúscula.

### Exemplos
`✨feat: Implementar comunicação com o rádio`

`⚙️fix: Tirar prints de debug`

`☘️test: Criar testes unitários para validação de entrada`

`📘docs: Atualizar README.md`

## Commits
### Estrutura de uma mensagem de commit
> `emoji`Mensagem de commit
- Deve ser curta, clara e direta.
- Priorizar linguagem imperativa (pode ser gerúndio também):
  - Responda mentalmente a pergunta: o que esse commit *faz*? E escreva a resposta como a mensagem do commit
  - Em caso de gerúndio: o que esse commit *está* fazendo?
- Para descrever com detalhes, usar a descrição do commit.
- Usar um emoji no início da mensagem de commit representando o objetivo do commit:
  - Usar a lógica dos prefixos

### Exemplos
`✨Cria esboço inicial das classes da interface`

`♻️Cria arquivo de constantes para nomes de cores`

`✨Implementando o sistema de chute`

`⚙️Consertando spin do robô atacante`
