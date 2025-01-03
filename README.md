# Padrões de commits

De acordo com a documentação do **[Conventional Commits](https://www.conventionalcommits.org/pt-br)**, commits semânticos são uma convenção simples para ser utilizada nas mensagens de commit. Essa convenção define um conjunto de regras para criar um histórico de commit explícito, o que facilita a criação de ferramentas automatizadas.

Esses commits auxiliarão você e sua equipe a entenderem de forma facilitada quais alterações foram realizadas no trecho de código que foi commitado.

Essa identificação ocorre por meio de uma palavra e emoji que identifica se aquele commit realizado se trata de uma alteração de código, atualização de pacotes, documentação, alteração de visual, teste...

## Tipo e descrição

O commit semântico possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.

- `feat`- Commits do tipo feat indicam que seu trecho de código está incluindo um **novo recurso** (se relaciona com o MINOR do versionamento semântico).

- `fix` - Commits do tipo fix indicam que seu trecho de código commitado está **solucionando um problema** (bug fix), (se relaciona com o PATCH do versionamento semântico).

- `docs` - Commits do tipo docs indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

- `test` - Commits do tipo test são utilizados quando são realizadas **alterações em testes**, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)

- `build` - Commits do tipo build são utilizados quando são realizadas modificações em **arquivos de build e dependências**.

- `perf` - Commits do tipo perf servem para identificar quaisquer alterações de código que estejam relacionadas a **performance**.

- `style` - Commits do tipo style indicam que houveram alterações referentes a **formatações de código**, semicolons, trailing spaces, lint... (Não inclui alterações em código).

- `refactor` - Commits do tipo refactor referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

- `chore` - Commits do tipo chore indicam **atualizações de tarefas** de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)

- `ci` - Commits do tipo ci indicam mudanças relacionadas a **integração contínua** (_continuous integration_).

- `raw` - Commits do tipo raw indicam mudanças relacionadas a arquivos de configurações, dados, features, parâmetros.

- `cleanup` - Commits do tipo cleanup são utilizados para remover código comentado, trechos desnecessários ou qualquer outra forma de limpeza do código-fonte, visando aprimorar sua legibilidade e manutenibilidade.

- `remove` - Commits do tipo remove indicam a exclusão de arquivos, diretórios ou funcionalidades obsoletas ou não utilizadas, reduzindo o tamanho e a complexidade do projeto e mantendo-o mais organizado.

## Recomendações

- Adicione um tipo consistente com o título do conteúdo.
- Recomendamos que na primeira linha deve ter no máximo 4 palavras.
- Para descrever com detalhes, usar a descrição do commit.
- Usar um emoji no início da mensagem de commit representando sobre o commit.
- Os links precisam ser adicionados em sua forma mais autêntica, ou seja: sem encurtadores de link e links afiliados.

## Complementos de commits

- **Rodapé:** informação sobre o revisor e número do card no Trello ou Jira. Exemplo: Reviewed-by: Elisandro Mello Refs #133
- **Corpo:** descrições mais precisas do que está contido no commit, apresentando impactos e os motivos pelos quais foram empregadas as alterações no código, como também instruções essenciais para intervenções futuras. Exemplo: see the issue for details on typos fixed.
- **Descrições:** uma descrição sucinta da mudança. Exemplo: correct minor typos in code

## Padrões de palavras-chave

<table>
  <thead>
    <tr>
      <th>Tipo do commit</th>
      <th>Palavra-chave</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>Acessibilidade</td>
      <td><code>accessibility</code></td>
    </tr>
    <tr>
      <td>Atualizando a versão de um submódulo</td>
      <td><code>arrow_up</code></td>
    </tr>
    <tr>
      <td>Retrocedendo a versão de um submódulo</td>
      <td><code>arrow_down</code></td>
    </tr>
    <tr>
      <td>Adicionando uma dependência</td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Animações e transições</td>
      <td><code>dizzy</code></td>
    </tr>
    <tr>
      <td>Bugfix</td>
      <td><code>bugfix</code></td>
    </tr>
    <tr>
      <td>Comentários</td>
      <td><code>comments</code></td>
    </tr>
    <tr>
      <td>Commit inicial</td>
      <td><code>init</code></td>
    </tr>
    <tr>
      <td>Configuração</td>
      <td><code>config</code></td>
    </tr>
    <tr>
      <td>Deploy</td>
      <td><code>deploy</code></td>
    </tr>
    <tr>
      <td>Documentação</td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Em progresso</td>
      <td><code>construction</code></td>
    </tr>
    <tr>
      <td>Infraestrutura</td>
      <td><code>infrastructure</code></td>
    </tr>
    <tr>
      <td>Novo recurso</td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Performance</td>
      <td><code>perf</code></td>
    </tr>
    <tr>
        <td>Refatoração</td>
        <td><code>refact</code></td>
    </tr>
    <tr>
      <td>Limpeza de Código</td>
      <td><code>cleanup</code></td>
    </tr>
    <tr>
      <td>Removendo um arquivo</td>
      <td><code>remove_file</code></td>
    </tr>
    <tr>
      <td>Removendo uma dependência</td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Responsividade</td>
      <td><code>responsiveness</code></td>
    </tr>
    <tr>
      <td>Segurança</td>
      <td><code>sec</code>c</td>
    </tr>
    <tr>
      <td>Testes</td>
      <td><code>test</code></td>
    </tr>
  </tbody>
</table>

## 💻 Exemplos

<table>
  <thead>
    <tr>
      <th>Comando Git</th>
      <th>Resultado no GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m "init: Commit inicial"</code>
      </td>
      <td>init: Commit inicial</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "docs: Atualização do README"</code>
      </td>
      <td>docs: Atualização do README</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "bugfix: Loop infinito na linha 50"</code>
      </td>
      <td>bugfix: Loop infinito na linha 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "feat: Página de login"</code>
      </td>
      <td>feat: Página de login</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "infrastructure: Modificação no Dockerfile"</code>
      </td>
      <td>infrastructure: Modificação no Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "refact: Passando para arrow functions"</code>
      </td>
      <td>refact: Passando para arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "perf: Melhoria no tempo de resposta"</code>
      </td>
      <td>perf: Melhoria no tempo de resposta</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "fix: Revertendo mudanças ineficientes"</code>
      </td>
      <td>fix: Revertendo mudanças ineficientes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "feat: Estilização CSS do formulário"</code>
      </td>
      <td>feat: Estilização CSS do formulário</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "test: Criando novo teste"</code>
      </td>
      <td>test: Criando novo teste</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "docs: Comentários sobre a função LoremIpsum( )"</code>
      </td>
      <td>docs: Comentários sobre a função LoremIpsum( )</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "cleanup: Eliminando blocos de código comentados e variáveis não utilizadas na função de validação de formulário"</code>
      </td>
      <td>cleanup: Eliminando blocos de código comentados e variáveis não utilizadas na função de validação de formulário</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "remove_file: Removendo arquivos não utilizados do projeto para manter a organização e atualização contínua"</code>
      </td>
      <td>remove_file: Removendo arquivos não utilizados do projeto para manter a organização e atualização contínua</td>
    </tr>
  </tbody>
</table>

# Principais comandos do Git

- `git clone url-do-repositorio-no-github` - Clona um repositório remoto existente no GitHub para o seu ambiente local.

- `git init` - Inicializa um novo repositório Git no diretório atual.

- `git add .` - Adiciona todos os arquivos e alterações no diretório atual para a área de stage (preparando-os para o commit).

- `git commit -m "mensagem do commit"` - Registra as alterações adicionadas na área de stage com uma mensagem descritiva sobre o que foi modificado.

- `git branch -M main` - Renomeia a branch atual (master) para main. O -M é usado para forçar a renomeação, movendo a branch se necessário.

- `git remote add origin https://github.com/usuario/nome-do-repositorio.git` - Adiciona um repositório remoto chamado origin ao repositório local. Use `https://github.com/usuario` para configurar o repositório remoto com HTTPS ou `git@github.com:usuario` para configurar com SSH.

- `git push -u origin main` - Envia os commits da branch main do repositório local para o repositório remoto origin e define main como a branch padrão para futuros push e pull. O -u (ou --set-upstream) configura a branch upstream para facilitar os próximos comandos git push e git pull e eliminar a necessidade de especificar a branch.

- `git remote add origin git@github.com:usuario/projeto.git` `git branch -M main` `git push -u origin main` - Quando você já tem um repositório local e quer conectá-lo a um repositório remoto no GitHub, adiciona o repositório remoto, renomeia a branch principal para main e envia os commits iniciais.

- `git fetch` - Busca todas as atualizações do repositório remoto sem integrá-las à branch atual. Isso atualiza as referências remotas.

- `git pull origin main` - Atualiza a branch local main com as mudanças do repositório remoto origin. Combina git fetch e git merge.

- `git push --force-with-lease` - Forma mais segura de forçar o envio de alterações locais para o repositório remoto. Verifica se não houve alterações feitas por outros colaboradores desde sua última atualização local, evitando sobrescrever acidentalmente o trabalho de outros.

- `git revert id_do_commit_que_vai_ser_revertido` - Cria um novo commit que desfaz as alterações feitas pelo commit especificado, preservando o histórico. Útil para desfazer mudanças de forma segura sem reescrever o histórico.

- `git reset --hard id_do_commit_anterior_ao_que_vai_ser_apagado` - Redefine o repositório para o estado do commit especificado, apagando todas as mudanças feitas após esse commit. Ideal para uso local. Para sincronizar remotamente, use `git push --force-with-lease` posteriormente.

- `git commit --amend -m "mensagem_reescrita"` - Altera a mensagem do último commit. Após usar este comando, sincronize remotamente com `git push --force-with-lease`.

- `git cherry-pick HASH_DO_COMMIT` - Utilizado para obter um commit específico. Exemplo de uso: Imagine que você tenha duas branchs (main) e (develop) e na segunda você tem 3 commits mas deseja apenas pegar o primeiro commit dela, com o uso de cherry-pick você pode.

# Glossário

- `fork` - Cópia de um repositório para a sua própria conta no GitHub. Isso cria um novo repositório em sua conta que é independente do original, permitindo que você faça alterações sem afetar o repositório original.

- `issues` - Ferramenta usada para gerenciar tarefas, pedidos de novos recursos e correções de bugs em projetos de código aberto. As issues devem ser descritas e listadas, permitindo aos colaboradores discutirem e rastrearem o progresso das mesmas.

- `pull request` - Mecanismo usado para submeter alterações propostas ao repositório original. Um pull request é uma solicitação para que os mantenedores do projeto revisem e potencialmente incorporem as alterações. O pull request passará por um processo de avaliação e pode ser aceito ou rejeitado.

- `gist` - Ferramenta que permite o compartilhamento de trechos de código sem a necessidade de criar um repositório completo. Gists podem ser compartilhados publicamente ou de forma privada.
