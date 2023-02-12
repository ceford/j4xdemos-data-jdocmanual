<!-- Filename: Help4.x:Banners:_Edit / Display title: Banners: Editar -->

## Descrição

Usado para adicionar ou editar banners que podem ser mostrados em seu
site Joomla!. Lembre-se de criar pelo menos um [cliente do
banner](https://docs.joomla.org/Help4.x:Banners:_Clients/pt-br "Help4.x:Banners: Clients/pt-br")
e uma [categoria do
banner](https://docs.joomla.org/Help4.x:Banners:_Categories/pt-br "Help4.x:Banners: Categories/pt-br")
antes de criar quaisquer banners.

## Como acessar

Para "**adicionar**" um novo banner ou "**editar**" um banner existente,
navegue até o [Gerenciador para
banners](https://docs.joomla.org/Help4.x:Banners/pt-br "Help4.x:Banners/pt-br"):

- Selecione **Componentes **→** Banners **→** Novo** para criar um novo
  banner.
- Selecione **Components **→** Banners** e acione o nome do banner para
  "**editar**" um banner existente.

## Captura da tela

Um banner pode ser uma imagem acionável ou algum código personalizado. O
tipo da imagem é mostrado na captura da tela abaixo. O tipo
personalizado tem a caixa para seleção da imagem substituída por uma
área para texto código.

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Components-Banners-Banners-Edit-screen-pt-br.png"
class="new"
title="File:Help-4x-Components-Banners-Banners-Edit-screen-pt-br.png">800px</a>

## Campos do formulário

- **Nome**: O nome do banner. Este é o nome que será mostrado na coluna
  *Nome* do [gerenciador para
  banners](https://docs.joomla.org/Help4.x:Banners/pt-br "Help4.x:Banners/pt-br").

<!-- -->

- **Alias**: O nome interno do item. Normalmente, você pode deixar em
  branco e o Joomla preencherá um valor padrão de título em letras
  minúsculas e com traços em vez de espaços. [Saiba
  mais.](https://docs.joomla.org/Alias/pt-br "Special:MyLanguage/Alias/pt-br")

### Aba (guia) Detalhes

**Painel esquerdo**

- **Type**: O tipo do banner a ser mostrado. As opções são um arquivo de
  imagem ou código HTML personalizado.
  - **Imagem**: Arquivo da imagem a ser mostrada no banner. Clique no
    botão *Selecionar* para navegar e selecionar o arquivo da imagem a
    ser usada. Use a página
    [Mídia](https://docs.joomla.org/Help4.x:Media/pt-br "Help4.x:Media/pt-br")
    para enviar arquivos de imagem para banners ao seu site. As imagens
    para os banners devem estar no diretório
    https://docs.joomla.org/images/banners/.
    - **Largura**: A largura fixa para redimensionar a imagem do banner.
      Deixe em branco se quiser usar a largura real do arquivo da imagem
      do banner.
    - **Altura**: A altura fixa para redimensionar a imagem do banner.
      Deixe em branco se quiser usar a altura real do arquivo da imagem
      do banner.
    - **Texto alternativo**: Texto a ser mostrado no lugar da imagem do
      banner caso a imagem não possa ser mostrada.
    - **Texto alternativo**: Texto alternativo para a imagem do banner.
  - **Personalizado**: Selecione "Personalizado" se desejar inserir um
    código personalizado para seu banner.
    - **Código personalizado**: Use {CLICKURL} e {NAME} para mesclar os
      valores "URL ao acionar" e "Nome", respectivamente, em seu código
      personalizado. Por exemplo:
      [![`{NAME}`](insira%20o%20URL%20da%20imagem "{NAME}")](%7BCLICKURL%7D).  
      Outra opção é inserir um código HTML personalizado. Por exemplo:
      [![](caminhodasuaimagem)](https://seudomínio.com)
- **URL ao acionar**: O URL que será acionado quando o usuário acionar o
  banner.
- **Description**. Enter a description for the Banner.

**Painel direito**

- **Estado**: O estado de publicação do item.

<!-- -->

- **Fixado**: *(Sim ou não)* Se o banner está "fixado" ou não. Se um ou
  mais banners em uma categoria forem designados como "fixados", eles
  terão prioridade sobre os banners que não forem fixos.

*Por exemplo, se dois banners em uma categoria estiverem fixados e um
terceiro banner não estiver, o terceiro banner não será mostrado se a
configuração do módulo para exibição do banner for "Fixado, aleatório"
ou "Fixado, ordenado". Apenas os dois banners fixados serão mostrados.
Se os banners fixados tiverem uma quantidade de impressões
(visualizações) predefinida, quando essas impressões forem usadas, os
banners fixados não serão mais mostrados e os que não são fixados
começarão a ser mostrados automaticamente.*

- **Linguagem**: Linguagem do item.

<!-- -->

- **Nota da versão**: Campo opcional para identificar esta versão do
  item na janela do [histórico das
  versões](https://docs.joomla.org/Help40:Components_Version_History/pt-br "Special:MyLanguage/Help40:Components Version History/pt-br")
  do item.

### Aba (guia) Detalhes do banner

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Components-Banners-Banners-Edit-Banners-Details-Tab-pt-br.png"
class="new"
title="File:Help-4x-Components-Banners-Banners-Edit-Banners-Details-Tab-pt-br.png">800px</a>

- **Máximo de impressões**: A quantidade de impressões (visualizações)
  compradas para este banner. As impressões são a quantidade de vezes
  que um banner será mostrado em uma página. Marque a caixa de seleção
  "ilimitado" se uma quantidade ilimitada de impressões for permitida.
- **Total de impressões**: a quantidade de vezes que este banner foi
  mostrado em uma página web para os usuários. Nenhuma entrada é
  permitida. Você pode redefinir esse número para 0 pressionando o botão
  "Redefinir impressões".
- **Total de acionamentos**: a quantidade de vezes que este banner foi
  acionado. Nenhuma entrada é permitida. Você pode redefinir esse número
  para 0 pressionando o botão "Redefinir acionamentos".

<!-- -->

- **Cliente**: O cliente para este banner. Os clientes são inseridos
  usando o gerenciador dos clientes para banners.

Selecione um na caixa da lista suspensa dos clientes existentes.

- **Tipo da compra**: O tipo da compra relacionada ao banner. Isso é
  usado para indicar como o cliente do banner comprou o tempo de
  exibição do banner.

As opções seguintes são: (*- Usar padrão do cliente -, ilimitado, anual,
mensal, semanal, diário*).

- **Monitorar as impressões**: Se deve ou não monitorar a quantidade de
  vezes que o banner é mostrado para os visitantes do site.
- **Monitorar acionamentos**: Se deve ou não monitorar a quantidade de
  vezes que o banner é acionado (clicado) pelos visitantes do site.

### Aba (guia) Publicação

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Components-Banners-Banners-Edit-Publishing-Options-Tab-pt-br.png"
class="new"
title="File:Help-4x-Components-Banners-Banners-Edit-Publishing-Options-Tab-pt-br.png">800px</a>

- **Início da publicação**: Data em que o banner será publicado e estará
  disponível para o site.

Insira a data (hora opcional) no formato *ano-mês-data hrs:min:seg* como
"2013-01-07 14:10:00" ou, alternativamente, use a janela modal "pop up"
e selecione uma data no calendário.

- **Término da publicação**: Data em que o banner deixará de ser
  publicado e não estará mais disponível para o site.

Insira a data (hora opcional) no formato *ano-mês-data hrs:min:seg* como
"2013-01-07 14:10:00" ou, alternativamente, use a janela modal "pop up"
e selecione um data no calendário.

- **Data da criação**: Data em que o item (artigo, categoria, link da
  web etc.) foi criado.

<!-- -->

- **Criado por**: Nome do usuário que criou este item em seu Joomla!.
  Por padrão, será o usuário conectado no momento. Se você quiser mudar
  isso para um usuário diferente, acione o (clique no) botão "Selecionar
  usuário" para selecionar um usuário diferente.

<!-- -->

- **Criado pelo alias**: Este campo opcional permite que você insira um
  alias para este autor para este artigo. Isso permite que você mostre
  um nome de autor diferente para este artigo.

<!-- -->

- **Data da modificação**: Data da última modificação.

<!-- -->

- **Modificado por**: Nome como usuário de quem executou a última
  modificação.

<!-- -->

- **Revisão**: Número das revisões neste item.

<!-- -->

- **Palavras-chaves**: Entrada opcional para palavras-chaves. Precisam
  ser inseridas separadas por vírgulas (por exemplo, "gatos, cachorros,
  animais de estimação") e podem ser inseridas em letras maiúsculas ou
  minúsculas. (Por exemplo, "GATOS" corresponderá a "gatos" ou "Gatos").
  As palavras-chaves podem ser usadas de várias maneiras:
  1.  Para ajudar os mecanismos para pesquisas e outros sistemas a
      classificar o conteúdo do artigo.
  2.  Em combinação com as tags para banners, para mostrar banners
      específicos com base no conteúdo do artigo. Por exemplo, digamos
      que você tenha um banner com um anúncio para produtos para cães e
      outro banner para produtos para gatos. Você pode mostrar seu
      banner relacionado à cachorros quando um usuário estiver
      visualizando um artigo relacionado a cães e seu banner relacionado
      a gatos quando um usuário estiver visualizando um artigo
      relacionado a gatos. Para fazer isso, você precisa fazer o
      seguinte:
      - Adicione as palavras-chave "cachorro" e "gato" aos artigos
        apropriados.
      - Adicione as tags "cachorro" e "gato" aos banners apropriados em
        [Banners:
        Editar](https://docs.joomla.org/Help40:Banners:_Edit/pt-br "Special:MyLanguage/Help40:Banners: Edit/pt-br").
      - Defina o parâmetro, do módulo para banners, "Pesquisar por tags"
        como "Sim" em [Módulos do site:
        Banners](https://docs.joomla.org/Help40:Site_Modules:_Banners/pt-br "Special:MyLanguage/Help40:Site Modules: Banners/pt-br").
  3.  Apenas para artigos, em combinação com o módulo "[Artigos -
      Relacionados](https://docs.joomla.org/Help40:Site_Modules:_Articles_-_Related/pt-br "Special:MyLanguage/Help40:Site Modules: Articles - Related/pt-br")",
      para mostrar artigos que compartilham pelo menos uma palavra-chave
      em comum. Por exemplo, se o artigo que está sendo mostrado tiver
      as palavras-chaves "gatos, cachorros, macacos", quaisquer outros
      artigos com pelo menos uma dessas palavras-chaves serão exibidos
      no módulo "Artigos - Relacionados".

<!-- -->

- **Usar prefixo próprio**: Se deve ou não usar o prefixo do banner ou
  do cliente. Selecione *Não* se quiser usar o prefixo do cliente do
  banner.

<!-- -->

- **Prefixo para meta palavras-chaves**: Ao fazer a correspondência das
  meta palavras-chaves, pesquisa apenas meta palavras-chaves com esses
  prefixos opcionais. Isso melhora o desempenho.

## Barra das ferramentas

No topo da página você verá a barra de ferramentas mostrada na [captura
de tela](#Captura_de_tela) acima. As funções são:

- **Salvar**: Salva o item e permanece na tela atual.

<!-- -->

- **Salvar fechar**: Salva o item e fecha a tela atual.

<!-- -->

- **Salvar & novo**: Salva o item e mantém a tela de edição aberta e
  pronta para criar outro item.

<!-- -->

- **Salvar como cópia**: Salva suas alterações em uma cópia do item
  atual. Não afeta o item atual. Este ícone da barra de ferramentas não
  é exibido se você estiver criando um novo item.

<!-- -->

- **Cancelar**: Fecha a tela atual e retorna à tela anterior sem salvar
  nenhuma modificação que você tenha feito. Ou

<!-- -->

- **Fechar**: Fecha a tela atual e retorna à tela anterior sem salvar
  nenhuma modificação que tenha feito. Este ícone da barra de
  ferramentas não é exibido se você estiver criando um novo item.

<!-- -->

- **Versões**: Abre a janela do histórico das versões do item para
  mostrar as versões anteriores deste item. Isso permite que você
  visualize versões mais antigas deste item e, se desejar, restaure a
  partir de uma versão mais antiga. Consulte [histórico das
  versões](https://docs.joomla.org/Help40:Components_Version_History/pt-br "Special:MyLanguage/Help40:Components Version History/pt-br")
  para mais informações.

<!-- -->

- **Ajuda**: Abre a tela de ajuda.

## Dicas rápidas

- Os banners são colocados em páginas específicas adicionando módulos do
  tipo "banners" através do [gerenciador para
  módulos](https://docs.joomla.org/Help4.x:Modules/pt-br "Help4.x:Modules/pt-br").
- Se você tem uma série de banners que gostaria de mostrar
  aleatóriamente em uma ou mais páginas:
  1.  Crie os banners que deseja incluir, certificando-se de que
      pertençam ao mesmo cliente e à mesma categoria.
  2.  Crie um módulo para banners para este cliente e categoria e, na
      atribuição do(s) menu(s), escolha as seleções dos menus para o
      módulo ser mostrado.
  3.  No módulo para banners, defina o valor "Aleatorização" como
      "Fixado, aleatóriamente".

Com essas configurações, os diferentes banners para esse cliente e essa
categoria serão mostrados nas páginas selecionadas em ordem aleatória.

## Informações relacionadas

**Mais ajuda relacionada ao componente para banners**:

|                                                                                                                                                                  |                                                                                                                                                                                                                                                                                                                                                                                                      |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Telas de ajuda relacionadas                                                                                                                                      | Descrição                                                                                                                                                                                                                                                                                                                                                                                            |
| [Banners](https://docs.joomla.org/Help4.x:Banners/pt-br "Help4.x:Banners/pt-br")                                                                                 | Usado para visualizar uma lista contendo os banners existentes, editar os atuais e criar novos banners. Deve haver pelo menos um cliente para banner e uma categoria para banner antes que um banner possa ser criado.                                                                                                                                                                               |
| [Banners: Opções](https://docs.joomla.org/Help4.x:Banners:_Options/pt-br "Help4.x:Banners: Options/pt-br")                                                       | Opções globais (configurações) relacionadas a clientes para banners.                                                                                                                                                                                                                                                                                                                                 |
| [Banners: Categorias](https://docs.joomla.org/Help4.x:Banners:_Categories/pt-br "Help4.x:Banners: Categories/pt-br")                                             | Usado para visualizar uma lista contendo as categorias para banners existentes, editar as atuais e criar novas categorias para banners. Observe que as categorias para banners são separadas das outras categorias, como artigos, contatos, feeds paranotícias e links da web. É preciso haver pelo menos um cliente para banners e uma categoria para banners antes que um banner possa ser criado. |
| [Banners: Categoria nova ou editar categoria](https://docs.joomla.org/Help4.x:Banners:_New_or_Edit_Category/pt-br "Help4.x:Banners: New or Edit Category/pt-br") | É aqui que você pode adicionar uma nova categoria para banners ou editar uma já existente. Observe que você precisa criar pelo menos uma categoria para banners antes de criar um banner. Além disso, as categorias para banners são separadas dos outros tipos de categorias, como artigos, contatos e feeds para notícias.                                                                         |
| [Banners: Clientes](https://docs.joomla.org/Help4.x:Banners:_Clients/pt-br "Help4.x:Banners: Clients/pt-br")                                                     | O gerenciador dos clientes para banners é onde você pode editar os clientes para banners existentes ou criar novos. Observe que você deve ter pelo menos um cliente para banners e uma categoria para banners definidos antes de poder adicionar seu primeiro banner.                                                                                                                                |
| [Banners: Cliente novo ou editar cliente](https://docs.joomla.org/Help4.x:Banners:_New_or_Edit_Client/pt-br "Help4.x:Banners: New or Edit Client/pt-br")         | É aqui que você adiciona um novo cliente para banners ou edita um existente. Observe que você precisa criar pelo menos um cliente para banners antes de criar um banner.                                                                                                                                                                                                                             |
| [Monitaramento para os banners](https://docs.joomla.org/Help4.x:Banners:_Tracks/pt-br "Help4.x:Banners: Tracks/pt-br")                                           | Usado para visualizar uma lista contendo informações sobre o monitoramento dos banners existentes.                                                                                                                                                                                                                                                                                                   |

**Para colocar banners nas páginas**:

|                                                                                                                       |                                                            |
|-----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| Telas de ajuda relacionadas                                                                                           | Descrição                                                  |
| [Módulo "Banners"](https://docs.joomla.org/Help4.x:Site_Modules:_Banners/pt-br "Help4.x:Site Modules: Banners/pt-br") | O módulo "Banners" mostra os banners ativos do componente. |
