<!-- Filename: Help4.x:News_Feeds / Display title: Ajuda4.x:Feeds para notícias -->

## Descrição

A tela do gerenciador dos feeds para notícias permite que você adicione
feeds para notícias de outros sites ao seu site Joomla!. Você pode
adicionar links a esses feeds para usuários criando disposições
(layouts) para feeds para notícias no
<a href="https://docs.joomla.org/Help4.x:News_Feeds:_New_or_Edit/pt-br"
class="mw-redirect"
title="Help4.x:News Feeds: New or Edit/pt-br">Gerenciador dos itens dos
menus - Novo/editar</a>.

## Como acessar

- Selecione **Componentes **→** Feeds para notícias **→** Feeds** no
  menu administrativo.
- Ou selecione o link **Feeds** no [Gerenciador dos feeds para
  notícias -
  Categorias](https://docs.joomla.org/Help4.x:News_Feeds:_Categories/pt-br "Help4.x:News Feeds: Categories/pt-br").

## Captura da tela

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Components-Newsfeeds-Feeds-screen-pt-br.png"
class="new"
title="File:Help-4x-Components-Newsfeeds-Feeds-screen-pt-br.png">800px</a>

## Cabeçalhos das colunas

Acione o cabeçalho da coluna para classificar a lista pelo valor da
coluna em questão.

- **Caixa de seleção**: Marque esta caixa para selecionar um ou mais
  itens. Para selecionar todos os itens, marque a caixa no cabeçalho da
  coluna. Depois que uma ou mais caixas forem marcadas, clique em um dos
  botões da barra de ferramentas para executar uma ação no item ou nos
  itens selecionados. Muitas ações da barra de ferramentas, como
  "Publicar" e "Cancelar publicação", podem funcionar com vários itens.
  Outras, como "Editar", funcionam apenas em um item de cada vez. Se
  vários itens estiverem marcados e você pressionar "Editar", apenas o
  primeiro item será aberto para edição.
- **Ordenação**: Você pode alterar a ordem de um item em uma lista da
  seguinte forma:
  - Se a lista das opções dos filtros incluir um filtro de posição,
    selecione a posição desejada. Isso limitará a lista aos itens
    atribuídos a essa posição.
  - Selecione o ícone de "Ordenação" <img
    src="https://docs.joomla.org/images/e/ee/Help30-Ordering-colheader-icon.png"
    decoding="async" data-file-width="12" data-file-height="23" width="12"
    height="23" alt="Help30-Ordering-colheader-icon.png" /> no cabeçalho
    da tabela para torná-lo o item de ordenação ativo. Os ícones de
    ordenação em cada linha mudarão de cinza claro para cinza escuro e o
    ponteiro mudará para uma seta de arrastar ao passar o mouse.
  - Selecione um dos ícones de "Ordenação" <img
    src="https://docs.joomla.org/images/8/87/Help30-Ordering-colheader-grab-bar-icon.png"
    decoding="async" data-file-width="10" data-file-height="21" width="10"
    height="21" alt="Help30-Ordering-colheader-grab-bar-icon.png" /> e
    arraste-o para cima ou para baixo para alterar a posição dessa linha
    na lista. Os itens serão exibidos na nova ordem dentro da posição.
- **Estado**: O estado de publicação do item.
- **Título**: O nome ou o título do feed. Faça-o o mais descritivo
  possível.
- **Acesso**: O [nível de acesso de
  visualização](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/pt-br "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/pt-br")
  para este item.
- **Artigos (quantidade)**: O número de artigos incluídos no feed.
- **Tempo do cache**: O número em segundos para armazenar o item em
  cache localmente. Ele pode ser deixado com segurança no padrão.
- **Associação**: Mostra a qual item dos menus este item está associado.
- **Linguagem**: Linguagem do item.
- **ID**: Este é um número de identificação exclusivo atribuído
  automaticamente pelo Joomla para este item. Ele é usado para
  identificar o item internamente e você não pode alterar esse número.
  Ao criar um novo item, este campo exibe "0" até que você salve a nova
  entrada, momento em que um novo ID é atribuído a ele.

## Filtros da lista

**Barra de pesquisa**: Perto do topo da página, você verá a barra de
pesquisa mostrada na [captura de tela](#screenshot) acima.

- **Pesquisar por texto**: Insira parte do termo de pesquisa e clique no
  ícone "Pesquisar". *Passe o mouse* para ver uma *dica* indicando quais
  campos serão pesquisados.Para "Pesquisar por ID" digite "id:x", onde
  "x" é o número de ID (por exemplo, "id:19").
- **Opções de filtros**: Clique para exibir os filtros adicionais.
- **Limpar**: Clique para limpar o campo "Filtros" e restaurar a lista
  ao seu estado não filtrado.
- **Ordenação**: Mostra o campo de ordenação da lista atual. 2 maneiras
  de alterar a ordem:
  - Selecionar na lista suspensa. A ordenação pode ser em ordem
    crescente ou decrescente.
  - Clicar em um título de coluna. O cabeçalho de coluna alterna entre
    ordem crescente e decrescente.
- **Número a ser exibido**: Mostra o número de itens em uma lista.
  Selecione na lista suspensa para alterar o número exibido.O padrão
  para um site é '20', mas isso pode ser alterado nas [Configurações
  Globais](https://docs.joomla.org/Help4.x:Site_Global_Configuration/pt-br#defaultlistlimit "Help4.x:Site Global Configuration/pt-br").

**Opções do filtro**

- **Selecionar estado**: Use a caixa de lista suspensa para selecionar o
  estado de publicação: "Publicados, Não publicados, Lixeira ou Todos".
  Para artigos, você também pode selecionar "Arquivados".
  **Importante:** Com a configuração padrão "-Selecionar estado-, a tela
  mostra apenas os itens "Publicados" e "Não publicados". Se você tiver
  o filtro definido para "-Selecionar estado-" e alterar os itens para
  "Lixeira", os itens "Lixeira" desaparecerão da tela. No entanto, eles
  não foram excluídos permanentemente. Para fazer isso você precisa:

1.  Alterar o filtro para "Lixeira". O ícone "Excluir" agora será
    exibido na barra de ferramentas.
2.  Selecionar os itens que você deseja excluir permanentemente.
3.  Clicar no ícone "Excluir".

Você pode ver todos os itens, independentemente de seu estado de
publicação, selecionando "Todos" para este filtro. Você também pode
republicar itens da "Lixeira" selecionando-os e clicando no ícone
"Publicar" na barra de ferramentas.

- **Selecionar categoria**: Selecione a partir da lista das categorias
  disponíveis.
- **Selecionar acesso**. Seleciona na lista de níveis de acesso de
  visualização disponíveis.
- 

**Selecionar linguagem**: Seleciona na lista de linguagens disponíveis.

- **Selecionar tag**: Seleciona a partir da lista de tags disponíveis.
- **Selecionar os níveis máximos**: Seleciona a partir da lista de
  níveis disponíveis.

## Barra das ferramentas

No topo da página você verá a barra de ferramentas mostrada na [captura
de tela](#Captura_de_tela) acima. As funções são:

- **Novo**: Abre a tela de edição para criar um novo feed para notícias.
- **Ações**: Revela uma lista de ações para os itens selecionados.
  Marque uma ou mais caixas de seleção de itens para ativar a lista.
- **Publicar**: Disponibiliza os feeds para notícias selecionados para
  os visitantes do seu site.
- **Cancelar publicação**: Torna os feeds para notícias selecionados
  indisponíveis para os visitantes do seu site.
- **Arquivo**: Altera o estado dos feeds para notícias selecionados para
  indicar que eles estão arquivados. Os feeds para notícias arquivados
  podem ser movidos de volta para o estado publicado ou não publicado
  selecionando "Arquivado" no filtro "Selecionar estado" e alterando o
  estado dos feeds para notícias.
- **Check-in**: Faz o check-in dos feeds para notícias selecionados.
  Funciona com um ou vários feeds para notícias selecionados.
- **Lixeira**: Altera o estado dos feeds para notícias selecionados para
  indicar que eles estão na lixeira.feeds para notícias na lixeira ainda
  podem ser recuperados selecionando "Lixeira" no filtro "Selecionar
  estado" e alterando o estado dos artigos para "Publicado" ou "Não
  publicado" conforme a preferência.Para excluir permanentemente feeds
  para notícias da lixeira, selecione "Lixeira" no filtro "Selecionar
  estado", selecione os feeds para notícias a serem excluídos
  permanentemente e clique no ícone "Esvaziar lixeira" na barra de
  ferramentas.
- **Lote**: Processa em lote os feeds para notícias selecionados.
  Funciona com um ou vários itens selecionados.
- **Opções**: Abre a janela de opções onde configurações, como os
  parâmetros padrões, podem ser editadas.
- **Ajuda**: Abre a tela de ajuda.

## Dicas rápidas

- Você precisa adicionar pelo menos uma categoria para os feeds para
  notícias *antes* de adicionar o primeiro feed. As categorias são
  adicionadas acionando "Feeds para notícias" e depois em "Categorias"
  no menu "Componentes".

## Informações relacionadas

- Para definir opções dos feeds para notícias: [Opções dos feeds para
  notícias](https://docs.joomla.org/Help4.x:News_Feed:_Options/pt-br "Help4.x:News Feed: Options/pt-br")
- Para criar ou editar feeds para notícias:
  <a href="https://docs.joomla.org/Help4.x:News_Feeds:_New_or_Edit/pt-br"
  class="mw-redirect"
  title="Help4.x:News Feeds: New or Edit/pt-br">Gerenciador dos feeds para
  notícias - Novo/Editar</a>
- Para trabalhar com as categorias dos feed para notícias: [Gerenciador
  das categorias (feeds para
  notícias)](https://docs.joomla.org/Help4.x:News_Feeds:_Categories/pt-br "Help4.x:News Feeds: Categories/pt-br")
