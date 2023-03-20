<!-- Filename: Help4.x:Banners:_New_or_Edit_Category / Display title: Ajuda4.x:Banners: Nova categoria ou editar categoria -->

## Descrição

É aqui que você pode adicionar uma nova categoria para banners ou editar
uma já existente. Observe que você precisa criar pelo menos uma
categoria para banners antes de criar um banner. Além disso, as
categorias para banners são separadas dos outros tipos de categorias,
como artigos, contatos e feeds de notícias.

## Como acessar

Navegue até o [gerenciador das categorias dos
banners](https://docs.joomla.org/Help4.x:Banners:_Categories/pt-br "Help4.x:Banners: Categories/pt-br"),
**Componentes **→** Banners **→** Categorias**

- **Nova**: Clique no ícone **Nova** na barra das ferramentas.
- **Editar**: Para editar uma categoria para banners existente, acione o
  (clique no) **nome da categoria** na tabela das categorias.

## Captura da tela

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Components-Banners-Categories-Edit-screen-pt-br.png"
class="new"
title="File:Help-4x-Components-Banners-Categories-Edit-screen-pt-br.png">800px</a>

## Campos do formulário

- **Título**: O título para este item. Isso pode ou não ser mostrado na
  página, dependendo dos valores do parâmetro que você escolher.
- **Alias**: O nome interno do item. Normalmente, você pode deixar em
  branco e o Joomla preencherá um valor padrão de título em letras
  minúsculas e com traços em vez de espaços. [Saiba
  mais.](https://docs.joomla.org/Alias/pt-br "Special:MyLanguage/Alias/pt-br")

### Aba (guia) Detalhes

**Painel esquerdo**

- **Descrição**: A descrição do item. As descrições de categorias,
  subcategorias e links da web podem ser exibidas nas páginas web,
  dependendo das configurações dos parâmetros. Essas descrições são
  inseridas usando o mesmo editor usado para artigos.

**Painel direito**

- **Superior (pai)**: O item (categoria, item dos menus e assim por
  diante) que é o superior (pai) do item que está sendo editado.
- **Estado**: O estado da publicação deste item.
  - *Publicado*: O item é visível do site (frontend).
  - *Despublicado*: O item não será visível para os visitantes do site
    (no frontend). Pode ser visível para usuários conectados que tenham
    permissão para editae o estado do item.
  - *Arquivado*: O item não será mais mostrado no blog ou na lista dos
    itens dos menus.
  - *Lixeira*: O item é excluído do site, mas ainda está no banco de
    dados. Ele pode ser excluído permanentemente do banco de dados com a
    função "Esvaziar lixeira" na barra das ferramentas (veja também
    "[Excluindo um
    artigo](https://docs.joomla.org/Deleting_an_Article/pt-br "Special:MyLanguage/Deleting an Article/pt-br")").
- **Acesso**: Selecione o nível do acesso para visualização para este
  item na caixa da listagem. Os níveis dos acessos mostrados dependerão
  do que foi configurado para este site em [Usuários → Níveis dos
  acessos](https://docs.joomla.org/Help40:Users:_Viewing_Access_Levels/pt-br "Special:MyLanguage/Help40:Users: Viewing Access Levels/pt-br").
  Observe que os níveis dos acessos são separados das permissões das
  ACLs. Os níveis dos acessos controlam o que um usuário pode ver. As
  permissões das ACLs controlam quais ações um usuário pode executar.
- **Linguagem**: Selecione a linguagem para este item. Se você não
  estiver usando o recurso multilíngue do Joomla!, mantenha o padrão
  "Todas".
- **Tags**: Atribua tags a itens do conteúdo. Você pode selecionar uma
  tag predefinida da lista ou inserir uma nova tag digitando o nome no
  campo e pressionando "enter".
- **Nota**: Isso normalmente é para uso da administração do site (por
  exemplo, para documentar informações sobre o item) e não aparece no
  frontend do mesmo.
- **Nota da versão**: Campo opcional para identificar esta versão do
  item na janela do [histórico das
  versões](https://docs.joomla.org/Help40:Components_Version_History/pt-br "Special:MyLanguage/Help40:Components Version History/pt-br")
  do item.

## Aba (guia) Opções

- **Disposição**: Selecione uma disposição na lista.
- **Imagem**: Opcional: Selecione uma imagem para mostrar ao lado desta
  categoria.
- **Texto alternativo**: Texto alternativo para o ícone - frequentemente
  usado por leitores de tela.

## Aba (guia) Publicação

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Banners-Categories-Edit-screen-publish-options-tab-pt-br.png"
class="new"
title="File:Help-4x-Banners-Categories-Edit-screen-publish-options-tab-pt-br.png">600px</a>

### Publicação

Os campos acinzentados são apenas informativos e não podem ser editados.

- **Data de criação**: Data em que o item (artigo, categoria, weblink,
  etc.) foi criado.
- **Criado por**: Opcional, escolha em uma janela pop-up de usuários.
  Selecione o úsuário clicando no nome de usuário. Padrões para o
  usuário criando uma nova categoria se deixado em branco.
- **Data de modificação**: *(Somente informativo)* Data da última
  modificação.
- **Modificado por**: *(Somente informativo)* Nome de usuário que
  realizou a última modificação.
- **Acessos**: Número de acessos em uma visualização de categoria.
- **ID**: O número de identificação exclusivo atribuído automaticamente
  a este item pelo Joomla!. Este número não pode ser alterado.
- **Meta descrição**: Um parágrafo opcional a ser usado como descrição
  da página na saída da HTML. Isso geralmente será exibido nos
  resultados dos mecanismos de pesquisas. Se inserido, isso cria um
  elemento meta de HTML com um atributo de nome de "descrição" e um
  atributo de conteúdo igual ao texto inserido.
- **Palavras-chave meta**: Entrada opcional para palavras-chave. Devem
  ser digitadas separadas por vírgulas (por exemplo, "gatos, cachorros,
  animais de estimação") e podem ser digitadas em letras maiúsculas ou
  minúsculas. (Por exemplo, "GATOS" corresponderá a "gatos" ou "Gatos").
  As palavras-chave podem ser usadas de várias maneiras:
  - Para ajudar os mecanismos de pesquisas e outros sistemas a
    classificar o conteúdo do artigo.
  - Em combinação com tags de banner, para exibir banners específicos
    com base no conteúdo do artigo. Por exemplo, digamos que você tenha
    um banner com um anúncio para produtos para cães e outro para
    produtos para gatos. Você pode exibir seu banner de cachorro quando
    um usuário estiver visualizando um artigo relacionado a cães e seu
    banner de gato exibir um artigo relacionado a gatos. Para fazer
    isso, você faria:
    - Adicionar as palavras-chave "cachorro" e "gato" aos artigos
      apropriados.
    - Adicionar as tags "cachorro" e "gato" aos banners apropriados na
      tela ["Novo/Editar" do gerenciador de
      banners](https://docs.joomla.org/Help4.x:Banners:_Edit/pt-br "Help4.x:Banners: Edit/pt-br").
    - Definir o parâmetro "Pesquisar por tags" do módulo Banner como
      "Sim" na tela [Editar do módulo
      Banner](https://docs.joomla.org/Help4.x:Site_Modules:_Banners/pt-br "Help4.x:Site Modules: Banners/pt-br").
  - Apenas para artigos, em combinação com o módulo [Artigos
    relacionados](https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Related/pt-br "Help4.x:Site Modules: Articles - Related/pt-br"),
    para exibir artigos que compartilham pelo menos uma palavra-chave em
    comum. Por exemplo, se o artigo atual exibido tiver as
    palavras-chave "gatos, cachorros, macacos", quaisquer outros artigos
    com pelo menos uma dessas palavras-chave serão exibidos no módulo de
    artigos relacionados.
- **Autor**: Entrada opcional para um nome de autor nos metadados. Se
  inserido, isso cria um meta elemento da HTML com o atributo de nome do
  "autor" e o atributo de conteúdo conforme inserido aqui.
- **Robôs**: As instruções para "robôs" da web que navegam até esta
  página.
  - *Usar global*: Usa o valor definido em Componente→Opções para este
    componente.
  - *Indexar, seguir*: Indexa esta página e segue os links nesta página.
  - *Sem indexar, siga*: Não indexa esta página, mas segue os links na
    página. Por exemplo, você pode fazer isso para uma página de mapa do
    site na qual deseja que os links sejam indexados, mas não deseja que
    essa página seja exibida nos mecanismos de pesquisas.
  - *Indexar, não seguir*: Indexa esta página, mas não segue nenhum link
    na página. Por exemplo, você pode querer fazer isso para um
    calendário de eventos, onde deseja que a página seja exibida nos
    mecanismos de pesquisas, mas não deseja indexar cada evento.
  - *Não indexar, não seguir*: Não indexa esta página ou segue quaisquer
    links na página.

## Aba (guia) Permissões

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Banners-Categories-Edit-screen-permissions-tab-pt-br.png"
class="new"
title="File:Help-4x-Banners-Categories-Edit-screen-permissions-tab-pt-br.png">600px</a>

Para alterar as permissões para esta extensão, faça o seguinte.

- Selecione o **grupo** clicando em seu título localizado à esquerda.
- Encontre a **ação** desejada. As ações possíveis são:
  - **Configurar ACL e opções**: Os usuários podem editar as opções e as
    permissões desta extensão.
  - **Configurar apenas opções**: Os usuários podem editar as opções,
    exceto as permissões desta extensão.
  - **Interface de administração de acesso**: Os usuários podem acessar
    a interface de administração do usuário desta extensão.
  - **Criar**: Os usuários podem criar o conteúdo desta extensão.
  - **Excluir**: Os usuários podem excluir o conteúdo desta extensão.
  - **Editar**: Os usuários podem editar o conteúdo desta extensão.
  - **Editar estado**: O usuário pode alterar o estado de publicação e
    as informações relacionadas ao conteúdo desta extensão.
  - **Editar próprio**: Os usuários podem editar o próprio conteúdo
    criado desta extensão.

- Selecione a permissão desejada para a ação que deseja alterar. As
  configurações possíveis são:
  - ***Herdado***: Herdado das permissões das configurações globais
    desta extensão.
  - ***Permitido***: Permitido para usuários neste grupo. Observe que,
    se esta ação for negada em um dos níveis mais altos, a permissão
    permitida aqui não terá efeito. Uma configuração negada não pode ser
    substituída.
  - ***Negado***: Negado para usuários neste grupo.

- Clique em **salvar** na **barra de ferramentas** na parte superior.
  Quando a tela for atualizada, a coluna de configuração calculada
  mostrará a permissão efetiva para este(a) grupo e ação.

## Barra das ferramentas

No topo da página você verá a barra de ferramentas mostrada na [captura
de tela](#Captura_de_tela) acima. As funções são:

- **Salvar**: Salva o item e permanece na tela atual.
- **Salvar fechar**: Salva o item e fecha a tela atual.
- **Salvar & novo**: Salva o item e mantém a tela de edição aberta e
  pronta para criar outro item.
- **Salvar como cópia**: Salva suas alterações em uma cópia do item
  atual. Não afeta o item atual. Este ícone da barra de ferramentas não
  é exibido se você estiver criando um novo item.
- **Cancelar**: Fecha a tela atual e retorna à tela anterior sem salvar
  nenhuma modificação que você tenha feito. Ou
- **Fechar**: Fecha a tela atual e retorna à tela anterior sem salvar
  nenhuma modificação que tenha feito. Este ícone da barra de
  ferramentas não é exibido se você estiver criando um novo item.
- **Versões**: Abre a janela do histórico das versões do item para
  mostrar as versões anteriores deste item. Isso permite que você
  visualize versões mais antigas deste item e, se desejar, restaure a
  partir de uma versão mais antiga. Consulte [histórico das
  versões](https://docs.joomla.org/Help40:Components_Version_History/pt-br "Special:MyLanguage/Help40:Components Version History/pt-br")
  para mais informações.
- **Associações**: Com uma linguagem específica definida para um item,
  permite a edição lado a lado em outra linguagem. Este ícone na barra
  das ferramentas é mostrado apenas em [sites
  multilíngues](https://docs.joomla.org/Help4.x:Multilingual_Associations/pt-br "Special:MyLanguage/Help4.x:Multilingual Associations/pt-br").
- **Ajuda**: Abre a tela de ajuda.

## Informações relacionadas

- Para criar ou editar banners: [Gerenciador das categorias dos
  banners -
  Nova/editar](https://docs.joomla.org/Help4.x:Banners:_Categories/pt-br "Help4.x:Banners: Categories/pt-br")
- Para trabalhar com clientes dos banners: [Gerenciador dos clientes dos
  banners](https://docs.joomla.org/Help4.x:Banners:_Clients/pt-br "Help4.x:Banners: Clients/pt-br")
- Para colocar banners nas páginas: [Gerenciador dos
  módulos](https://docs.joomla.org/Help4.x:Modules/pt-br "Help4.x:Modules/pt-br")
