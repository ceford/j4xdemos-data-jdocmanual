<!-- Filename: Help4.x:Articles:_Edit / Display title: Ajuda4.x:Artigos: Editar -->

## Descrição

Esta tela é usada para adicionar um novo artigo ou editar um artigo
existente, geralmente usando um editor Wysiwyg. O editor padrão é o
TinyMCE, mas se outros editores estiverem instalados, o editor padrão
pode ser definido como qualquer outro para o site como um todo ou para
usuários individuais.

A maioria dos parâmetros tem padrões adequados, mas você pode querer
definir uma categoria específica ou fornecer metadados específicos para
o artigo.

## Como acessar

**Conteúdo **→** Artigos**

Para adicionar um artigo:

- clique no botão **Novo** na barra das ferramentas

Para editar um artigo:

- selecione um **Título** a partir da lista

## Captura da tela

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-content-article-manager-add-new-article-pt-br.png"
class="new"
title="File:Help-4x-content-article-manager-add-new-article-pt-br.png">800px</a>

## Campos do formulário

- **Título**. O título para este artigo.
- **Alias**. O nome interno deste artigo. Normalmente, você pode deixar
  isso em branco e o Joomla! preencherá com um valor padrão em letras
  minúsculas, e com hífens em vez de espaços, fundamentado no título.
  [Aprender mais.](https://docs.joomla.org/Alias/pt-br "Alias/pt-br")

### Conteúdo

**Painel esquerdo**

- **Texto do artigo**. É aqui que você insere o conteúdo do artigo. O
  Joomla! inclui 3 editores, o padrão ([Editor -
  TinyMCE](https://docs.joomla.org/Help4.x:Editors/pt-br#tinymce "Help4.x:Editors/pt-br"))
  é mostrado aqui.

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Article-Editor-buttons-pt-br.png"
class="new"
title="File:Help-4x-Article-Editor-buttons-pt-br.png">600px</a>

A lista suspensa do conteúdo no S.G.C. (CMS) fornece acesso aos links
para artigos, contatos, campos, mídia, menus ou módulos. [Aprender
mais.](https://docs.joomla.org/Help4.x:Editors/pt-br#cmscontent "Help4.x:Editors/pt-br")

- **Alternar editor**. O botão "Alternar editor" é mostrado abaixo da
  janela para edição. Este botão permite alternar entre o TinyMCE e
  [nenhum
  editor](https://docs.joomla.org/Help4.x:Editors/pt-br#none "Help4.x:Editors/pt-br").

**Painel direito**

- **Estado**. O estado da publicação deste artigo.
  - Publicado: O artigo torna-se visível no site (frontend).
  - Despublicado: O artigo não fica visível para os convidados no site
    (frontend). Ele pode ser visível para usuários que tenham iniciado
    suas sessões e que tenham [permissão para edição do
    estado](#permissions) no artigo.
  - Arquivado: O artigo não será mais mostrado nos itens dos menus que
    são <a
    href="https://docs.joomla.org/index.php?title=Help4.x:Menu_Item:_Category_Blog/pt-br&amp;action=edit&amp;redlink=1"
    class="new"
    title="Help4.x:Menu Item: Category Blog/pt-br (page does not exist)">blogs
    para categoria(s)</a> ou <a
    href="https://docs.joomla.org/index.php?title=Help4.x:Menu_Item:_Category_List/pt-br&amp;action=edit&amp;redlink=1"
    class="new"
    title="Help4.x:Menu Item: Category List/pt-br (page does not exist)">listas
    para categoria(s)</a>.
  - Lixeira: O artigo é excluído do site, mas ainda fica no banco de
    dados. [Aprender
    mais](https://docs.joomla.org/J4.x:Deleting_an_Article/pt-br "J4.x:Deleting an Article/pt-br").
- **Categoria**. Seleciona a categoria para este artigo.
- **Destacado**. Selecione "Sim" se o artigo deve ser mostrado no [item
  dos menus para
  destacados](https://docs.joomla.org/Help4.x:Menu_Item:_Featured_Articles/pt-br "Help4.x:Menu Item: Featured Articles/pt-br").
- **Acesso**. Seleciona o nível do acesso para visualização para este
  artigo. Os níveis dos acessos dependem do que foi configurado em
  [Usuários: Níveis dos
  acessos](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/pt-br "Help4.x:Users: Viewing Access Levels/pt-br").
- **Linguagem**. Seleciona a linguagem para este artigo. Mantenha o
  padrão "Todas" se você não estiver usando o <a
  href="https://docs.joomla.org/index.php?title=Help4.x:Extensions:_Languages/pt-br&amp;action=edit&amp;redlink=1"
  class="new"
  title="Help4.x:Extensions: Languages/pt-br (page does not exist)">recurso
  multilíngue</a>.
- **Tags**. Atribui tags a este artigo. Você pode selecionar uma tag a
  partir de uma <a
  href="https://docs.joomla.org/index.php?title=Help4.x:Tags/pr-br&amp;action=edit&amp;redlink=1"
  class="new" title="Help4.x:Tags/pr-br (page does not exist)">lista
  pré-definida</a> ou inserir uma nova tag digitando o nome no campo e
  pressionando enter.
- **Nota**. Isso é normalmente para uso administrativo (por exemplo,
  para documentar informações sobre este artigo) e não aparece no site
  (frontend).
- **Nota da versão**. Campo opcional para identificar a versão deste
  artigo no [histórico de
  versões](https://docs.joomla.org/Help4.x:Components_Version_History/pt-br "Help4.x:Components Version History/pt-br").

### Imagens e links

**Nota**: Isso pode ser ocultado por um usuário com permissões
administrativas em [Artigo:
Opções](https://docs.joomla.org/Help4.x:Articles:_Options/pt-br "Help4.x:Articles: Options/pt-br").  
Esta seção permite mostrar imagens e links em seus artigos usando
disposições padronizadas.

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-screenshot-article-edit-images-links-pt-br.png"
class="new"
title="File:Help-4x-screenshot-article-edit-images-links-pt-br.png">600px</a>

**Imagem da introdução**

- **Imagem da introdução**. Acione o (clique no) botão "Selecionar" para
  selecionar uma imagem que será mostrada em um local fixo no texto da
  introdução deste artigo. Isso abrirá uma janela que permite selecionar
  uma imagem da sua pasta de imagens. [Aprender
  mais](https://docs.joomla.org/Adding_an_image_to_an_article/pt-br "Adding an image to an article/pt-br").
- **Descrição da imagem (texto alternativo)**. Defina o atributo alt
  para esta imagem. Algumas palavras descritivas para os leitores de
  tela.
- **Nenhuma descrição**. Marque na rara instância de uma imagem
  puramente decorativa. Observe que, se a descrição da imagem estiver
  vazia e a caixa de seleção "Sem descrição" estiver desmarcada, a
  imagem não atenderá aos critérios de acessibilidade. Se uma descrição
  de imagem estiver presente, esta caixa de seleção não terá efeito.
- **Classe da imagem**. Você pode adicionar qualquer classe CSS para
  suas próprias ideias de estilo. Para a posição da imagem, use, por
  exemplo, float-start e float-end.
  <a href="https://cassiopeia.joomla.com/help" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">Aprender mais</a>.
- **Legenda**. Cria uma legenda para esta imagem.

**Imagem do artigo completo**

- **Imagem do artigo completo**. Acione o (clique no) botão "Selecionar"
  para selecionar uma imagem que será mostrada em um local fixo no texto
  completo deste artigo. Isso abrirá uma janela que permite selecionar
  uma imagem da sua pasta de imagens. [Aprender
  mais](https://docs.joomla.org/Adding_an_image_to_an_article/pt-br "Adding an image to an article/pt-br").
- **Descrição da imagem (texto alternativo)**. Define o atributo alt
  para esta imagem. Algumas palavras descritivas para os leitores de
  tela.
- **Nenhuma descrição**. Marque na rara instância de uma imagem
  puramente decorativa. Observe que, se a descrição da imagem estiver
  vazia e a caixa de seleção "Sem descrição" estiver desmarcada, a
  imagem não atenderá aos critérios de acessibilidade. Se uma descrição
  de imagem estiver presente, esta caixa de seleção não terá efeito.
- **Classe da imagem**. Você pode adicionar qualquer classe CSS para
  suas próprias ideias de estilo. Para a posição da imagem, use, por
  exemplo, float-start e float-end.
  <a href="https://cassiopeia.joomla.com/help" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">Aprender mais</a>.
- **Legenda**. Insira uma legenda opcional para esta imagem.

**Link A**

- **Link A**. O URL do primeiro link a ser mostrado em um local fixo no
  texto do artigo. Este deve ser um URL completo, não relativo. Por
  exemplo, normalmente começaria com 'https://'.
- **Texto do link A**. O texto usado para o "Link A". Se estiver em
  branco, o URL será mostrado.
- **Janela de destino do URL**. Define o valor padrão para o destino do
  primeiro link neste artigo. As opções são:
  - Abrir na janela principal: Abre na janela principal do navegador,
    substituindo o artigo atual do Joomla!.
  - Abrir em uma nova janela: Abre o link em uma nova janela do
    navegador.
  - Abrir em pop-up: Abre o link em uma janela pop-up do navegador (sem
    os controles para navegação completos).
  - Modal: Abre o link em uma janela pop-up modal.

**Link B**, **Link C**: Mesmas opções do "Link A."

### Opções

**Nota**: Isso pode ser ocultado por um usuário com permissões
administrativas em [Artigo:
Opções](https://docs.joomla.org/Help4.x:Articles:_Options/pt-br "Help4.x:Articles: Options/pt-br").  
Este é um conjunto de opções que você pode usar para controlar como este
artigo será mostrado no site (frontend).

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-screenshot-article-edit-article-options-pt-br.png"
class="new"
title="File:Help-4x-screenshot-article-edit-article-options-pt-br.png">600px</a>

**Disposição**

- **Disposição**. Usa uma disposição da exibição do artigo fornecida ou
  das <a
  href="https://docs.joomla.org/index.php?title=Help4.x:Templates:_Customize/pt-br&amp;action=edit&amp;redlink=1"
  class="new"
  title="Help4.x:Templates: Customize/pt-br (page does not exist)">substituições
  nos temas</a>.
- **Título**. Mostra o título do artigo.
- **Títulos vinculados**. Mostra o título como um link para o artigo.
- **Tags**. Insere as tags para este artigo. Selecione as tags
  existentes inserindo as primeiras letras ou crie novas tags
  inserindo-as aqui. <a
  href="https://docs.joomla.org/index.php?title=J4.x:How_To_Use_Content_Tags_in_Joomla/pt-br&amp;action=edit&amp;redlink=1"
  class="new"
  title="J4.x:How To Use Content Tags in Joomla/pt-br (page does not exist)">Aprender
  mais</a>.
- **Texto da introdução**.
  - Mostrar: O texto da introdução do artigo será mostrado quando você
    detalhar o artigo.
  - Ocultar: Apenas a parte do artigo após a pausa "Leia mais" será
    mostrada.
- **Posição das informações do artigo**.
  - Acima: Coloca o bloco de informações do artigo acima do texto.
  - Em baixo: Coloca o bloco de informações do artigo em baixo do texto.
  - Dividido: Divide o bloco de informações do artigo em 2 blocos
    separados. Um bloco está acima e o outro está abaixo do texto.
- **Título das Informações do artigo**. Mostra "Detalhes" na parte
  superior do bloco de informações do artigo.

**Categoria**

- **Categoria**. Mostra o título da categoria do artigo.
- **Link da categoria**. Mostra o título como um link para aquela
  categoria.
- **Categoria parental**. Mostra o título da categoria parental do
  artigo.
- **Link da categoria parental**. Mostra o título como um link para
  aquela categoria.

**Associações**

- **Associações**. Mostra as bandeiras ou os códigos das linguagens
  associadas. [Apenas
  multilíngue](https://docs.joomla.org/Help4.x:Multilingual_Associations/pt-br "Help4.x:Multilingual Associations/pt-br").

**Autor**

- **Autor**. Mostra o autor do artigo.
- **Link para a página de contato do autor**. Mostra isso como um link
  para uma disposição de contato desse autor.Nota: O autor deve ser <a
  href="https://docs.joomla.org/index.php?title=Help4.x:Contacts/pt-br&amp;action=edit&amp;redlink=1"
  class="new"
  title="Help4.x:Contacts/pt-br (page does not exist)">configurado como um
  contato</a>.

**Data**

- **Data da criação**. Mostra a data da criação do artigo.
- **Data da modificação**. Mostra a data da modificação do artigo.
- **Data da publicação**. Mostra a data do início da publicação do
  artigo.

**Opções**

- **Navigação**. Mostra um link para navegação "Anterior" ou "Próximo"
  ao detalhar o artigo.
- **Acionamentos (acessos, cliques)**. Mostra a quantidade de vezes que
  o artigo foi mostrado por um usuário.
- **Links não autorizados**. Se definido como "Sim", o textos
  introdutórios dos artigos restritos serão mostrados. Acionar o (clicar
  no) link "Leia mais" exigirá que os usuários iniciem uma sessão para
  visualizar o conteúdo completo do artigo.
- **Posicionamento dos links.**
  - Acima: Os links são mostrados acima do conteúdo.
  - Em baixo: Os links são mostrados abaixo do conteúdo.
- **Texto "Ler mais"**. Personaliza o texto que é mostrado para o texto
  padrão "Ler mais".
- **Título da página no navegador**. Texto para o título da página no
  navegador que será usado quando o artigo for visualizado com um item
  dos menus não relacionado ao artigo. Se estiver em branco (vazio), o
  título do artigo será usado.

### Campos

Esta seção mostra os <a
href="https://docs.joomla.org/index.php?title=Help4.x:Fields/pt-be&amp;action=edit&amp;redlink=1"
class="new" title="Help4.x:Fields/pt-be (page does not exist)">campos
personalizados</a> que foram definidos para este artigo.

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-pt-br.png"
class="new"
title="File:Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-pt-br.png">600px</a>

### Publicado

**Nota**: Isso pode ser ocultado por um usuário com permissões
administrativas no [Artigo:
Opções](https://docs.joomla.org/Help4.x:Articles:_Options/pt-br "Help4.x:Articles: Options/pt-br").  
Esta seção permite que você insira parâmetros e
[Metadados](https://docs.joomla.org/Using_The_Meta_Description/pt-br "Using The Meta Description/pt-br")
para este artigo.

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-pt-br.png"
class="new"
title="File:Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-pt-br.png">600px</a>

**Publicação**

- **Início da publicação**. Data e hora para iniciar a publicação.
  Insira o artigo com antecedência e, em seguida, publique-o
  automaticamente em um momento futuro.
- **Término da publicação**. Data e hora para terminar a publicação. O
  artigo é alterado automaticamente para o estado "Despublicado"
  posteriormente.
- **Início como destacado**. Data e hora para iniciar o estado como
  destacado. Insira o artigo com antecedência e, em seguida, apresente-o
  automaticamente em um momento futuro.
- **Término como destacado**. Data e hora para terminar o estado como
  destacado. O artigo é alterado automaticamente para o estado "Não
  destacado" em um momento futuro.
- **Data da criação**. A data no momento em que o artigo foi criado.
  Insira uma data e hora diferentes ou acione o (clique no) ícone do
  calendário para encontrar a data desejada.
- **Criado por**. Nome do usuário que criou este artigo. O padrão será o
  usuário conectado no momento. Se você quiser alterar isso para um
  usuário diferente, acione o (clique no) botão "Selecionar usuário".
- **Criado pelo alias**. Insira um alias (pseudônimo) para o autor deste
  artigo. Isso permite que você mostre um nome de autor diferente.
- **Data da modificação**. Data da última modificação.
- **Modificado por**. Nome de usuário que realizou a última modificação.
- **Revisão**. Quantidade de revisões para este artigo.
- **Acionamentos (acessos, cliques)**. A quantidade de vezes que este
  artigo foi visualizado.
- **ID**. Um número de identificação exclusivo para este artigo, você
  não pode alterar esse número. Ao criar um novo artigo, este campo
  mostra "0" até que você salve a nova entrada.

**Metadados**

- **Meta descrição**. Um parágrafo para ser usado como a descrição da
  página. [Aprender
  mais](https://docs.joomla.org/Using_The_Meta_Description/pt-br "Using The Meta Description/pt-br").
- **Palavras-chaves**. Entrada para palavras-chaves. <a
  href="https://docs.joomla.org/index.php?title=Using_Keywords/pt-br&amp;action=edit&amp;redlink=1"
  class="new" title="Using Keywords/pt-br (page does not exist)">Aprender
  mais</a>.
- **Robôs**. As instruções para os "robôs' da web que navegam nesta
  página. Defina "Usar global" nas [configurações
  globais](https://docs.joomla.org/Help4.x:Site_Global_Configuration/pt-br#robots "Help4.x:Site Global Configuration/pt-br").
- **Autor**. Entrada para um nome de autor nos metadados.
- **Direitos do conteúdo**. Descreve quais direitos os outros têm para
  usar este conteúdo.

### Associações

**Nota**: Isso pode ser ocultado por um usuário com permissões
administrativas em [Artigo:
Opções](https://docs.joomla.org/Help4.x:Articles:_Options/pt-br "Help4.x:Articles: Options/pt-br").  
A aba (guia) é mostrada apenas em [sites
multilíngues](https://docs.joomla.org/Help4.x:Multilingual_Associations/pt-br "Help4.x:Multilingual Associations/pt-br").

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-screenshot-article-edit-associations-pt-br.png"
class="new"
title="File:Help-4x-screenshot-article-edit-associations-pt-br.png">600px</a>

### Configurar a tela para edição

**Nota**: Isso pode ser ocultado por um usuário com permissões
administrativas em [Artigo:
Opções](https://docs.joomla.org/Help4.x:Articles:_Options/pt-br "Help4.x:Articles: Options/pt-br").

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-screenshot-article-edit-configure-edit-screen-pt-br.png"
class="new"
title="File:Help-4x-screenshot-article-edit-configure-edit-screen-pt-br.png">600px</a>

- **Opções da publicação**. Se configurado para "Ocultar", a [aba (guia)
  "Opções da
  publicação"](https://docs.joomla.org/Help4.x:Articles:_Edit/pt-br#publishing "Help4.x:Articles: Edit/pt-br")
  não aparecerá na área administrativa (backend). Isso significa que os
  usuários da área administrativa (backend) não poderão editar os campos
  nesta aba (guia). Esses campos sempre serão definidos com seus valores
  padrões.
- **Opções do artigo**. Se configurado para "Ocultar", a [aba (guia)
  "Opções do
  artigo"](https://docs.joomla.org/Help4.x:Articles:_Edit/pt-br#options "Help4.x:Articles: Edit/pt-br")
  não aparecerá na área administrativa (backend). Isso significa que os
  usuários da área administrativa (backend) não poderão editar os campos
  nesta aba (guia). Esses campos sempre serão definidos com seus valores
  padrões.
- **Imagens e links na administração (backend)**. Se configurado como
  "Sim", a <a
  href="https://docs.joomla.org/index.php?title=Help4.x:Articles:_Edit/pr-br&amp;action=edit&amp;redlink=1"
  class="new"
  title="Help4.x:Articles: Edit/pr-br (page does not exist)">aba (guia)
  "Imagens e links"</a> será mostrada.
- **Imagens e links no site (frontend)**. Se configurado como "Sim", a
  aba (guia) "Imagens e links" será mostrada na tela do editor do artigo
  no site (frontend).

### Permissões

**Nota**: Isso pode ser ocultado por um usuário com permissões
administrativas em [Artigo:
Opções](https://docs.joomla.org/Help4.x:Articles:_Options/pt-br "Help4.x:Articles: Options/pt-br").  
É aqui que você pode inserir as permissões para este artigo. [Aprender
mais](https://docs.joomla.org/J3.x:Access_Control_List_Tutorial/pt-br#hierarchylevels "J3.x:Access Control List Tutorial/pt-br").

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-screenshot-article-edit-permissions-pt-br.png"
class="new"
title="File:Help-4x-screenshot-article-edit-permissions-pt-br.png">600px</a>

Para alterar as permissões deste artigo, faça o seguinte.

1.  Selecione o **grupo** acionando o (clicando em) seu título
    localizado à esquerda.
2.  Encontre a **ação** desejada.
    - **Excluir**. Os usuários podem excluir este artigo.
    - **Editar**. Os usuários podem editar este artigo.
    - **Editar estado**. O usuário pode alterar o estado da publicação e
      as informações relacionadas a este artigo.
3.  Selecione a permissão desejada para a ação que deseja alterar.
    - **Herdado**. Herdado para usuários neste grupo a partir das
      [configurações
      globais](https://docs.joomla.org/Help4.x:Site_Global_Configuration/pt-br#permissions "Help4.x:Site Global Configuration/pt-br"),
      [Opções de
      artigos](https://docs.joomla.org/Help4.x:Articles:_Options/pt-br#permissions "Help4.x:Articles: Options/pt-br"),
      ou da [categoria para
      artigos](https://docs.joomla.org/Help4.x:Articles:_Edit_Category/pt-br#permissions "Help4.x:Articles: Edit Category/pt-br").
    - **Permitido**. Permitido para os usuários neste grupo.Nota: Se
      esta ação for negada em um dos níveis mais altos, a permissão
      permitida aqui não terá efeito. Uma configuração negada não pode
      ser substituída.
    - **Negado**. Negado para os usuários neste grupo.
4.  Acione (clique em) **Salvar** na **barra das ferramentas** na parte
    superior. Quando a tela for atualizada, a coluna "Configuração
    calculada" mostrará a permissão efetiva para este grupo e ação.

## Barra das ferramentas

No topo da página você verá a barra das ferramentas mostrada na [captura
de tela](#screenshot) acima.

- **Salvar**. Salva o artigo e permanece na tela atual.
- **Salvar e fechar**. Salva o artigo e fecha a tela atual.
  - **Salvar e novo**. Salva o artigo e mantém a tela de edição aberta e
    pronta para criar outro artigo.
  - **Salvar no menu**. Salva o artigo em um item dos menus e abre a
    tela do item dos menus.
  - **Salvar como cópia**. Salva suas alterações em uma cópia do artigo
    atual. Não afeta o artigo atual.
- **Fechar**. Fecha a tela atual e retorna à tela anterior sem salvar
  nenhuma modificação que você possa ter feito.
- **Versões**. Abre a janela "Histórico das versõe do artigo" para
  mostrar as versões anteriores deste artigo. Isso permite que você
  visualize as versões mais antigas deste artigo e, se desejar, restaure
  a partir de uma das versões mais antigas. [Aprender
  mais](https://docs.joomla.org/Help4.x:Components_Version_History/pt-br "Help4.x:Components Version History/pt-br").
- **Prévia**. Abre uma caixa de diálogo modal mostrando uma visualização
  deste artigo no site. Requer [sessões
  compartilhadas](https://docs.joomla.org/Help4.x:Site_Global_Configuration/pt-br#sharedsessions "Help4.x:Site Global Configuration/pt-br")
  ou uma sessão iniciada no site (front-end).
- **Verificação de acessibilidade**. Abre uma janela que mostra os
  resultados da verificação de acessibilidade do artigo.
- **Associações**. Com uma linguagem específica definida para um artigo,
  permite a edição lado a lado em outra linguagem. Este ícone é mostrado
  apenas em [sites
  multilíngues](https://docs.joomla.org/Help4.x:Multilingual_Associations/pt-br "Help4.x:Multilingual Associations/pt-br").
- **Alternar ajuda incorporada**. Mostra o texto de ajuda em baixo de
  algumas opções.
- **Ajuda**. Abre esta tela de ajuda.

## Dicas rápidas

- Existem 2 métodos para inserir uma imagem no artigo usando o editor
  TinyMCE.
  1.  A lista suspensa do [conteúdo do
      S.G.C.](https://docs.joomla.org/Help4.x:Editors/pt-br#cmscontent "Help4.x:Editors/pt-br")
      fornece acesso à [tela de
      mídia](https://docs.joomla.org/Help4.x:Media/pt-br "Help4.x:Media/pt-br")
      que permite procurar arquivos de imagens e fazer o envio
      (carregamento, upload) das mesmas.
  2.  A lista suspensa "Inserir" é um formulário simples para o qual
      você precisa saber o URL da imagem. É usado para imagens externas.
- As quebras "[Ler
  mais](https://docs.joomla.org/Help4.x:Editors/pt-br#readmore "Help4.x:Editors/pt-br")"
  permitem que você economize espaço na página inicial ou em qualquer
  página com disposição para blogs mostrando apenas a primeira parte de
  um artigo. A [quebras de
  páginas](https://docs.joomla.org/Help4.x:Editors/pt-br#pagebreak "Help4.x:Editors/pt-br")
  permitem que você forneça navegação em várias páginas para artigos
  longos. Você pode usar ambos em um artigo, se desejar.Por exemplo,
  você pode colocar uma quebra "Ler mais" após o primeiro parágrafo de
  um artigo de várias páginas e ter quebras de página após cada página.
  Nenhuma navegação de página seria mostrada na página inicial até que o
  usuário selecionasse o link "Ler mais". Naquela época, o sumário do
  artigo mostrava links para todas as páginas.

## Informações relacionadas

- Este
  [portal](https://docs.joomla.org/Portal:Joomla_4/pt-br "Portal:Joomla 4/pt-br")
  reúne informações relacionadas especificamente ao Joomla! 4.

|                                                                                                                                              |                                                                                                                                                                                                                |
|----------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Telas de ajuda relacionadas                                                                                                                  | Descrição                                                                                                                                                                                                      |
| [Artigos: Opções](https://docs.joomla.org/Help4.x:Articles:_Options/pt-br "Help4.x:Articles: Options/pt-br")                                 | Usado para definir os padrões globais para os itens dos menus que mostram artigos. Esses valores padrões serão usados quando "Usar global" for selecionado para uma opção em um item dos menus para artigos.   |
| <a                                                                                                                                           
 href="https://docs.joomla.org/index.php?title=Help4.x:Articles/pt-br&amp;action=edit&amp;redlink=1"                                           
 class="new"                                                                                                                                   
 title="Help4.x:Articles/pt-br (page does not exist)">Artigos</a>                                                                              | A lista para artigos é usada para localizar, marcar como destacados, adicionar e editar artigos.                                                                                                               |
| <span class="mw-selflink selflink">Artigos: Editar</span>                                                                                    | É aqui que você pode adicionar e editar artigos. Você também pode selecionar a categoria de um artigo, indicar se ela está ou não está publicada e se está selecionada para aparecer na página inicial.        |
| [Artigos: Destacados](https://docs.joomla.org/Help4.x:Articles:_Featured/pt-br "Help4.x:Articles: Featured/pt-br")                           | Usado para controlar quais "artigos destacados" são mostrados na página inicial e em que ordem eles são mostrados.                                                                                             |
| <a                                                                                                                                           
 href="https://docs.joomla.org/index.php?title=Help4.x:Articles:_Categories/pt-br&amp;action=edit&amp;redlink=1"                               
 class="new"                                                                                                                                   
 title="Help4.x:Articles: Categories/pt-br (page does not exist)">Artigos:                                                                     
 Categorias</a>                                                                                                                                | categorias.                                                                                                                                                                                                    |
| [Menus: Artigos arquivados](https://docs.joomla.org/Help4.x:Menu_Item:_Article_Archived/pt-br "Help4.x:Menu Item: Article Archived/pt-br")   | Mostra uma lista personalizada de artigos classificados por datas ou títulos. Os artigos arquivados não são mais publicados, mas ainda são armazenados no site.                                                |
| <a                                                                                                                                           
 href="https://docs.joomla.org/index.php?title=Help4.x:Menu_Item:_Category_Blog/pt-be&amp;action=edit&amp;redlink=1"                           
 class="new"                                                                                                                                   
 title="Help4.x:Menu Item: Category Blog/pt-be (page does not exist)">Menus:                                                                   
 Blog para categoria</a>                                                                                                                       | Usado para mostrar artigos pertencentes a uma categoria específica em uma disposição para blogs. Controla os principais artigos, os artigos introdutórios e os links adicionais para mais artigos.             |
| <a                                                                                                                                           
 href="https://docs.joomla.org/index.php?title=Help4.x:Menu_Item:_Category_List/pt-br&amp;action=edit&amp;redlink=1"                           
 class="new"                                                                                                                                   
 title="Help4.x:Menu Item: Category List/pt-br (page does not exist)">Menus:                                                                   
 Lista para categoria</a>                                                                                                                      | Usado para mostrar artigos pertencentes a uma categoria específica em uma disposição para lista.                                                                                                               |
| [Menus: Criar artigo](https://docs.joomla.org/Help4.x:Menu_Item:_Create_Article/pt-br "Help4.x:Menu Item: Create Article/pt-br")             | Permite que os usuários enviem um artigo. Normalmente, isso está disponível apenas para usuários que iniciaram suas sessões no site (frontend). Os usuários devem ter permissão para criar artigos.            |
| [Menus: Artigos destacados](https://docs.joomla.org/Help4.x:Menu_Item:_Featured_Articles/pt-br "Help4.x:Menu Item: Featured Articles/pt-br") | Usado para mostrar todos os artigos que foram marcados como destacados. Os artigos são mostrados em uma disposição para blog.                                                                                  |
| <a                                                                                                                                           
 href="https://docs.joomla.org/index.php?title=Help4.x:Menu_Item:_List_All_Categories/pt-br&amp;action=edit&amp;redlink=1"                     
 class="new"                                                                                                                                   
 title="Help4.x:Menu Item: List All Categories/pt-br (page does not exist)">Menus:                                                             
 Listar todas as categorias em uma árvore de categorias para artigos</a>                                                                       | Usado para mostrar uma lista hierárquica de categorias. Dependendo das opções selecionadas para esta disposição, você pode acionar (clicar em) um título de categoria para mostrar os artigos dessa categoria. |
| [Menus: Artigo único](https://docs.joomla.org/Help4.x:Menu_Item:_Single_Article/pt-br "Help4.x:Menu Item: Single Article/pt-br")             | Usado para mostrar um artigo.                                                                                                                                                                                  |
