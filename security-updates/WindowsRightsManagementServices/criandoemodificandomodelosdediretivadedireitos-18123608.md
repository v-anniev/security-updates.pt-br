---
TOCTitle: Criando e modificando modelos de diretiva de direitos
Title: Criando e modificando modelos de diretiva de direitos
ms:assetid: '6014176f-ef71-4d29-b3e3-da129c18563d'
ms:contentKeyID: 18123608
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720281(v=WS.10)'
---

Criando e modificando modelos de diretiva de direitos
=====================================================

Ao adicionar ou editar um modelo de diretiva de direitos, você pode definir os seguintes elementos.

-   **Nome e descrição do modelo de diretiva de direitos**. Opcionalmente, é possível fornecer um endereço de email para o qual os usuários podem solicitar mais direitos além dos que os modelos concedem.
-   **Usuários e grupos que têm permissão para adquirir licenças de uso para conteúdo publicado usando este modelo de diretiva de direitos.** Para especificar que qualquer usuário pode adquirir uma licença de uso para conteúdo protegido, use o grupo **Qualquer Pessoa**, que é um grupo especial reconhecido pelo RMS. Para adicionar esse grupo especial ao seu modelo, na página **Configurações do Modelo de diretiva de direitos**, digite a palavra **Qualquer Pessoa** no campo **Adicionar** e clique no botão **Adicionar usuários ou grupo**.
-   **Direitos concedidos a cada usuário ou grupo.** Alguns direitos são automaticamente selecionados devido a interdependências de direitos específicos. Por exemplo, se você selecionar o direito **Editar**, os direitos **Exibir** e **Salvar** também serão selecionados. Para obter informações sobre como os direitos listados correspondem aos direitos definidos no vocabulário XrML, consulte a seção sobre [XrML e direitos no RMS](https://technet.microsoft.com/7eb5cdd1-cd48-4b2b-96b6-fc74f7b42e7f), mais adiante neste tópico.
-   **Diretiva de vencimento para conteúdo publicado usando esse modelo de diretiva de direitos.** Por padrão, o conteúdo nunca expira. Isso significa que os usuários podem adquirir licenças de uso a qualquer momento. Você pode escolher uma das seguintes opções de diretiva de vencimento:
    -   **O conteúdo nunca expira**. Esta é a opção padrão. Quando essa opção estiver selecionada, a licença de uso permitirá ao usuário acessar o conteúdo enquanto ele estiver no computador.
    -   **O conteúdo expira em**. Você pode especificar uma data na qual o conteúdo expira, indicando que a licença de uso concedida expira nessa data e que nenhum usuário pode adquirir uma licença de uso para o conteúdo depois dessa data.
    -   **A licença de conteúdo vence** *n* **dias após a data de publicação**. Você pode especificar o número de dias depois da publicação em que nenhuma licença de uso poderá ser adquirida para o conteúdo.
    -   **As licenças de uso de conteúdo devem ser renovadas a cada:** *n* **dias**. Você especifica que os usuários devem renovar suas licenças de uso depois de um determinado período de tempo ter passado desde a aquisição da licença de uso do conteúdo. Você pode aplicar esta diretiva em conjunto com as diretivas anteriores.
-   **Diretivas estendidas**. Você pode selecionar uma ou mais das seguintes diretivas:
    -   **O autor recebe direitos completos sem vencimento**. Essa diretiva dá ao autor direitos completos e perpétuos. Essa configuração é aplicada mesmo que você tenha especificado que o conteúdo expirará em um determinado tempo.
    -   **O conteúdo protegido pelo RMS pode ser exibido em navegadores confiáveis**. Essa diretiva controla se o conteúdo pode ou não ser exibido em navegadores confiáveis se o aplicativo habilitado para RMS que criou o conteúdo permitir isso. Se você não selecionar essa caixa de seleção, o conteúdo protegido deverá ser exibido usando o aplicativo que o criou.
    -   **Exigir uma nova licença de uso sempre que o conteúdo for acessado**. Essa diretiva controla se os usuários devem ou não adquirir uma nova licença de uso a cada vez que tentarem consumir conteúdo publicado usando esse modelo de diretiva de direitos. Se essa diretiva estiver selecionada, o usuário deverá estar conectado ao servidor do RMS para acessar o conteúdo.

    | ![](images/Cc720281.Caution(WS.10).gif)Cuidado                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
    |-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
    | Tenha cuidado ao habilitar a diretiva **Exigir uma nova licença de uso sempre que o conteúdo for acessado**. Ela exige que os usuários estejam conectados à rede toda vez que consumirem conteúdo publicado usando esse modelo de diretiva de direitos. Se eles não estiverem conectados à rede, não poderão consumir o conteúdo. Se essa configuração não estiver habilitada, os usuários precisarão obter uma licença de uso somente na primeira vez em que tentarem consumir conteúdo. Os usuários podem recusar a licença quando estiverem offline, até que a licença expire. |

-   **Aplicar dados específicos do aplicativo**. Essa diretiva fornece a oportunidade para diretiva personalizada que esteja baseada em condições específicas ao aplicativo habilitado para RMS. Se você selecionar essa caixa de seleção, digite um nome e um par de valores exigidos pelo aplicativo e clique em **Adicionar** para adicioná-los à lista.
-   **Diretiva de revogação para esse modelo de diretiva de direitos**. Você pode especificar se uma lista de revogação é necessária, selecionando **Diretiva de revogação para esse modelo de diretiva de direitos**. Se desejar requerer revogação, você deve criar e manter uma lista de revogação. Para obter mais informações sobre revogação, consulte "[Gerenciando a revogação](https://technet.microsoft.com/df732a7d-1fb0-4845-87ca-fab4bc5f98a0)", já mencionado neste tema.
-   **Lista de revogação para acesso do cliente**. Essa propriedade fornece uma URL para a lista de revogação. É possível disponibilizar a lista de revogação usando um serviço da Web que possa ser acessado usando uma URL. Quando um computador com o cliente do RMS tentar abrir conteúdo protegido por direitos que exija uma lista de revogação, primeiro o aplicativo habilitado para RMS consultará a lista de revogação do computador local; se ela não for encontrada ou se estiver desatualizada, o aplicativo tentará se conectar à URL especificada nas propriedades do modelo. Depois que o cliente do RMS se conecta à URL de revogação, ele verifica se os valores de OBJECT TYPE, ID TYPE e ID sob o elemento ISSUER da lista de revogação correspondem aos valores na licença de uso do RMS. O cliente do RMS também comparará as chaves pública e particular usadas para assinar a lista de revogação. Se um desses valores não coincidir, a lista de revogação será ignorada.
-   **Intervalo de atualização da lista de revogação**. Essa propriedade fornece o número de dias de validade de uma lista de revogação. Se a lista de revogação baixada no computador cliente for mais antiga do que o tempo especificado, uma nova lista será baixada.
-   **Arquivo de chave pública**. Essa propriedade fornece o caminho e o nome do arquivo da chave pública cuja chave particular correspondente é usada para assinar a lista de revogação.