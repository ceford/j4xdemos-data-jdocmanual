<!-- Filename: Help4.x:Banners:_Categories / Display title: Ajuda4.x:Banners: Categorias -->

## Descrição

Usado para visualizar uma lista contendo as categorias dos banners
existentes, editar categorias dos banners atuais e criar novas. Observe
que as categorias dos banners são separadas das outras categorias, como
artigos, contatos, feeds para notícias e links da web. Deve haver pelo
menos um cliente para banners e categoria para banners **antes** que um
banner possa ser criado.

## Como acessar

- Selecione **Componentes **→** Banners **→** Categorias**

## Captura da tela

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Components-Banners-Categories-screen-pt-br.png"
class="new"
title="File:Help-4x-Components-Banners-Categories-screen-pt-br.png">800px</a>

## Cabeçalhos das colunas

Clique no cabeçalho da coluna para classificar a lista pelo valor dessa
coluna.

- **Caixa de seleção**: Marque esta caixa para selecionar um ou mais
  itens. Para selecionar todos os itens, marque a caixa no cabeçalho da
  coluna. Depois que uma ou mais caixas forem marcadas, clique em um dos
  botões da barra de ferramentas para executar uma ação no item ou nos
  itens selecionados. Muitas ações da barra de ferramentas, como
  "Publicar" e "Cancelar publicação", podem funcionar com vários itens.
  Outras, como "Editar", funcionam apenas em um item de cada vez. Se
  vários itens estiverem marcados e você pressionar "Editar", apenas o
  primeiro item será aberto para edição.

<!-- -->

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

<!-- -->

- **Estado**: O estado de publicação do item.

<!-- -->

- **Título**: O nome do objeto. Para um item de menu, o título será
  exibido no menu. Para um artigo ou uma categoria, o título pode,
  opcionalmente, ser exibido na página web. Esta entrada é obrigatória.
  Você pode abrir o item para edição clicando no título.

<!-- -->

- **Acessos (visualizações)**: A quantidade de vezes que um item foi
  visualizado.

<!-- -->

- **Acesso**: O [nível de acesso de
  visualização](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/pt-br "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/pt-br")
  para este item.

<!-- -->

- **Linguagem**: Linguagem do item.

<!-- -->

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

### Opções do filtro

- ***- Selecionar estado -*** Mostra os itens publicados e
  despublicados. *Não* mostraos itens que estão na lixeira ou
  arquivados.
  - ***Lixeira***: Mostra apenas os itens que foram enviados para a
    lixeira. **Nota importante:** Para excluir permanentemente os itens:
    Altere o estado dos itens para "Lixeira". Altere o filtro do estado
    para "Lixeira". Neste ponto, os itens na lixeira serão mostrados e
    um ícone chamado "Esvaziar lixeira" será mostrado na barra das
    ferramentas. Selecione os itens desejados na lixeira e acione
    (clique em) "Esvaziar lixeira" na barra das ferramentas. Os itens
    serão excluídos permanentemente.
  - ***Despublicado***: Mostra apenas os itens despublicados.
  - ***Publicado***: Mostra apenas os itens publicados.
  - ***Arquivado***: Mostra apenas os itens que estão arquivados.
  - ***Todos***: Mostra todos os itens independentemente do estado da
    publicação.

<!-- -->

- ***- Selecionar acesso -*** Mostra itens com qualquer nível do acesso
  para visualização.
  - **: Mostra itens apenas com este nível do acesso para visualização.

<!-- -->

- ***- Selecionar linguagem -***: Mostra todos os itens
  independentemente da linguagem definida.
  - **: Mostra os itens apenas para esta linguagem.
  - ***Todas***: Mostra os itens nos quais a linguagem está definida
    como "Todas". Estes podem ser os itens que não são específicos para
    linguagens, como imagens.

<!-- -->

- ***- Selecionar tags -*** Mostra os itens com quaisquer (ou nenhuma)
  tag(s).
  - **: Mostra apenas os itens com esta tag.

<!-- -->

- ***- Selecionar o máximo de níveis -***: Mostra todos os itens,
  independentemente da quantidade de níveis atribuída.
  - ***1***: Mostra apenas os itens com este nível na hierarquia.
  - ***2-10***: Mostre apenas os itens cuja categoria esteja entre os
    2-10 níveis mais altos na hierarquia das categorias.

### Quantidade de itens a serem mostrados

**Controles da página**: Quando o número de itens for mais que uma
página, você verá uma barra de controle na página perto da parte
inferior da página mostrada na [captura de tela](#screenshot) acima. O
número da página atual que está sendo visualizada tem um fundo de cor
escura.

- **Início**: Clique para ir para a primeira página.
- **Anterior**: Clique para ir para a página anterior.
- **Números das páginas**: Clique para ir para a página desejada.
- **Próxima**: Clique para ir para a próxima página.
- **Fim**: Clique para ir para a última página.

## Barra das ferramentas

No topo da página você verá a barra de ferramentas mostrada na [captura
de tela](#Captura_de_tela) acima. As funções são:

- **Novo**: Abre a tela de edição para criar um novo item.

<!-- -->

- **Ações**: Revela uma lista de ações para os itens selecionados.
  Marque uma ou mais caixas de seleção de itens para ativar a lista.

<!-- -->

- **Reconstruir**: Reconstrói e atualiza a tabela relevante.
  Normalmente, você "não" precisa reconstruir esta tabela. Esta função é
  fornecida caso os dados na tabela passem a estar corrompidos.

<!-- -->

- **Opções**: Abre a janela de opções onde configurações, como os
  parâmetros padrões, podem ser editadas.

<!-- -->

- **Ajuda**: Abre a tela de ajuda.

## Processo em lote

O processo em lote permite uma alteração nas configurações de um grupo
de itens selecionados marcados com uma marca de seleção nas caixas de
seleção correspondentes. Para usar: acione o link encontrado abaixo da
tabela de itens que está sendo visualizada para ativar a área do campo
suspenso. Usar o botão "Lote", na barra das ferramentas, abrirá uma
janela pop-up como mostrado abaixo.

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-colheader-batch-process-categories-pt-br.png"
class="new"
title="File:Help-4x-colheader-batch-process-categories-pt-br.png">File:Help-4x-colheader-batch-process-categories-pt-br.png</a>

Você pode alterar um valor ou todos os três valores em uma única ação.

***Nota** - Se você copiar itens para uma nova categoria, as alterações
relacionadas à níveis de acessos e linguagens que você selecionou serão
aplicadas às cópias, não ao original.*

**Como processar em lote** um grupo de itens:

- Selecione um ou mais itens na lista marcando as caixas de seleção da
  categoria desejada.
- Clique no botão "Lote" na barra das ferramentas.
- Defina um ou mais dos seguintes valores:
  - Para alterar os **níveis dos acessos**, selecione o novo nível de
    acesso desejado na caixa da listagem para definir os níveis dos
    acessos.
  - Para alterar a **linguagem**, selecione a linguagem desejada na
    caixa da listagem para definir a linguagem.
  - \*\* Para alterar a **categoria**, selecione uma categoria. Para
    deixar a categoria inalterada, use o valor padrão "Selecionar".
    - Para copiar os itens para uma categoria diferente, selecione a
      categoria desejada na caixa da listagem dad categorias e marque a
      opção para copiar. Nesse caso, os itens originais permanecem
      inalterados, as cópias são atribuídas à nova categoria e, se
      selecionadas, ao novo nível para acesso e linguagem.
    - Para mover os itens para uma categoria diferente, selecione a
      categoria desejada na caixa da listagem das categorias e marque a
      opção para mover. Nesse caso, os itens originais serão movidos
      para uma nova categoria e, se selecionados, serão atribuídos o
      novo nível do acesso e linguagem.
- Quando todas as configurações forem inseridas, acione (clique em)
  "Processar" para realizar as alterações. Uma mensagem **"Processo em
  lote concluído com sucesso."** será mostrada.

Observe que nada acontecerá se você (a) não tiver nenhum item
selecionado ou (b) não tiver selecionado um nível para acesso, linguagem
ou categoria. Se você deseja limpar suas seleções inseridas, acione o
(clique no) botão "Cancelar". Isso retornará todos os controles
relacionados ao processamento em lote para seus valores padrões. Observe
que isso *não* desmarca as caixas selecionadas dos itens.

## Dicas rápidas

- Você precisa adicionar pelo menos um cliente dos banners e uma
  categoria dos banner *antes* de adicionar um banner.

## Informações relacionadas

- Para criar ou editar banners: [Banners -
  Novo/editar](https://docs.joomla.org/Help4.x:Banners:_Edit/pt-br "Help4.x:Banners: Edit/pt-br")
- Para trabalhar com clientes dos banners: [Gerenciador dos clientes dos
  banners](https://docs.joomla.org/Help4.x:Banners:_Clients/pt-br "Help4.x:Banners: Clients/pt-br")
