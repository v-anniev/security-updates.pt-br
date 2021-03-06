---
TOCTitle: 'MS16-MAY'
Title: Resumo do Boletim de Segurança da Microsoft de maio de 2016
ms:assetid: 'ms16-may'
ms:contentKeyID: 72979856
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms16-may(v=Security.10)'
---

Modelo do MSRC ppDocument

Resumo do Boletim de Segurança da Microsoft de maio de 2016
===========================================================

Publicado em: 10 de maio de 2016 | Atualizado em: 13 de maio de 2016

**Versão:** 2.0

Este resumo de boletins lista os boletins de segurança lançados em maio de 2016.

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft forem emitidos, visite [Notificações de Segurança Técnica da Microsoft](http://technet.microsoft.com/pt-br/security/dd252948.aspx).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

Sinopse
-------

<span id="sectionToggle0"></span>
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os softwares afetados, consulte a próxima seção, **Softwares afetados**.
<p></p>
<table style="width:100%;border:1px solid black;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>ID do Boletim</strong></td>
<td style="border:1px solid black;"><strong>Título do boletim e Sinopse</strong></td>
<td style="border:1px solid black;"><strong>Classificação Máxima de Severidade<br />
e Impacto da Vulnerabilidade</strong></td>
<td style="border:1px solid black;"><strong>Requisito de reinicialização</strong></td>
<td style="border:1px solid black;"><strong>Problemas<br />
Conhecidos</strong></td>
<td style="border:1px solid black;"><strong>Softwares Afetados</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-051">MS16-051</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (3155533)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Internet Explorer. A vulnerabilidade mais grave pode permitir a execução remota de código se um usuário visualiza uma página da Web especialmente criada usando o Internet Explorer. O atacante que explorar com êxito as vulnerabilidades poderá ganhar os mesmos direitos de usuário que o usuário em questão. Se o usuário atual estiver conectado com direitos de usuário administrativo, um atacante poderá assumir o controle do sistema afetado. O atacante poderia instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-052">MS16-052</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa do Microsoft Edge (3155538)<br />
</strong>Esta atualização de segurança elimina vulnerabilidades no Microsoft Edge. A vulnerabilidade mais grave pode permitir a execução remota de código se um usuário visualizar uma página da Web criada especialmente usando o Microsoft Edge. O atacante que explorar com êxito as vulnerabilidades poderá ganhar os mesmos direitos de usuário que o usuário em questão. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema podem correr menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-053">MS16-053</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para JScript e VBScript (3156764)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades nos mecanismos de script do JScript e VBScript no Microsoft Windows. As vulnerabilidades podem permitir a execução remota de código se um usuário visita um site especialmente criado. O atacante que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Se um usuário atual tiver feito logon com direitos administrativos, o atacante que explorar com êxito essas vulnerabilidades poderá obter o controle total do sistema afetado. O atacante poderia instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-054">MS16-054</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Microsoft Office (3155544)<br />
</strong>Esta atualização de segurança elimina vulnerabilidades no Microsoft Office. As vulnerabilidades podem permitir a execução remota de código se um usuário abrir um arquivo do Microsoft Office especialmente criado. Um atacante que tenha conseguido explorar as vulnerabilidades pode executar um código arbitrário no contexto do usuário atual. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Office Services e Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-055">MS16-055</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o componente gráfico da Microsoft (3156754)<br />
</strong>Esta atualização de segurança elimina vulnerabilidades no Microsoft Windows. A vulnerabilidade mais grave pode permitir a execução remota de código se um usuário abre um documento ou visita um site especialmente criado. Os usuários cujas contas estão configuradas para ter menos direitos de usuário podem ser menos afetados do que os usuários que têm direitos de administrador.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-056">MS16-056</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança do Diário do Windows (3156761)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um usuário abre um arquivo de diário especialmente criado. Os usuários cujas contas estão configuradas para ter menos direitos de usuário podem ser menos afetados do que os usuários que têm direitos de administrador.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-057">MS16-057</a></td>
<td style="border:1px solid black;"><strong>Atualizações de segurança para o Windows Shell (3156987)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir execução remota de código se um atacante convence com êxito um usuário a navegar em um site especialmente criado que aceite conteúdo online fornecido pelo usuário ou a abrir um site com conteúdo especialmente criado. O atacante que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os usuários cujas contas estão configuradas para ter menos direitos de usuário podem ser menos afetados do que aqueles que têm direitos de administrador.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-058">MS16-058</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Windows IIS (3141083)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um atacante com acesso ao sistema local executa um aplicativo mal-intencionado. O atacante que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os usuários cujas contas estão configuradas para ter menos direitos de usuário podem ser menos afetados do que aqueles que têm direitos de administrador.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-059">MS16-059</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Windows Media Center (3150220)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de um código se o Windows Media Center abrir um arquivo de link do Media Center (.mcl) especialmente criado que faz referência a um código mal-intencionado. O atacante que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os usuários cujas contas estão configuradas para ter menos direitos de usuário podem ser menos afetados do que aqueles que têm direitos de administrador.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-060">MS16-060</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para kernel do Windows (3154846)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade poderá permitir a elevação de privilégio se um atacante se conectar a um sistema afetado e executar um aplicativo especialmente criado.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-061">MS16-061</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para RPC da Microsoft (3155520)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um atacante com autenticação faz solicitações RPC (Chamada de Procedimento Remoto) mal-formadas para um host afetado.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-062">MS16-062</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para drivers do modo Kernel do Windows (3158222)<br />
</strong>Esta atualização de segurança elimina vulnerabilidades no Microsoft Windows. A mais severa das vulnerabilidades poderá permitir a elevação de privilégio se um atacante se conectar a um sistema afetado e executar um aplicativo especialmente criado.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-064">MS16-064</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Adobe Flash Player (3157993)</strong><br />
Esta atualização de segurança resolve vulnerabilidades no Adobe Flash Player quando instalado em todas as edições com suporte do Windows 8.1, do Windows Server 2012, do Windows Server 2012 R2, do Windows RT 8.1 e do Windows 10.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Adobe Flash Player</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-065">MS16-065</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o .NET Framework (3156757)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft .NET Framework. A vulnerabilidade pode causar a divulgação de informações se um atacante injeta dados não criptografados no canal protegido de destino e então realiza um ataque intermediário (MiTM, man-in-the-middle) entre o cliente de destino e um servidor legítimo.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-066">MS16-066</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Modo de Segurança Virtual (3155451)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir um bypass do recurso de segurança se um atacante executa um aplicativo especialmente criado para ignorar as proteções de integridade do código no Windows.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Desvio de recurso de segurança</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-067">MS16-067</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Driver de Gerenciador de Volumes (3155784)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a divulgação de informações se um disco USB montado sobre o protocolo RDP por meio do Microsoft RemoteFX não é vinculado corretamente à sessão do usuário da montagem.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Índice de exploração  
--------------------
  
<span id="sectionToggle1"></span>
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidade são listadas em ordem de ID do boletim, depois de ID do CVE. Só serão incluídas as vulnerabilidades que tiverem uma classificação de gravidade Crítica ou Importante nos boletins.
  
**Como devo usar a tabela?**
  
Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Índice de Exploração da Microsoft](http://technet.microsoft.com/pt-br/security/cc998259).
  
Nas colunas a seguir, "Versão Mais Recente de Software" se refere ao software, e "Versões Mais Antigas de Software" se refere a todas as versões mais antigas e suportadas do software, como listado nas tabelas "Softwares Afetados" e "Softwares não afetados" do boletim.

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**ID do CVE**                    
</td>
<td style="border:1px solid black;">
**Título da vulnerabilidade**
</td>
<td style="border:1px solid black;">
**Avaliação de exploração para  
Versão de software mais recente**
</td>
<td style="border:1px solid black;">
**Avaliação de exploração para  
Versão de software mais antiga**
</td>
<td style="border:1px solid black;">
**Negação de Serviço  
Avaliação de exploração**
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-051: Atualização de segurança cumulativa para o Internet Explorer (3155533)**](https://technet.microsoft.com/pt-br/library/security/ms16-051)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0187](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0187)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0188](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0188)
</td>
<td style="border:1px solid black;">
Bypass do recurso de segurança do Internet Explorer
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0189](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0189)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
0 - Exploração detectada
</td>
<td style="border:1px solid black;">
0 - Exploração detectada
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0192](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0192)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0194](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0194)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informação do Internet Explorer
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-052: Atualização de segurança cumulativa do Microsoft Edge (3155538)**](https://technet.microsoft.com/pt-br/library/security/ms16-052)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0186](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0186)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0191](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0191)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0192](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0192)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0193](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0193)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-053: Atualização de segurança cumulativa para JScript e VBScript (3156764)**](https://technet.microsoft.com/pt-br/library/security/ms16-053)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0187](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0187)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0189](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0189)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
0 - Exploração detectada
</td>
<td style="border:1px solid black;">
0 - Exploração detectada
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-054: Atualização de segurança para o Microsoft Office (3155544)**](https://technet.microsoft.com/pt-br/library/security/ms16-054)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0126](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0126)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0140](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0140)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0183](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0183)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de RCE de elementos gráficos no Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0198](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0198)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
1 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-055: Atualização de segurança para o componente gráfico da Microsoft (3156754)**](https://technet.microsoft.com/pt-br/library/security/ms16-055)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0168](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0168)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações dos componentes gráficos do Windows
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Temporário
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0169](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0169)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações dos componentes gráficos do Windows
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Temporário
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0170](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0170)
</td>
<td style="border:1px solid black;">
Vulnerabilidade RCE dos componentes gráficos do Windows
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0184](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0184)
</td>
<td style="border:1px solid black;">
Uso de Direct3D após a liberação da vulnerabilidade
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0195](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0195)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do componente do Windows Imaging
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-056: Atualização de segurança do Diário do Windows (3156761)**](https://technet.microsoft.com/pt-br/library/security/ms16-056)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0182](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0182)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Diário
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-057: Atualizações de segurança para o Windows Shell (3156987)**](https://technet.microsoft.com/pt-br/library/security/ms16-057)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0179](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0179)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Windows Shell
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-058: Atualização de segurança para o Windows IIS (3141083)**](https://technet.microsoft.com/pt-br/library/security/ms16-058)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0152](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0152)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código de carregamento de DLL do Windows
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-059: Atualização de segurança para o Windows Media Center (3150220)**](https://technet.microsoft.com/pt-br/library/security/ms16-059)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016- 0185](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0185)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Windows Media Center
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-060: Atualização de segurança para kernel do Windows (3154846)**](https://technet.microsoft.com/pt-br/library/security/ms16-060)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0180](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0180)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio de kernel do Windows
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-061: Atualização de segurança para RPC da Microsoft (3155520)**](https://technet.microsoft.com/pt-br/library/security/ms16-061)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0178](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0178)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do mecanismo de representação de dados da rede RPC
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-062: Atualização de segurança para drivers do modo Kernel do Windows (3158222)**](https://technet.microsoft.com/pt-br/library/security/ms16-062)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0171](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0171)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Permanente
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0173](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0173)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0174](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0174)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Permanente
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016- 0175](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0175)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Win32k
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0176](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0176)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégios do subsistema do kernel de gráficos do Microsoft DirectX
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0196](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0196)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Permanente
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0197](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0197)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégios do subsistema do kernel de gráficos do Microsoft DirectX
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-064: Atualização de segurança para o Adobe Flash Player (3157993)**](https://technet.microsoft.com/pt-br/library/security/ms16-064)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-15](https://helpx.adobe.com/security/br/products/flash-player/apsb16-15.html)
</td>
<td style="border:1px solid black;">
Consulte o [Boletim de segurança da Adobe APSB16-15](https://helpx.adobe.com/security/br/products/flash-player/apsb16-15.html) para classificações da prioridade da atualização e gravidade da vulnerabilidade.
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-065: Atualização de segurança para o .NET Framework (3156757)**](https://technet.microsoft.com/pt-br/library/security/ms16-065)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0149](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0149)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações de TLS/SSL
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-066: Atualização de segurança para o Modo de Segurança Virtual (3155451)**](https://technet.microsoft.com/pt-br/library/security/ms16-066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0181](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0181)
</td>
<td style="border:1px solid black;">
Bypass do recurso de segurança de integridade do código do hipervisor
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-067: Atualização de segurança para o Driver de Gerenciador de Volumes (3155784)**](https://technet.microsoft.com/pt-br/library/security/ms16-067)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0190](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0190)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações de redirecionamento da unidade de protocolo RDP
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>
 

Softwares Afetados
------------------

<span id="sectionToggle2"></span>
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.

Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, a classificação de gravidade da atualização do software também estará listada.

**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.

 

### Sistemas operacionais do Windows e componentes (Tabela 1 de 2)

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/pt-br/library/security/ms16-051)
</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/pt-br/library/security/ms16-052)
</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/pt-br/library/security/ms16-053)
</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/pt-br/library/security/ms16-055)
</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/pt-br/library/security/ms16-056)
</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/pt-br/library/security/ms16-057)
</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/pt-br/library/security/ms16-058)
</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/pt-br/library/security/ms16-059)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3156013)  
(Crítica)  
Windows Vista Service Pack 2  
(3156016)  
(Crítica)  
Windows Vista Service Pack 2  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3155178)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3141083)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3150220)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3156013)  
(Crítica)  
Windows Vista x64 Edition Service Pack 2  
(3156016)  
(Crítica)  
Windows Vista x64 Edition Service Pack 2  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3155178)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3141083)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3150220)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/pt-br/library/security/ms16-051)
</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/pt-br/library/security/ms16-052)
</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/pt-br/library/security/ms16-053)
</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/pt-br/library/security/ms16-055)
</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/pt-br/library/security/ms16-056)
</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/pt-br/library/security/ms16-057)
</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/pt-br/library/security/ms16-058)
</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/pt-br/library/security/ms16-059)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(Moderado)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3156013)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3156016)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3141083)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(Moderado)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3156013)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3156016)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3141083)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(Moderado)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3156013)  
(Crítica)  
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3141083)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/pt-br/library/security/ms16-051)
</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/pt-br/library/security/ms16-052)
</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/pt-br/library/security/ms16-053)
</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/pt-br/library/security/ms16-055)
</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/pt-br/library/security/ms16-056)
</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/pt-br/library/security/ms16-057)
</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/pt-br/library/security/ms16-058)
</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/pt-br/library/security/ms16-059)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3156013)  
(Crítica)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(3156016)  
(Crítica)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3155178)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3150220)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3156013)  
(Crítica)  
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3156016)  
(Crítica)  
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3155178)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3150220)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/pt-br/library/security/ms16-051)
</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/pt-br/library/security/ms16-052)
</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/pt-br/library/security/ms16-053)
</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/pt-br/library/security/ms16-055)
</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/pt-br/library/security/ms16-056)
</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/pt-br/library/security/ms16-057)
</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/pt-br/library/security/ms16-058)
</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/pt-br/library/security/ms16-059)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3156013)  
(Crítica)  
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3156016)  
(Crítica)  
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3156013)  
(Crítica)  
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3156016)  
(Crítica)  
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/pt-br/library/security/ms16-051)
</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/pt-br/library/security/ms16-052)
</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/pt-br/library/security/ms16-053)
</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/pt-br/library/security/ms16-055)
</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/pt-br/library/security/ms16-056)
</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/pt-br/library/security/ms16-057)
</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/pt-br/library/security/ms16-058)
</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/pt-br/library/security/ms16-059)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3156013)  
(Crítica)  
Windows 8.1 para sistemas de 32 bits  
(3156016)  
(Crítica)  
Windows 8.1 para sistemas de 32 bits  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3155178)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3156059)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3150220)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3156013)  
(Crítica)  
Windows 8.1 para sistemas baseados em x64  
(3156016)  
(Crítica)  
Windows 8.1 para sistemas baseados em x64  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3155178)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3156059)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3150220)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 e Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/pt-br/library/security/ms16-051)
</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/pt-br/library/security/ms16-052)
</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/pt-br/library/security/ms16-053)
</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/pt-br/library/security/ms16-055)
</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/pt-br/library/security/ms16-056)
</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/pt-br/library/security/ms16-057)
</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/pt-br/library/security/ms16-058)
</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/pt-br/library/security/ms16-059)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3154070)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3156013)  
(Crítica)  
Windows Server 2012  
(3156016)  
(Crítica)  
Windows Server 2012  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3156013)  
(Crítica)  
Windows Server 2012 R2  
(3156016)  
(Crítica)  
Windows Server 2012 R2  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3156059)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/pt-br/library/security/ms16-051)
</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/pt-br/library/security/ms16-052)
</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/pt-br/library/security/ms16-053)
</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/pt-br/library/security/ms16-055)
</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/pt-br/library/security/ms16-056)
</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/pt-br/library/security/ms16-057)
</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/pt-br/library/security/ms16-058)
</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/pt-br/library/security/ms16-059)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3156013)  
(Crítica)  
Windows RT 8.1  
(3156016)  
(Crítica)  
Windows RT 8.1  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3155178)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3156059)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/pt-br/library/security/ms16-051)
</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/pt-br/library/security/ms16-052)
</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/pt-br/library/security/ms16-053)
</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/pt-br/library/security/ms16-055)
</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/pt-br/library/security/ms16-056)
</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/pt-br/library/security/ms16-057)
</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/pt-br/library/security/ms16-058)
</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/pt-br/library/security/ms16-059)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156387)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156387)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3156387)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3156387)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3156387)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156387)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156387)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3156387)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3156387)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3156387)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156421)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156421)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3156421)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3156421)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3156421)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156421)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156421)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3156421)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3156421)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3156421)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Opção de instalação Server Core**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/pt-br/library/security/ms16-051)
</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/pt-br/library/security/ms16-052)
</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/pt-br/library/security/ms16-053)
</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/pt-br/library/security/ms16-055)
</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/pt-br/library/security/ms16-056)
</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/pt-br/library/security/ms16-057)
</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/pt-br/library/security/ms16-058)
</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/pt-br/library/security/ms16-059)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(Moderado)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3156013)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3156016)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3141083)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
(Moderado)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3156013)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3156016)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3141083)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
JScript 5.8 e VBScript 5.8  
(3155413)  
(Moderado)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3156013)  
(Crítica)  
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3156016)  
(Crítica)  
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3156013)  
(Crítica)  
Windows Server 2012 (instalação Server Core)  
(3156016)  
(Crítica)  
Windows Server 2012 (instalação Server Core)  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3156013)  
(Crítica)  
Windows Server 2012 R2 (instalação Server Core)  
(3156016)  
(Crítica)  
Windows Server 2012 R2 (instalação Server Core)  
(3156019)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>
 
 

### Sistemas operacionais do Windows e componentes (Tabela 2 de 2)

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/pt-br/library/security/ms16-060)
</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/pt-br/library/security/ms16-061)
</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/pt-br/library/security/ms16-062)
</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/pt-br/library/security/ms16-064)
</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/pt-br/library/security/ms16-065)
</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/pt-br/library/security/ms16-066)
</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/pt-br/library/security/ms16-067)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3153199)  
(Importante)  
Windows Vista Service Pack 2  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(Importante)  
Microsoft .NET Framework 4.6  
(3142037)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3153199)  
(Importante)  
Windows Vista x64 Edition Service Pack 2  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(Importante)  
Microsoft .NET Framework 4.6  
(3142037)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/pt-br/library/security/ms16-060)
</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/pt-br/library/security/ms16-061)
</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/pt-br/library/security/ms16-062)
</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/pt-br/library/security/ms16-064)
</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/pt-br/library/security/ms16-065)
</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/pt-br/library/security/ms16-066)
</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/pt-br/library/security/ms16-067)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3153199)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(Importante)  
Microsoft .NET Framework 4.6  
(3142037)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3153199)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(Importante)  
Microsoft .NET Framework 4.6  
(3142037)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3153199)  
(Importante)  
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/pt-br/library/security/ms16-060)
</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/pt-br/library/security/ms16-061)
</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/pt-br/library/security/ms16-062)
</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/pt-br/library/security/ms16-064)
</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/pt-br/library/security/ms16-065)
</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/pt-br/library/security/ms16-066)
</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/pt-br/library/security/ms16-067)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3153199)  
(Importante)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3153199)  
(Importante)  
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/pt-br/library/security/ms16-060)
</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/pt-br/library/security/ms16-061)
</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/pt-br/library/security/ms16-062)
</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/pt-br/library/security/ms16-064)
</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/pt-br/library/security/ms16-065)
</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/pt-br/library/security/ms16-066)
</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/pt-br/library/security/ms16-067)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3153199)  
(Importante)  
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3153199)  
(Importante)  
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/pt-br/library/security/ms16-060)
</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/pt-br/library/security/ms16-061)
</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/pt-br/library/security/ms16-062)
</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/pt-br/library/security/ms16-064)
</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/pt-br/library/security/ms16-065)
</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/pt-br/library/security/ms16-066)
</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/pt-br/library/security/ms16-067)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3153704)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3153199)  
(Importante)  
Windows 8.1 para sistemas de 32 bits  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3153704)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3153199)  
(Importante)  
Windows 8.1 para sistemas baseados em x64  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2012 e Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/pt-br/library/security/ms16-060)
</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/pt-br/library/security/ms16-061)
</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/pt-br/library/security/ms16-062)
</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/pt-br/library/security/ms16-064)
</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/pt-br/library/security/ms16-065)
</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/pt-br/library/security/ms16-066)
</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/pt-br/library/security/ms16-067)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153704)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153199)  
(Importante)  
Windows Server 2012  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(Moderado)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142025)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142032)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3142035)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3155784)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153704)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153199)  
(Importante)  
Windows Server 2012 R2  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(Moderado)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3155784)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/pt-br/library/security/ms16-060)
</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/pt-br/library/security/ms16-061)
</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/pt-br/library/security/ms16-062)
</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/pt-br/library/security/ms16-064)
</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/pt-br/library/security/ms16-065)
</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/pt-br/library/security/ms16-066)
</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/pt-br/library/security/ms16-067)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153704)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153199)  
(Importante)  
Windows RT 8.1  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3142030)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/pt-br/library/security/ms16-060)
</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/pt-br/library/security/ms16-061)
</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/pt-br/library/security/ms16-062)
</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/pt-br/library/security/ms16-064)
</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/pt-br/library/security/ms16-065)
</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/pt-br/library/security/ms16-066)
</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/pt-br/library/security/ms16-067)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3156387)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3156387)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3156387)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156387)  
(Importante)  
Microsoft .NET Framework 4.6  
(3156387)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3156387)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3156387)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3156387)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3156387)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156387)  
(Importante)  
Microsoft .NET Framework 4.6  
(3156387)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3156387)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3156421)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3156421)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3156421)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156421)  
(Importante)  
Microsoft .NET Framework 4.6.1  
(3156421)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3156421)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3156421)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3156421)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3156421)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156421)  
(Importante)  
Microsoft .NET Framework 4.6.1  
(3156421)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3156421)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Opção de instalação Server Core**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/pt-br/library/security/ms16-060)
</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/pt-br/library/security/ms16-061)
</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/pt-br/library/security/ms16-062)
</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/pt-br/library/security/ms16-064)
</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/pt-br/library/security/ms16-065)
</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/pt-br/library/security/ms16-066)
</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/pt-br/library/security/ms16-067)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante **](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(instalação Server Core)  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(instalação Server Core)  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(instalação Server Core)  
(3153199)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(instalação Server Core)  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(instalação Server Core)  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(instalação Server Core)  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(instalação Server Core)  
(3153199)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(instalação Server Core)  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(instalação Server Core)  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(instalação Server Core)  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(instalação Server Core)  
(3153199)  
(Importante)  
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(instalação Server Core)  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)  
(3153704)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)  
(3153199)  
(Importante)  
Windows Server 2012  
(instalação Server Core)  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142025)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142032)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3142035)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)  
(3155784)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)  
(3153171)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)  
(3153704)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)  
(3153199)  
(Importante)  
Windows Server 2012 R2  
(instalação Server Core)  
(3156017)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)  
(3155784)  
(Importante)
</td>
</tr>
</table>
 
 

### Microsoft Office Suites e software

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/pt-br/library/security/ms16-054)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2984938)  
(Importante)  
Microsoft Office 2007 Service Pack 3  
(2984943)  
(Importante)  
Microsoft Word 2007 Service Pack 3  
(3115116)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/pt-br/library/security/ms16-054)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(3115121)  
(Crítica)  
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(3054984)  
(Importante)  
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(3101520)  
(Importante)  
Microsoft Word 2010 Service Pack 2 (edições de 32 bits)  
(3115123)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(3115121)  
(Crítica)  
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(3054984)  
(Importante)  
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(3101520)  
(Importante)  
Microsoft Word 2010 Service Pack 2 (edições de 64 bits)  
(3115123)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/pt-br/library/security/ms16-054)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 32 bits)  
(3115016)  
(Importante)  
Microsoft Word 2013 Service Pack 1 (edições de 32 bits)  
(3115025)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 64 bits)  
(3115016)  
(Importante)  
Microsoft Word 2013 Service Pack 1 (edições de 64 bits)  
(3115025)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/pt-br/library/security/ms16-054)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3115016)  
(Importante)  
Microsoft Word 2013 RT Service Pack 1  
(3115025)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/pt-br/library/security/ms16-054)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (edição de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (edição de 32 bits)  
(3115103)  
(Importante)  
Microsoft Word 2016 (edição de 32 bits):  
(3115094)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (edição de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (edição de 64 bits)  
(3115103)  
(Importante)  
Microsoft Word 2016 (edição de 64 bits):  
(3115094)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office para Mac 2011**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/pt-br/library/security/ms16-054)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office para Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Word para Mac 2011  
(3155776)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016 para Mac**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/pt-br/library/security/ms16-054)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 para Mac
</td>
<td style="border:1px solid black;">
Microsoft Word 2016 para Mac  
(3155777)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Outros softwares do Office**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/pt-br/library/security/ms16-054)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3
</td>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3  
(3115115)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115132)  
(Crítica)
</td>
</tr>
</table>
 
**Observação para MS16-054**

Este boletim abrange mais de uma categoria de software. Consulte outras tabelas nesta seção para obter informações adicionais sobre softwares afetados.

### Microsoft Office Services e Web Apps

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/pt-br/library/security/ms16-054)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Serviços de Automação do Word  
(3115117)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/pt-br/library/security/ms16-054)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3115124)  
(Crítica)
</td>
</tr>
</table>
 
**Observação para MS16-054**

Este boletim abrange mais de uma categoria de software. Consulte outras tabelas nesta seção para obter informações adicionais sobre softwares afetados.

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

<span id="sectionToggle3"></span>
Vários recursos estão disponíveis para ajudar administradores a implantar atualizações de segurança.

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns.

O WSUS (Windows Server Update Services), SMS (Systems Management Server) e SCCM (System Center Configuration Manager) ajudam os administradores a distribuir as atualizações de segurança.

Os componentes do Avaliador de Compatibilidade de Atualizações, incluídos no Kit de Ferramentas de Compatibilidade de Aplicativos, auxilia a otimizar os testes e a validação das atualizações do Windows com relação aos aplicativos instalados.

Para obter mais informações sobre essas e outras ferramentas disponíveis, consulte [Ferramentas de segurança para profissionais de TI](http://technet.microsoft.com/pt-br/security/cc297183). 

Agradecimentos
--------------

<span id="sectionToggle4"></span>
A Microsoft reconhece os esforços dos membros da comunidade de segurança que nos ajudam a proteger os consumidores graças à divulgação responsável de vulnerabilidades. Consulte [Agradecimentos](https://technet.microsoft.com/pt-br/library/security/mt674627.aspx) para obter mais informações.

Outras informações
------------------

<span id="sectionToggle5"></span>
### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

Em relação ao lançamento de boletins que ocorre na segunda terça-feira do mês, a Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows no Windows Update, Microsoft Update, Windows Server Update Services e Centro de Download. Nenhuma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows está disponível para os lançamentos de boletins de segurança desvinculados.

### Atualizações não relacionadas à segurança no MU, WU e WSUS

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 do Banco de Dados de Conhecimento da Microsoft](https://support.microsoft.com/pt-br/kb/894199): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/pt-br/windowsserver/bb332157.aspx). Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do Microsoft Active Protections Program (MAPP)](http://technet.microsoft.com/pt-br/security/dn467918).

### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de segurança para gerenciamento de atualizações](http://technet.microsoft.com/pt-br/library/bb466251.aspx) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://www.microsoft.com/downloads/results.aspx?displaylang=pt-br&freetext=security%20update). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=pt-br).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter informações adicionais, consulte o [artigo 913086 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://technet.microsoft.com/pt-br/security/cc136632.aspx).

### Suporte

O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle).

Soluções de segurança para profissionais de TI: [Suporte e Solução de Problemas de Segurança do TechNet](http://technet.microsoft.com/pt-br/security/bb980617)

Ajuda a proteger seu computador executando o Windows contra vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=pt-br)

Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx?ln=pt-br)

### Aviso de isenção de responsabilidade

As informações fornecidas na Base de Dados de Conhecimento da Microsoft são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

### Revisões

-   V1.0 (10 de maio de 2016): Resumo do boletim publicado.
-   V1.1 (11 de maio de 2016): O resumo do boletim foi revisado para alterar o impacto da vulnerabilidade do MS16-061 de elevação de privilégio para execução remota de código e o título do CVE 2016-0178 para Vulnerabilidade de execução remota de código do mecanismo de representação de dados da rede RPC. Esta é apenas uma alteração informativa.
-   V1.2 (13 de maio de 2016): Para o MS16-067, o Resumo do boletim foi revisado para alterar a classificação de severidade da vulnerabilidade para o Windows 8.1 e o Windows RT 8.1 para Não aplicável, pois esses sistemas operacionais não são afetados pela vulnerabilidade descrita neste boletim. Os clientes que aplicaram a atualização de segurança 3155784 não precisam fazer mais nada. Esta é apenas uma alteração informativa.
-   V2.0 (13 de maio de 2016): Para o MS16-064, o Resumo do boletim foi revisado para anunciar o lançamento da atualização 3163207 para abordar as vulnerabilidades incluídas no Boletim de segurança da Adobe APSB16-15. Observe que a atualização 3163207 substitui a atualização lançada anteriormente no MS16-064 (atualização 3157933). A Microsoft recomenda enfaticamente que os clientes instalem a atualização 3163207 para ficarem protegidos das vulnerabilidades descritas no Boletim de segurança da Adobe APSB16-15.

*Página gerada em 13/05/2016 às 09:15-07:00.*
