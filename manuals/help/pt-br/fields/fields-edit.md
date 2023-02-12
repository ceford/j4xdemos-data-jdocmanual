<!-- Filename: Help4.x:Fields:_Edit / Display title: Ajuda4.x:Campos: Editar -->

## Descrição

É aqui que você pode adicionar e editar os campos em artigos, contatos e
usuários.

A tela de ajuda mostra, como exemplo, "usuários".

## Como acessar

**Usuários **→** Campos**

Para adicionar um campo:

- clique no botão **Novo** na barra das ferramentas

Para editar um campo:

- Selecione um **título** a partir da lista

## Captura da tela

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Fields-Edit-screen-pt-br.png"
class="new" title="File:Help-4x-Fields-Edit-screen-pt-br.png">800px</a>

## Campos do formulário

- **Título**: O título para este campo.

### Geral

**Painel esquerdo**

Parâmetros para todos os campos:

- **Tipo**: Se você criar um campo, poderá escolher um dos 16 tipos de
  campos. Quando você salva o campo, esse tipo é permanente. [Aprender
  mais](https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field/pt-br "J3.x:Adding custom fields/Calendar Field/pt-br").
- **Nome**: O nome será usado para identificar o campo. Deixe em branco
  (vazio) e o Joomla! preencherá um valor padrão a partir do título.
- **Rótular**: Usa um texto descritivo do campo para o rótulo do campo.
  Este texto não é traduzível. Se você não inserir nenhum texto para um
  rótulo, o texto do título também será usado como texto do rótulo.
- **Descrição**: A descrição do campo. Um texto que será mostrado como
  uma dica para ferramenta quando o usuário mover o mouse sobre a caixa
  para texto enquanto o utiliza na administração (backend) ao criar um
  artigo, contato ou componente de terceiros que suporte campos. Este
  texto não é traduzível. Você não vê esta descrição no site (frontend).
- **Necessário**: Este é um campo obrigatório? Neste caso, o campo deve
  ser preenchido antes de enviar um artigo, contato ou componente de
  terceiros que suporte campos.

**Painel direito**

- **Estado**: O estado da publicação deste campo.
  - Publicado: O campo fica visível durante a edição de um artigo ou
    contato. E é visível no site (frontend).
  - Despublicado: O campo não ficará visível para os usuários durante a
    edição de um artigo ou contato.
  - Arquivado: O campo não serã mostrado mais na edição em um artigo ou
    contato. Você pode abri-lo em "<a
    href="https://docs.joomla.org/index.php?title=Help4.x:Fields/pt-br&amp;action=edit&amp;redlink=1"
    class="new"
    title="Help4.x:Fields/pt-br (page does not exist)">Campos</a>"
    quando definir o filtro como arquivado.
  - Lixeira: O campo é excluído, mas ainda está no banco de dados. Ele
    pode ser excluído permanentemente do banco de dados em "<a
    href="https://docs.joomla.org/index.php?title=Help4.x:Fields/pt-br&amp;action=edit&amp;redlink=1"
    class="new"
    title="Help4.x:Fields/pt-br (page does not exist)">Campos</a>" com a
    função "Esvaziar lixeira". [Aprender
    mais](https://docs.joomla.org/J4.x:Deleting_an_Article/pt-br "J4.x:Deleting an Article/pt-br").
- **Grupo do campo**: Você pode atribuir um campo a um ou mais grupos
  para campos.
- **Categoria**: Você pode atribuir um campo a uma ou mais categorias.
  Note que o padrão "Todas" não inclui os artigos "descategorizados".
- **Acesso**: Selecione o nível do acesso para visualização para este
  campo. Os níveis do acesso dependem do que foi configurado em
  [Usuários: Níveis dos
  acessos](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/pt-br "Help4.x:Users: Viewing Access Levels/pt-br").
- **Linguagem**: Selecione a linguagem para este campo. Se você não
  estiver usando o <a
  href="https://docs.joomla.org/index.php?title=Help4.x:Extensions:_Languages/pt-br&amp;action=edit&amp;redlink=1"
  class="new"
  title="Help4.x:Extensions: Languages/pt-br (page does not exist)">recurso
  multilíngue</a> do Joomla!, mantenha o padrão "Todas".
- **Nota**: Um campo opcional para fazer suas anotações pessoais para o
  campo.

### Opções

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Fields-Edit-options-subscreen-pt-br.png"
class="new"
title="File:Help-4x-Fields-Edit-options-subscreen-pt-br.png">600px</a>

**Opções do formulário**

- **Espaço reservado**: Um texto para o espaço reservado que aparecerá
  dentro do campo como uma dica para a entrada. O espaço reservado está
  ativo na administração (backend) ao criar um artigo, contato ou
  componente de terceiros que oferece suporte a campos. Você não vê isso
  no site (frontend).
- **Classe do campo**: Os atributos da classe do campo quando o campo é
  renderizado. Se forem necessárias classes diferentes, liste-as com
  espaços.
- **Classe do rótulo (formulário)**: Classe CSS para aplicar ao rótulo
  do campo quando estiver no modo de edição (inserindo entrada em um
  campo).
- **Editável em**: Em qual parte do site o campo deve ser mostrado. Na
  administração (backend), no site (frontend) ou em ambos?
- **Showon Attribute**. Conditionally show or hide the field depending
  on the value of other fields. The syntax to use here, for example:
  `list-of-items:value1[OR]list-of-items:value2`
  - list-of-items – It is the *name* of an already created field on
    which this field will depends to be show.
  - value1 – Is the value need have the field on which it depends to be
    show.
  - \[OR\] – To create a choice among multiple fields. In the example,
    this field will show when *list-of-items* field have the value:
    *value1* OR *value2*
  - \[AND\] – To combine multiple fields. This field will show only when
    *list-of-items* field have the value: *value1* AND *value2*
  - You can also use value 'does not equal' as in
    **list-of-items!:value1**. The syntax will show this field only when
    *list-of-items* is not equal to *value1*
  - To show this field when *list-of-items* field has been selected and
    have not a empty value, use the syntax *list-of-items!:* (without a
    value specified).

**Note:** Subform fields handle different the identifier *name* of
*list-of-items*. If you create a Subform custom field and you add this
conditional field you are creating to there, you need use *field\[ID\]*
instead of *list-of-items*, where ID is the id of the field
*list-of-items*. Therefore, the showon attribute for this conditional
field you are creating need be: `field36:value1[OR]field36:value2` where
36 is the ID of the field 'List of items'.

**Opções da exibição**

- **Classe da exibição**: A classe do contêiner do campo na saída.
- **Classe do valor**: A classe do valor do campo na saída.
- **Rotular**: Mostra o rótulo quando o campo for renderizado.
- **Classe do rótulo (saída)**: Classe CSS a ser aplicada ao rótulo do
  campo quando ele é mostrado (mostrando a saída de um campo).
- **Exibição automática**: O Joomla! oferece alguns eventos de conteúdo
  que são acionados durante o processo de criação do conteúdo. Este é o
  local para definir como os campos devem ser integrados ao conteúdo.
  Você pode escolher
  - Após o título
  - Antes de mostrar o conteúdo
  - Após mostrar o conteúdo
  - Não mostrar automaticamente
- **Prefixo**: Texto fixo a ser mostrado antes de um campo, por exemplo
  £.
- **Sufixo**: Texto fixo a ser mostrado após um campo, por exemplo EUR.
- **Disposição**: Se houver uma disposição personalizada, ela será
  selecionada aqui.
- **Mostrar quando somente leitura**: Se o campo for somente leitura
  (talvez o usuário não tenha o nível do acesso), o campo deve ser
  mostrado ou ocultado.

### Publicação

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Fields-Edit-publishing-subscreen-pt-br.png"
class="new"
title="File:Help-4x-Fields-Edit-publishing-subscreen-pt-br.png">600px</a>

- **Data da criação**: A hora atual em que o campo foi criado. Digite
  uma data e hora diferentes ou acione o (clique no) ícone do calendário
  para encontrar a data desejada.
- **Criado por**: Nome do usuário que criou este campo. Isso será o
  padrão para o usuário conectado no momento. Se você quiser alterar
  isso para um usuário diferente, acione o (clique no) botão "Selecionar
  usuário".
- **Data da modificação**: Data da última modificação.
- **Modificado por**: Nome do usuário que executou a última modificação.
- **ID**: Um número para identificação exclusivo para este campo, você
  não pode alterar esse número. Ao criar um novo campo, este campo
  mostra "0" até que você salve a nova entrada.

### Permissões

É aqui que você pode inserir permissões para este campo. [Aprender
mais](https://docs.joomla.org/J3.x:Access_Control_List_Tutorial/pt-br#hierarchylevels "J3.x:Access Control List Tutorial/pt-br").

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Fields-Edit-permissions-subscreen-pt-br.png"
class="new"
title="File:Help-4x-Fields-Edit-permissions-subscreen-pt-br.png">600px</a>

Para alterar as permissões para este campo, faça o seguinte:

1.  Selecione o **Grupo** acionando (clicando em) seu título localizado
    à esquerda.
2.  Encontre a **ação** desejada.
    - **Excluir**: Os usuários podem excluir este campo.
    - **Editar**: Os usuários podem editar este campo.
    - **Editar estado**: O usuário pode alterar o estado da publicação e
      as informações relacionadas para este campo.
    - **Editar valor do campo personalizado**: Os usuários podem editar
      o valor do campo.
3.  Selecione a permissão desejada para a ação que deseja alterar.
    - **Herdado**: Herdado, para os usuários neste grupo, das
      [configurações
      globais](https://docs.joomla.org/Help4.x:Site_Global_Configuration/pt-br#permissions "Help4.x:Site Global Configuration/pt-br"),
      grupo ou categoria parental.
    - **Permitido**: Permitido para os usuários neste grupo.Nota: Se
      esta ação for negada em um dos níveis mais altos, a permissão
      permitida aqui não terá efeito. Uma configuração negada não pode
      ser substituída.
    - **Negado**: Negado para os usuários neste grupo.
4.  Acione (clique em) **Salvar** na **barra das ferramentas** na parte
    superior. Quando a tela for atualizada, a coluna "Configuração
    calculada" mostrará a permissão efetiva para este grupo e ação.

## Barra das ferramentas

No topo da página você verá a barra das ferramentas mostrada na [captura
da tela](#screenshot) acima.

- **Salvar**: Salva o campo e permanece na tela atual.
- **Salvar e fechar**: Salva o campo e fecha a tela atual.
  - **Salvar e novo**: Salva o campo e mantém a tela de edição aberta e
    pronta para criar outro campo.
  - **Salvar como cópia**: Salva suas alterações em uma cópia do campo
    atual. Não afeta o campo atual.
- **Fechar**: Fecha a tela atual e retorna à tela anterior sem salvar
  nenhuma modificação que você possa ter feito.
- **Ajuda**: Abre esta tela de ajuda.

## Dicas rápidas

Se você quer saber como usar os campos: [Gerenciando campos
personalizados](https://docs.joomla.org/J3.x:Adding_custom_fields/pt-br "J3.x:Adding custom fields/pt-br").

## Informações relacionadas

- Este
  [portal](https://docs.joomla.org/Portal:Joomla_4/pt-br "Portal:Joomla 4/pt-br")
  reúne informações relacionadas especificamente ao Joomla! 4.

|                                                                                                               |                                                                                                                                                                            |
|---------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Telas de ajuda relacionadas                                                                                   | Descrição                                                                                                                                                                  |
| <a                                                                                                            
 href="https://docs.joomla.org/index.php?title=Help4.x:Fields/pt-br&amp;action=edit&amp;redlink=1"              
 class="new"                                                                                                    
 title="Help4.x:Fields/pt-br (page does not exist)">Campos</a>                                                  | Os campos são usados para mostrar atributos adicionais dos artigos, contatos e usuários. Os dados são inseridos na administração (backend) e mostrados no site (frontend). |
| <span class="mw-selflink selflink">Campos: Editar</span>                                                      | É aqui que você pode adicionar e editar os campos em artigos, contatos e usuários.                                                                                         |
| <a                                                                                                            
 href="https://docs.joomla.org/index.php?title=Help4.x:Field_Groups/pt-br&amp;action=edit&amp;redlink=1"        
 class="new"                                                                                                    
 title="Help4.x:Field Groups/pt-br (page does not exist)">Grupos de                                             
 campos</a>                                                                                                     | A tela dos grupos de campos é usada para listar, adicionar e editar grupos de campos.                                                                                      |
| <a                                                                                                            
 href="https://docs.joomla.org/index.php?title=Help4.x:Field_Groups:_Edit/pt-br&amp;action=edit&amp;redlink=1"  
 class="new"                                                                                                    
 title="Help4.x:Field Groups: Edit/pt-br (page does not exist)">Grupos de                                       
 campos: Editar</a>                                                                                             | Grupos de campos são usados para coletar campos relacionados em uma aba (guia) nomeada em um formulário de entrada de dados.                                               |
