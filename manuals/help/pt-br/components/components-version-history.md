<!-- Filename: Help4.x:Components_Version_History / Display title: Histórico de versões de componentes -->

## Descrição

A tela "Histórico das versões" permite gerenciar versões anteriores do
item que está sendo editado. O histórico das versões está disponível
para
[artigos](https://docs.joomla.org/Help4.x:Articles:_Edit/pt-br "Help4.x:Articles: Edit/pt-br"),
[banners](https://docs.joomla.org/Help4.x:Banners:_Edit/pt-br "Help4.x:Banners: Edit/pt-br")
e
[clientes](https://docs.joomla.org/Help4.x:Banners:_New_or_Edit_Client/pt-br "Help4.x:Banners: New or Edit Client/pt-br"),
<a
href="https://docs.joomla.org/index.php?title=Help4.x:Contacts:_Edit/pr-br&amp;action=edit&amp;redlink=1"
class="new"
title="Help4.x:Contacts: Edit/pr-br (page does not exist)">contatos</a>,
<a
href="https://docs.joomla.org/index.php?title=Help4.x:News_Feeds:_Edit/pt-br&amp;action=edit&amp;redlink=1"
class="new"
title="Help4.x:News Feeds: Edit/pt-br (page does not exist)">feeds para
notícias</a>, [notas dos
usuários](https://docs.joomla.org/Help4.x:User_Notes:_New_or_Edit/pt-br "Help4.x:User Notes: New or Edit/pt-br")
e todas as categorias.

Cada vez que você salva o item com novas alterações, uma nova versão é
criada automaticamente. Você pode controlar quantas versões manter para
cada item nas opções do componente. Você também pode optar por manter
uma ou mais versões para sempre. Se assim for marcado, essas versões não
serão excluídas automaticamente, mesmo que você exceda o número máximo
de versões inseridas nas opções.

Nota: Se você usa versionamento, os [campos
personalizados](https://docs.joomla.org/J3.x:Adding_custom_fields/pt-br "J3.x:Adding custom fields/pt-br")
não são armazenados em versões diferentes.

## Como acessar

Clique no botão **Versões** na barra de ferramentas enquanto edita o
item.

## Captura da tela

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Components-Version-History-screen-pt-br.png"
class="new"
title="File:Help-4x-Components-Version-History-screen-pt-br.png">600px</a>

## Cabeçalhos das colunas

- **Caixa de seleção**: Marque esta caixa para selecionar um ou mais
  itens. Para selecionar todos os itens, marque a caixa no cabeçalho da
  coluna. Depois que as caixas forem marcadas, clique em um botão da
  barra de ferramentas para executar uma ação nos itens selecionados.
- **Data**: A hora e a data em que a versão foi salva. Clicar neste link
  abre a visualização dessa versão em uma janela pop-up. Observe que uma
  das datas será seguida por um símbolo de estrela. Isso indica que esta
  é a versão que está atualmente salva e sendo editada.
- **Nota de versão**: Ao editar um item, você tem a opção de inserir uma
  nota de versão. Isso pode ser usado para ajudá-lo a lembrar qual
  versão possui quais informações. Se você inseriu uma nota de versão
  antes de salvar o item, ela será exibida nesta coluna.
- **Manter para sempre**: Esta coluna mostra se você marcou a opção
  "Manter para sempre" na versão. Normalmente, cada versão será mantida
  de acordo com as configurações na tela de opções do componente. As
  configurações padrões são predefinidas para manter no máximo 10
  versões anteriores para um item. Nesse caso, quando você salva um item
  que já possui 10 versões salvas, a versão mais antiga é excluída. Se
  opção "Manter para sempre" for marcada em uma versão, essa versão não
  será contada como uma das versões salvas e não será excluída quando o
  número máximo for atingido.Para ativar ou desativar a opção "manter
  para sempre", marque a caixa de seleção da versão e clique no botão
  "Manter ativado/desativado" na barra de ferramentas.
- **Autor**: O usuário que salvou esta versão.
- **Contador de caracteres**: O total de caracteres salvos nesta versão.
  Observe que isso inclui os nomes das colunas do banco de dados, bem
  como os caracteres reais digitados.

## Barra de ferramentas

No topo da página você verá a barra de ferramentas mostrada na [captura
de tela](#screenshot) acima. As funções são:

- **Restaurar**: A versão atual do item é marcada com uma estrela à
  direita da data. Se você deseja restaurar uma das outras versões
  salvas, marque a caixa de seleção da versão desejada e clique no botão
  "Restaurar". A versão atual do item será substituída pela versão
  selecionada e a tela de edição será recarregada com a versão
  restaurada carregada no editor.
- **Pré-visualização**: Para pré-visualizar uma versão, clique na coluna
  "Data" da versão desejada ou marque a caixa de seleção e clique no
  botão "Pré-visualizar". Uma janela separada do navegador será
  carregada mostrando a versão selecionada do item, semelhante à captura
  de tela abaixo. <a
  href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Version-History-Help-preview-pt-br.png"
  class="new"
  title="File:Help-4x-Version-History-Help-preview-pt-br.png">600px</a>
  Quando terminar de visualizar a versão, feche a janela do navegador.
- **Comparar**: Para comparar duas versões para ver o que foi alterado,
  clique nas caixas de seleção de cada uma das versões e clique no botão
  "Comparar". Uma nova janela do navegador será aberta, conforme
  mostrado na captura de tela abaixo. <a
  href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Version-History-Help-compare-pt-br.png"
  class="new"
  title="File:Help-4x-Version-History-Help-compare-pt-br.png">600px</a>
  A primeira coluna é o nome do campo, a segunda é a versão mais antiga,
  a terceira é a versão mais recente e a última coluna destaca as
  diferenças entre as duas versões.
- **Manter ligado/desligado**: Este botão permite ativar ou desativar o
  recurso "Manter para sempre" para uma versão. Normalmente, a versão
  mais antiga de um item é excluída automaticamente quando o número
  máximo de versões (definido nas opções do componente) for excedido. Se
  você definir a propriedade "Manter para sempre" para uma versão, ela
  nunca será excluída automaticamente.
- **Excluir**: Este botão permite excluir manualmente uma ou mais
  versões. Marque a caixa de seleção das versões que deseja excluir e
  clique no botão "Excluir". Observe que isso *não* exclui o item que
  está sendo editado. Ele apenas exclui o histórico de versões do item.

## Informações relacionadas

Para definir as opções do histórico de versões, clique no botão "Opções"
do componente desejado.
