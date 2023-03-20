<!-- Filename: Help4.x:Site_Modules:_Articles_-_Category / Display title: Ajuda4.x:Módulos do site: Artigos - Categoria -->

## Descrição

O módulo **Artigos - Categoria** exibe uma lista com os artigos
publicados em uma ou mais categorias.

## Como acessar

- Selecione **Sistema **→** Gerenciar (painel) **→** Módulos do site**
  no menu da administração. Então...
  - Para criar um novo módulo: selecione o botão **Novo** na barra das
    ferramentas. Então...
    - Selecione o tipo do módulo necessário.
  - Para editar um módulo existente:
    - Encontre o módulo na lista contendo os módulos instalados e
      selecione o link do título na coluna **Título**.

## Captura da tela

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-site-module-manager-module-articles-category-pt-br.png"
class="new"
title="File:Help-4x-modules-site-module-manager-module-articles-category-pt-br.png">800px</a>

## Campos do formulário

- **Título**: O título do módulo. Este também é o título exibido para o
  módulo dependendo do campo *Mostrar título* do formulário

### Aba (guia) Módulo

**Painel esquerdo**

- **Modo**: (*Normal*/*dinâmico*). Por favor, selecione o modo que você
  gostaria de usar. Se o modo normal for escolhido, basta configurar o
  módulo e ele mostrará uma lista estática dos artigos nos itens dos
  menus aos quais você atribuir o módulo. Se o modo dinâmico for
  escolhido, você ainda poderá configurar o módulo normalmente, porém
  agora a opção para categoria(s) não será mais utilizada. Em vez disso,
  o módulo detectará dinamicamente se você está ou não em uma exibição
  para categoria(s) e mostrará a lista dos artigos dessa(s)
  categoria(s). Quando o modo dinâmico é escolhido, é melhor deixar o
  módulo configurado para mostrar em todas as páginas, pois ele decidirá
  se deseja ou não mostrar algo dinamicamente.
- **Mostrar na página do artigo**: (*Mostrar*/*ocultar*). Selecione para
  mostrar ou ocultar a lista dos artigos a partir das páginas dos
  artigos. Isso significa que o módulo só será mostrado dinamicamente
  nas páginas da(s) categoria(s).

**Painel direito**

- **Mostrar título**: (Mostrar/Ocultar) Escolhe se mostra ou oculta o
  título dos módulos no front-end. O título será aquele no campo do
  formulário acima.
- **Posição**: Escolhe a [posição do
  módulo](https://docs.joomla.org/Module_Position/pt-br "Module Position/pt-br")
  na qual deseja que o módulo seja exibido. Uma posição de módulo
  personalizada pode ser inserida para uso com o [plugin para carregar
  posição](https://docs.joomla.org/How_do_you_put_a_module_inside_an_article%3F/pt-br "How do you put a module inside an article?/pt-br")
  ou o botão de posição pode ser pressionado para selecionar uma posição
  de módulo do tema.
- **Estado**: O estado de publicação do item.
- **Acesso**: O [nível de acesso de
  visualização](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/pt-br "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/pt-br")
  para este item.
- **Ordenação dos módulos**: Isso mostra uma lista suspensa de cada
  módulo na posição em que o módulo em questão está. Esta é a ordem em
  que os módulos serão exibidos quando exibidos no frontend, bem como na
  página
  "[Módulos](https://docs.joomla.org/Help4.x:Modules/pt-br "Help4.x:Modules/pt-br")".
- **Início da publicação**: Data e hora para iniciar a publicação. Use
  este campo se desejar inserir conteúdo antecipadamente e publicá-lo
  automaticamente no futuro.
- **Término da publicação**: Data e hora para o término da publicação.
  Use este campo se desejar que o conteúdo seja alterado automaticamente
  para o estado "Não publicado" em um momento futuro (por exemplo,
  quando não for mais aplicável).
- **Linguagem**: Linguagem do item.
- **Nota**: Isso normalmente é para uso da administração do site (por
  exemplo, para documentar informações sobre o item) e não aparece no
  frontend do mesmo.

### Aba (guia) Atribuição no(s) menu(s)

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-manager-site-module-menu-assignment-tab-pt-br.png"
class="new"
title="File:Help-4x-modules-manager-site-module-menu-assignment-tab-pt-br.png">800px</a>

- **Atribuição de módulo**: Selecione **Em todas as páginas**, **Nenhuma
  página**, **Apenas nas páginas selecionadas** ou **Em todas as
  páginas, exceto as selecionadas** da lista.
- **Seleção de menu**: Se as duas últimas opções forem selecionadas, uma
  lista mostrará todos os itens de menu. Isso permite que você atribua
  módulos à algumas, mas não à todas as páginas, e selecionando os links
  de menu aos quais deseja associar o módulo, você pode personalizar em
  quais páginas os módulos aparecem/não aparecem. Consulte [Como você
  atribui um módulo a páginas
  específicas?](https://docs.joomla.org/How_do_you_assign_a_module_to_specific_pages%3F/pt-br "How do you assign a module to specific pages?/pt-br")
  para mais informações.

### Aba (guia) Opções da filtragem

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-site-module-manager-module-articles-category-filtering-options-pt-br.png"
class="new"
title="File:Help-4x-modules-site-module-manager-module-articles-category-filtering-options-pt-br.png">800px</a>

- **Artigos destacados**: (*Mostrar*/*ocultar*/*somente*). Selecione
  para também mostrar, ocultar, ou somente mostrar artigos destacados.
- **Quantidade**: O número (quantidade) de itens a serem mostrados. O
  valor padrão ("0") mostrará todos os artigos.
- **Tipo da filtragem por categoria(s)**: (*Inclusivo*/*exclusivo*).
  Selecione inclusivo, para incluir as categorias selecionadas, ou
  exclusivo, para não incluir as categorias selecionadas.
- **Categoria(s)**: Por favor, selecione uma ou mais categorias.
- **Artigo(s) da(s) categoria(s) filha(s)**: (*Incluir*/*excluir*).
  Incluir ou não incluir os artigos das categorias filhas.
- **Profundidade da(s) categoria(s)**: O número (quantidade) de níveis
  das categoria filhas a serem retornados.
- **Tipo da filtragem por autores**: (*Inclusivo*/*exclusivo*).
  Selecione inclusivo, para incluir os autores selecionados, ou
  exclusivo, para não incluir os autores selecionados.
- **Autor(es)**: Selecione um ou mais autores a partir da lista abaixo.
- **Tipo da filtragem por alias(es) do(s) autor(es)**:
  (*Inclusivo*/*exclusivo*). Selecione inclusivo, para incluir o(s)
  alias(es) do(s) autor(es) selecionado(s), ou exclusivo, para não
  incluir o(s) alias(es) do(s) autor(es) selecionado(s).
- **Alias(es) do(s) autor(es)**: Selecione um ou mais alias(es) do(s)
  autor(es) a partir da lista abaixo.
- **IDs dos artigos que não serão incluídos**: Insira cada ID em uma
  nova linha.
- **Filtragem por datas**: (*Desligada*/*intervalo entre datas*/*data
  relativa*). Selecione o tipo da filtragem por datas.
- **Campo do intervalo das datas**: (*Datas das criações*/*datas das
  modificações*/*datas dos inícios das publicações*). Selecione a qual
  dos campos das datas você deseja que o intervalo das datas seja
  aplicado.
- **Data inicial do intervalo**: Se o intervalo entre datas estiver
  selecionado acima, por favor insira uma data inicial.
- **Data término do intervalo**: Se o intervalo entre datas estiver
  selecionado acima, por favor insira uma data término.
- **Data relativa**: Se a data relativa for selecionada acima, por favor
  insira um valor numérico para os dias. Os resultados serão recuperados
  em correspondência à data atual e ao valor que você insere.

### Aba (guia) Opções da classificação

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-site-module-manager-module-articles-category-ordering-options-pt-br.png"
class="new"
title="File:Help-4x-modules-site-module-manager-module-articles-category-ordering-options-pt-br.png">800px</a>

- **Campo dos artigos pelo qual classificar**: (*Ordem do gerenciador
  dos artigos*/*ordem dos artigos
  destacados*/*acessos*/*títulos*/*IDs*/*aliases*/*datas das
  criações*/...). Selecione por qual dos campos você deseja que os
  artigos sejam classificados. A classificação dos destacados só deve
  ser usada quando a opção da filtragem para artigos destacados estiver
  definida como "somente".
- **Direção da clasdificação**: (*Em ordem decrescente*/*em ordem
  crescente*). Selecione a direção pela qual deseja que os artigos sejam
  ordenados.

### Aba (guia) Opções do agrupamento

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-site-module-manager-module-articles-category-grouping-options-pt-br.png"
class="new"
title="File:Help-4x-modules-site-module-manager-module-articles-category-grouping-options-pt-br.png">800px</a>

- **Agrupamento dos artigos**: (*Nenhum*/*anos*/*meses e
  anos*/*autores*/*categorias*). Selecione como você gostaria que os
  artigos fossem agrupados.
- **Direção do agrupamento**: (*Em ordem decrescente*/*em ordem
  crescente*). Selecione a direção pela qual deseja que os agrupamentos
  dos artigos sejam classificados.
- **Formato da exibição dos mesed e dos anos**: Insira um formato válido
  para datas. Consulte:
  <a href="https://www.php.net/manual/pt_BR/function.date.php"
  class="external free" target="_blank"
  rel="nofollow noreferrer noopener">https://www.php.net/manual/pt_BR/function.date.php</a>
  para obter informações relacionadas à formatação.

### Aba (guia) Opções da exibição

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-site-module-manager-module-articles-category-display-options-pt-br.png"
class="new"
title="File:Help-4x-modules-site-module-manager-module-articles-category-display-options-pt-br.png">800px</a>

- **Títulos vinculados**: (*Sim*/*não*).
- **Data**: (*Mostrar*/*ocultar*). Selecione para mostrar se você deseja
  que a data seja mostrada.
- **Campo da data**: (*Datas das criações*/*datas das
  modificações*/*datas dos inícios das publicações*). Selecione qual dos
  campos das datas você deseja mostrar.
- **Formato das datas**: Por favor, insira um formato válido para as
  datas. Consulte:
  <a href="https://www.php.net/manual/pt_BR/function.date.php"
  class="external free" target="_blank"
  rel="nofollow noreferrer noopener">https://www.php.net/manual/pt_BR/function.date.php</a>
  para obter informações relacionadas à formatação.
- **Categoria**: (*Mostrar*/*ocultar*). Selecione para mostrar se deseja
  que o nome da categoria seja mostrado.
- **Acessos**: (*Mostrar*/*ocultar*). Selecione para mostrar se deseja
  que o número dos acessos de cada artigo sejam exibidos.
- **Autores**: (*Mostrar*/*ocultar*). Selecione para mostrar se deseja
  que os autores (ou os aliases dos autores, se disponível) sejam
  mostrados.
- **Textos introdutórios**: (*Mostrar*/*ocultar*). Selecione para
  mostrar se deseja que os textos introdutórios sejam mostrados.
- **Limite para os textos introdutórios**: Por favor, insira um valor
  limite em caracteres numéricos. Os textos introdutórios serão
  reduzidos para o número de caracteres que você inserir.
- **Mostrar o "Ler mais":** (*Mostrar*/*ocultar*). Se definido para
  mostrar, os links "Ler mais..." serão mostrados se o textos principais
  forem fornecidos para os artigos.
- **Mostrar os títulos com o "Ler mais ..."**: (*Mostrar*/*ocultar*). Se
  configurado para mostrar, os títulos dos artigos serão mostrados nos
  botões "Ler mais ...".
- **Limite do "Ler mais ..."**: Defina um limite na quantidade dos
  caracteres nos títulos dos artigos para serem mostrados nos botões
  "Ler mais ...".

### Aba (guia) Avançado

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-site-module-manager-module-articles-category-advanced-options-pt-br.png"
class="new"
title="File:Help-4x-modules-site-module-manager-module-articles-category-advanced-options-pt-br.png">800px</a>

- **Disposição**: Se você definiu uma ou mais disposições (layouts)
  alternativas para um módulo no tema ou no núcleo do Joomla!, você pode
  selecionar a disposição (layout) a ser usada para este módulo.
- **Classe do módulo**: Um sufixo aplicado à classe CSS do módulo. Isso
  permite que você crie estilos CSS personalizados que serão aplicados
  apenas a este módulo. Você então modificaria o arquivo "user.css" do
  seu tema (modelo) para aplicar o estilo a essa nova classe. Insira
  este parâmetro com um espaço à esquerda para criar uma nova classe CSS
  para este módulo. Insira o parâmetro sem um espaço à esquerda para
  alterar o nome da classe CSS para este módulo.
- **Cache**: Usar global/sem cache. Se deve ou não armazenar em cache o
  conteúdo deste módulo. Definir a opção "Usar global" usará as
  configurações de cache da tela de configurações globais.
- **Tempo de cache**: O número de segundos para armazenar o item em
  cache localmente. Pode ser deixado com segurança no padrão.
- **Estilo do módulo**: Você pode usar esta opção para substituir o
  estilo do tema para sua posição.
- **Tag do módulo.** A tag de HTML para o módulo a ser colocada. Por
  padrão, esta é uma tag div, mas outros elementos da HTML5 também podem
  ser usados.
- **Tamanho do bootstrap**: (Valores de 0 a 12) Isso permite que você
  escolha a largura do módulo através do elemento span embutido no
  bootstrap.
- **Tag de cabeçalho**: A tag da HTML a ser usada para o cabeçalho ou o
  título dos módulos. Esta pode ser uma tag h1, h2, h3, h4, h5, h6 ou p.
  Observe que você deve usar um estilo de módulo (chrome) da html5 ou
  adicionar seus estilos de módulo personalizados em /html/modules.php.
- **Classe de cabeçalho**: Aqui você pode adicionar classes CSS
  opcionais para adicionar ao cabeçalho do módulo ou ao elemento de
  título.

### Aba (guia) Permissões do módulo

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-manager-admin-module-administrator-permissions-pt-br.png"
class="new"
title="File:Help-4x-modules-manager-admin-module-administrator-permissions-pt-br.png">800px</a>

Para alterar as permissões, faça o seguinte.

- Selecione o **grupo** clicando em seu título localizado à direita.
- Localize a **ação** desejada. As ações possíveis são:
  - **Excluir**: Os usuários podem excluir o módulo.
  - **Editar**: Os usuários podem editar o módulo.
  - **Editar estado**: O usuário pode alterar o estado de publicação e
    as informações relacionadas ao módulo.
- Seleciona a permissão desejada para a ação que deseja alterar. As
  configurações possíveis são:
  - ***Herdado***: Herdado, para usuários neste grupo, das permissões
    das configurações globais, das opções do gerenciador de artigos ou
    das categorias.
  - ***Permitido***: Permitido para usuários deste grupo. Observe que,
    se esta ação for negada em um dos níveis mais altos, a permissão
    aqui não terá efeito. Uma configuração negada não pode ser
    substituída.
  - ***Negado***: Negado para usuários neste grupo.
- Selecione **salvar** na **barra de ferramentas**. Quando a tela for
  atualizada, a coluna "Configuração calculada" mostrará a permissão
  efetiva relacionada a este grupo e à esta ação.

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
- **Fechar**: Fecha a tela atual e retorna à tela anterior sem salvar
  nenhuma modificação que tenha feito. Este ícone da barra de
  ferramentas não é exibido se você estiver criando um novo item.
- **Ajuda**: Abre a tela de ajuda.

## Captura da tela do site (front-end)

*As imagens de exemplo do site (frontend) são imagens genéricas usando
os temas gratuitos do site (front-end) fornecidos na instalação do
núcleo do Joomla!. A visualização real pode depender do tema
personalizado instalado usado e do estilo do tema para essas
visualizações em um site Joomla!.* Módulo para categoria(s) dos artigos
mostrado:

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-module-manager-articles-category-frontend-screenshot-pt-br.png"
class="new"
title="File:Help-4x-module-manager-articles-category-frontend-screenshot-pt-br.png">File:Help-4x-module-manager-articles-category-frontend-screenshot-pt-br.png</a>

O nome do tipo do módulo para este módulo é "mod_articles_category". Ele
está relacionado ao componente do conteúdo.
