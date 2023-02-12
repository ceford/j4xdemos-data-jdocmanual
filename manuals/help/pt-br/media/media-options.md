<!-- Filename: Help4.x:Media:_Options / Display title: Ajuda4.x:Mídia: Opções -->

## Descrição

As configurações das opções para mídia permitem a configuração dos
parâmetros usados globalmente para mídia. Controle os tipos de arquivo
permitidos para envio, verificação do tipo das MIME, lista negra para
tipo das MIME e mais opções.

## Como acessar

**CConteúdo **→** Mídia**

- acione o (clique no) botão **Opções** na barra das ferramentas

## Captura da tela

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Media-Options-screen-pt-br.png"
class="new"
title="File:Help-4x-Media-Options-screen-pt-br.png">800px</a>

## Campos do formulário

### Mídia

- **Tamanho máximo (em MB)**. Use zero para nenhum limite. Nota: O
  servidor tem um limite máximo.
- **Caminho para a pasta dos arquivos**. Insira o caminho para a pasta
  dos arquivos em relação à raiz do seu espaço web.Mudar para um caminho
  diferente do padrão "images" talvez quebre seus links. Não inicie o
  caminho com uma barra.
- **Caminho para a pasta das imagens**. Insira o caminho para a pasta
  das imagens em relação à raiz do seu espaço web.Este caminho deve ser
  igual ao caminho para os arquivos (padrão) ou para uma subpasta do
  caminho para a pasta dos arquivos. Não inicie o caminho com uma barra.
- **Restringir envios**. Restringe os envios, das imagens, para usuários
  inferiores a gerentes se 'Fileinfo' ou 'MIME Magic' não estiverem
  instalados.
  - **Extensões permitidas**. Restringe os envios, dos arquivos da
    lista, para usuários inferiores a gerentes.
  - **Verificar os tipos das MIME**. Usa 'Fileinfo' ou 'MIME Magic' para
    tentar verificar os arquivos. Tente desabilitar isso se você receber
    erros relacionados aos tipos das MIME inválidos.
- **Legal Image Extensions (File Types)**. Extensões das imagem (tipos
  dos arquivo) que você tem permissão para enviar (separadas por
  vírgula). Elas são usadas para verificar se há cabeçalhos para imagens
  válidos.
- **Legal Audio Extensions (File Types)**. Extensões para áudios (tipos
  dos arquivo) que você tem permissão para enviar (separadas por
  vírgulas). Elas são usadas para verificar se há cabeçalhos para áudios
  válidos.
- **Legal Video Extensions (File Types)**. Extensões para vídeos (tipos
  dos arquivo) que você tem permissão para enviar (separadas por
  vírgula). Elas são usadas para verificar se há cabeçalhos para vídeos
  válidos.
- **Legal Document Extensions (File Types)**. Extensões para documentos
  (tipos dos arquivo) que você tem permissão para enviar (separadas por
  vírgulas). Elas são usadas para verificar os cabeçalhos para
  documentos válidos.
- **Extensões ignoradas**. Extensões para arquivos ignoradas na
  verificação dos tipos das MIME e dos envios restritos.
- **Tipos das MIME legais.** Uma lista separada por vírgulas dos tipos
  das MIME legais para envio.

### Permissões

Esta seção permite configurar as permissões padrõed da [lista para
controle do
acesso](https://docs.joomla.org/Access_Control_List/pt-br "Access Control List/pt-br")
para todas as mídias.

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-Media-Options-permissions-subscreen-pt-br.png"
class="new"
title="File:Help-4x-Media-Options-permissions-subscreen-pt-br.png">600px</a>

Para alterar as permissões para mídia, faça o seguinte:

1.  Selecione o **grupo** clicando em seu título localizado à esquerda.
2.  Encontre a **ação** desejada.
    - **Configurar ACL e opções**: Os usuários podem editar as opções e
      as permissões.
    - **Configurar apenas as opções**: Os usuários podem editar as
      opções, exceto as permissões.
    - **Acessar a interface administrativa**: Os usuários podem acessar
      a interface administrativa do usuário.
    - **Criar**: Os usuários podem criar mídia.
    - **Excluir**: Os usuários podem excluir a mídia.
    - **Editar**: Os usuários podem editar a mídia.
3.  Selecione a permissão desejada para a ação que deseja alterar.
    - **Herdado**: Herdado, para usuários neste grupo, das permissões
      nas [configurações
      globais](https://docs.joomla.org/Help4.x:Site_Global_Configuration/pt-br#permissions "Help4.x:Site Global Configuration/pt-br").
    - **Permitido**: Permitido para usuários neste grupo. Observação: Se
      esta ação for negada em um dos níveis mais altos, a permissão
      permitida aqui não terá efeito. Uma configuração negada não pode
      ser substituída.
    - **Negado**: Negado para usuários neste grupo.
4.  Acione (clique em) **Salvar** na **barra dad ferramentas** na parte
    superior. Quando a tela for atualizada, a coluna "Configuração
    calculada" mostrará a permissão efetiva para este grupo e ação.

## Barra das ferramentas

No topo da página você verá a barra das ferramentas mostrada na [captura
da tela](#screenshot) acima.

- **Salvar**: Salva as opções para mídia e permanece na tela atual.
- **Salvar e fechar**: Salva as opções para mídia e fecha a tela atual.
- **Fechar**: Fecha a tela atual e retorna à tela anterior sem salvar
  nenhuma modificação que tenha sido feita.
- **Alternar ajuda embutida**: Mostra o texto da ajuda abaixo de algumas
  opções.
- **Ajuda**: Abre esta tela de ajuda.

## Dicas rápidas

- Se você é um usuário iniciante, pode apenas manter os valores padrões
  aqui até aprender mais sobre como usar as opções globais.
- Se você é um usuário avançado, pode economizar tempo criando bons
  valores padrões aqui.

## Informação relacionada

- Tela de ajuda relacionada:
  [Mídia](https://docs.joomla.org/Help4.x:Media/pt-br "Help4.x:Media/pt-br").
- Tutorial: [Gerenciando
  mídia](https://docs.joomla.org/J4.x:Managing_Media/pt-br "J4.x:Managing Media/pt-br").
