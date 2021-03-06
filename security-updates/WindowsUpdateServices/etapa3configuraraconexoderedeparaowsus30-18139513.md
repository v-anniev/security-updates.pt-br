---
TOCTitle: 'Etapa 3: Configurar a conexão de rede para o WSUS 3.0'
Title: 'Etapa 3: Configurar a conexão de rede para o WSUS 3.0'
ms:assetid: 'dbc9d9f7-cf52-4539-9f9e-3e823273218a'
ms:contentKeyID: 18139513
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc708602(v=WS.10)'
---

Etapa 3: Configurar a conexão de rede para o WSUS 3.0
=====================================================

Após a instalação do WSUS 3.0, o assistente de configuração será iniciado automaticamente. Você também pode executá-lo mais tarde, por meio da página **Opções** do console do WSUS 3.0.

Antes de iniciar o processo de configuração, assegure-se de que você saiba as respostas para as seguintes questões:

1. O firewall do servidor está configurado para permitir que os clientes acessem o servidor?

2. Esse computador pode se conectar ao servidor upstream (como o Microsoft Update)?

3. Você tem o nome do servidor proxy e as credenciais do usuário para o servidor proxy, se necessário?

Por padrão, o WSUS é configurado para usar o Microsoft Update como o local a partir do qual obter as atualizações. Se você tiver um servidor proxy na rede, configure o WSUS para usar o servidor proxy. Se houver um firewall corporativo entre o WSUS e a Internet, talvez seja necessário configurar o firewall para garantir que o WSUS possa obter as atualizações.

| ![](images/Cc708602.note(WS.10).gif)Observação                                                                                                                               |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Embora seja preciso ter conexão com a Internet para baixar as atualizações do Microsoft Update, o WSUS oferece um recurso para importar as atualizações para redes que não estejam conectadas à Internet. |

**A Etapa 3 contém os seguintes procedimentos**:

-   Configurar o firewall.
-   Especificar a maneira como o servidor obterá atualizações (a partir do Microsoft Update ou de outro servidor do WSUS).
-   Configurar o servidor proxy para que o WSUS possa obter as atualizações.

**Para configurar o firewall**
-   Se houver um firewall corporativo entre o WSUS e a Internet, talvez seja necessário configurar o firewall para garantir que o WSUS possa obter as atualizações. Para obter as atualizações do Microsoft Update, o servidor do WSUS usa a porta 80 para o protocolo HTTP e a porta 443 para o protocolo HTTPS. Essas opções não são configuráveis.

-   Se a sua organização não permitir que a porta 80 ou a porta 443 fique aberta para todos os endereços, você pode restringir o acesso apenas aos seguintes domínios para que o WSUS e as Atualizações Automáticas possam se comunicar com o Microsoft Update:

    -   http://windowsupdate.microsoft.com
    -   http://\*.windowsupdate.microsoft.com
    -   https://\*.windowsupdate.microsoft.com
    -   http://\*.update.microsoft.com
    -   https://\*.update.microsoft.com
    -   http://\*.windowsupdate.com
    -   http://download.windowsupdate.com
    -   http://download.microsoft.com
    -   http://\*.download.windowsupdate.com
    -   http://wustat.windows.com
    -   http://ntservicepack.microsoft.com

| ![](images/Cc708602.note(WS.10).gif)Observação                                                                                                                                                                 |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| As instruções para configurar o firewall destinam-se a um firewall corporativo posicionado entre o WSUS e a Internet. Como o WSUS inicia todo o seu tráfego de rede, não é necessário configurar o Firewall do Windows no servidor do WSUS. |

Embora a conexão entre o Microsoft Update e o WSUS exija que as portas 80 e 443 estejam abertas, você pode configurar vários servidores do WSUS para sincronização com uma porta personalizada.

Os dois procedimentos seguintes supõem que você esteja usando o assistente de configuração. Em uma seção posterior, você aprenderá como iniciar o snap-in de Administração do WSUS e configurar o servidor na página **Opções**.

**Para especificar a maneira como o servidor obterá atualizações**
1.  No assistente de configuração, após ingressar no Programa de Aperfeiçoamento da Microsoft, clique em **Avançar** para escolher o servidor upstream.

2.  Se você optar por sincronizar a partir do Microsoft Update, terá terminado com esta página. Clique em **Avançar** ou selecione **Especificar Servidor Proxy** no painel esquerdo.

3.  Se você optar pela sincronização a partir de outro servidor do WSUS, especifique o nome do servidor e a porta na qual esse servidor se comunicará com o servidor upstream.

4.  Para usar SSL, marque a caixa de seleção **Usar SSL ao sincronizar informações de atualização**. Nesse caso, os servidores usarão a porta 443 para sincronização. (Você deve verificar se tanto esse servidor como o servidor upstream dão suporte a SSL.)

5.  Se esse for um servidor de réplica, marque a caixa de seleção **Esta é uma réplica do servidor upstream**.

6.  Neste ponto, a configuração do servidor upstream estará concluída. Clique em **Avançar** ou selecione **Especificar servidor proxy** no painel esquerdo.

**Para definir configurações do servidor proxy**
1.  Na página **Especificar Servidor Proxy** do assistente de configuração, marque a caixa de seleção **Usar um servidor proxy ao sincronizar** e digite o nome do servidor proxy e o número da porta (porta 80 por padrão) nas caixas correspondentes.

2.  Se você desejar se conectar ao servidor proxy com credenciais de usuário específicas, marque a caixa de seleção **Utilizar credenciais de usuário para se conectar ao servidor proxy** e digite o nome de usuário, o domínio e senha do usuário nas caixas correspondentes. Se quiser habilitar a autenticação básica para o usuário que se conectar ao servidor proxy, marque a caixa de seleção **Permitir autenticação básica (a senha é enviada em texto não criptografado)**.

3.  Neste ponto, a configuração do servidor proxy estará concluída. Clique em **Avançar** para seguir para a próxima página, onde é possível iniciar a configuração do processo de sincronização.

Os dois procedimentos seguintes supõem que você esteja usando o snap-in de Administração do WSUS para configuração. Estes dois procedimentos mostram como iniciar o snap-in de Administração do WSUS e configurar o servidor na página **Opções**.

**Para iniciar o console de administração do WSUS**
-   Para iniciar o console de administração do WSUS, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Ferramentas Administrativas** e clique em **Microsoft Windows Server Update Services 3.0**.

| ![](images/Cc708602.note(WS.10).gif)Observação                                                                                                                                                                                                                                      |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Para usar todos os recursos do console do WSUS, você deve ser membro dos grupos de segurança Administradores do WSUS ou Administradores locais no servidor no qual o WSUS está instalado. No entanto, os membros do grupo de segurança Relatores do WSUS têm acesso somente leitura ao console de administração. |

**Para especificar uma origem da atualização e o servidor proxy**
1.  No console do WSUS, clique em **Opções** no painel esquerdo sob o nome do servidor e clique em **Origem da Atualização e Servidor Proxy** no painel central.

2.  Uma caixa de diálogo será exibida com as guias **Origem da Atualização** e **Servidor Proxy**.

3.  Na guia **Origem da Atualização**, selecione o local a partir do qual esse servidor obterá atualizações. Se você optar por sincronizar a partir do Microsoft Update (o padrão), terá terminado com esta página do assistente.

4.  Se você optar por sincronizar a partir de outro servidor do WSUS, será necessário especificar a porta para a comunicação entre os servidores (o padrão é a porta 80). Se escolher uma porta diferente, verifique se ambos os servidores podem usar essa porta.

5.  Você também pode especificar se o SSL deve ser usado ao sincronizar a partir do servidor upstream do WSUS. Nesse caso, os servidores usarão a porta 443 para sincronização a partir do servidor upstream.

6.  Se esse servidor for uma réplica do segundo servidor do WSUS, marque a caixa de seleção **Esta é uma réplica do servidor upstream**. Nesse caso, todas as atualizações devem ser aprovadas somente no servidor upstream do WSUS.

7.  Na guia **Servidor proxy**, marque a caixa de seleção **Usar um servidor proxy ao sincronizar** e digite o nome e o número da porta (porta 80 por padrão) do servidor proxy nas caixas correspondentes.

8.  Se você desejar se conectar ao servidor proxy com credenciais de usuário específicas, marque a caixa de seleção **Utilizar credenciais de usuário para se conectar ao servidor proxy** e digite o nome de usuário, o domínio e senha do usuário nas caixas correspondentes. Se quiser habilitar a autenticação básica para o usuário que se conectar ao servidor proxy, marque a caixa de seleção **Permitir autenticação básica (a senha é enviada em texto não criptografado)**.

9.  Clique em **OK** para salvar as configurações.
