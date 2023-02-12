<!-- Filename: Help4.x:Languages:_Edit_Override / Display title: Substituição de Edição do Gestor de Idiomas das Extensões -->

## Descrição

A «Substituição» permite-lhe alterar uma entrada principal do Joomla.

No código do Joomla, as entradas de texto que são para aparecer na
«Interface do Utilizador», na interface do «Site» ou na interface do
«Administrador», são expressas como constantes de entrada. Por exemplo,
a entrada "Por favor, inicie a sessão para ver o artigo" é expressa como
*COM_CONTENT_ERROR_LOGIN_TO_VIEW_ARTICLE*. A entrada do texto pode ser
traduzida para qualquer idioma. O idioma predefinido é inglês Britânico.
Existem centenas de tais entradas numa instalação do Joomla.

Se uma entrada não se adequar ao seu *site*, poderá utilizar a
funcionalidade «Substituição de Idioma» para substituir o original.

## Como Aceder

- Selecione **Sistema **→** Painel de Gestão **→** Substituição de
  Idioma**. Depois...
  - Selecione um **Idioma e Cliente** na lista suspensa. Depois...
    - Clique no botão **Novo** na «Barra de Ferramentas» para criar uma
      nova substituição. Ou...
    - Selecione a hiperligação constante na coluna **Constante** para
      editar uma substituição existente.

## Captura de Ecrã

<img
src="https://docs.joomla.org/images/thumb/0/01/Help-4x-Extensions-Language-Manager-Overrides-Edit-screen-en.png/800px-Help-4x-Extensions-Language-Manager-Overrides-Edit-screen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/0/01/Help-4x-Extensions-Language-Manager-Overrides-Edit-screen-en.png 1.5x"
data-file-width="1151" data-file-height="927" width="800" height="644"
alt="Help-4x-Extensions-Language-Manager-Overrides-Edit-screen-en.png" />

## Dos Campos

**Right Panel: Search text you want to change**

- **Search For.** Start here! You are more likely to know the Value
  (expired) than the Constant (\_EXPIRED). In either case, the search is
  a case insensitive for the partial string.
- **Search Text.** Enter the text to search for and select the
  **Search** button.
- **Search Results.** A list of strings containing the search term
  appears in a separate panel. Select the one you are looking for. The
  constant and text will be copied into the **Create a New Override**
  panel, labelled **Edit this Override** if you editing an existing
  override.

**Left Panel: Create a New Override or Edit this Override**

- **Language Constant.** This is the strings used in the code by the
  developer. If the value does not exist in the code the string will
  never be used.
- **Text.** This is where you override the default term with your
  version.
- **File.** This shows where the override file is located in the file
  system. You might need to know this for trouble-shooting.

## Barra de Ferramentas

Próximo do topo da página irá ver a barra de filtro mostrada na «Captura
de Ecrã» acima. As funções são:

- **Guardar**. Guarda o item e fica no ecrã atual.

<!-- -->

- 

**Save & Close**. Saves the item and closes the current screen.

- **Guardar e Novo**. Guarda o item e mantém o ecrã de edição aberto e
  pronto para criar outro item.

<!-- -->

- **Cancelar**. Fecha o ecrã atual e volta para o ecrã anterior sem
  guardar quaisquer modificações que tenham sido efetuadas. Ou

<!-- -->

- **Fechar**. Fecha o ecrã atual e volta ao ecrã anterior sem guardar
  quaisquer modificações que tenham sido efetuadas. This toolbar icon is
  not shown if you are creating a new item.

<!-- -->

- **Ajuda**. Abre este ecrã de ajuda.
