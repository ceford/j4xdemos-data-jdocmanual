<!-- Filename: Help4.x:Users:_New_or_Edit_Group / Display title: Usuários: Novo/editar grupo -->

## Descrição

O Joomla! é instalado com um conjunto de grupos de usuários adequado
para o gerenciamento de sites padrões. Os grupos padrões não devem ser
editados! Novos grupos podem ser criados para fins especiais. Por
exemplo, você pode desejar criar um grupo com acesso permitido a apenas
um componente.

## Como acessar

- Selecione **Usuários **→** Grupos** no menu da administração. Então...
  - Selecione o botão **Novo** na barra de ferramentas ou...
  - Selecione um link da coluna **título do grupo** para editar um grupo
    existente.

## Captura de tela

<img
src="https://docs.joomla.org/images/3/33/Help-4x-users-user-manager-add-new-user-group-en.png"
decoding="async" data-file-width="600" data-file-height="281"
width="800" height="375"
alt="Help-4x-users-user-manager-add-new-user-group-en.png" />

## Detalhes do grupo de usuários

- **Título do grupo**: Insira um título para o grupo.
- **Pai do grupo**:
  (*Público*/*Convidado*/*Gerente*/*Administrador*/*Registrado*/*Autor*/*Editor*
  /...). Escolha um pai para este grupo.

Os grupos de usuários controlam quais ações um usuário pode realizar no
site. As ações incluem coisas como criar um novo artigo, alterar as
opções de um componente ou iniciar uma sessão. O administrador do site
atribui permissões para várias ações a cada grupo. As permissões para
ações podem ser atribuídas em diferentes níveis na hierarquia de
componentes (configurações globais, opções de componentes, categorias e
artigos). Se um usuário não tiver permissão para uma determinada ação,
ele não poderá realizar essa ação.

Os grupos de usuários também controlam quais objetos um usuário pode
visualizar no site. Os objetos incluem categorias, artigos, módulos,
itens de menu e outros. Ao criar um nível de acesso, um ou mais grupos
de usuários são atribuídos a ele. Então, quando você cria um objeto
(como um item de menu ou módulo), o objeto recebe um nível de acesso. Se
um usuário for membro de um grupo atribuído a um nível de acesso, esse
usuário poderá visualizar qualquer objeto atribuído a esse nível de
acesso. Caso contrário, esse usuário não poderá visualizar esse objeto.

Os grupos de usuários podem ser organizados em uma hierarquia. Nesse
caso, todos os grupos filhos herdam as permissões de ações e os níveis
de acessos de um grupo pai. Se usado com sabedoria, esse recurso pode
economizar muito tempo relacionado à configuração de seu sistema de
segurança, pois significa que você não precisa inserir informações
duplicadas relacionadas às configurações.

## Barra de ferramentas

Na parte superior, você verá a barra de ferramentas mostrada na captura
de tela acima. As funções são:

- **Salvar**: Salva o item e permanece na tela atual.

<!-- -->

- **Salvar fechar**: Salva o item e fecha a tela atual.

<!-- -->

- **Salvar & novo**: Salva o item e mantém a tela de edição aberta e
  pronta para criar outro item.

<!-- -->

- **Cancelar**: Fecha a tela atual e retorna à tela anterior sem salvar
  nenhuma modificação que você tenha feito.

<!-- -->

- **Ajuda**: Abre a tela de ajuda.

## Dicas rápidas

- Se um novo grupo tiver permissões semelhantes a um grupo existente,
  você poderá economizar trabalho tornando o novo grupo filho do grupo
  existente. Dessa forma, você só precisa alterar as permissões que são
  diferentes para o novo grupo.

## Informações relacionadas

- [Usuários:
  Grupos](https://docs.joomla.org/Help4.x:Users:_Groups/pt-br "Help4.x:Users: Groups/pt-br")
- [Tutorial relacionado às listas de controle de acessos (ACL) para o
  Joomla!
  3.x](https://docs.joomla.org/J3.x:Access_Control_List_Tutorial/pt-br "J3.x:Access Control List Tutorial/pt-br")
