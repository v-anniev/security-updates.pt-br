---
TOCTitle: 'MS16-SEP'
Title: Resumo de boletins de segurança da Microsoft de setembro de 2016
ms:assetid: 'ms16-sep'
ms:contentKeyID: 73895892
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms16-sep(v=Security.10)'
---

Modelo do MSRC ppDocument

Resumo de boletins de segurança da Microsoft de setembro de 2016
================================================================

Publicado em: 13 de setembro de 2016 | Atualizado em: 11 de julho de 2017

**Versão:** 2.0

Este resumo de boletins lista os boletins de segurança lançados em setembro de 2016.

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft forem emitidos, visite [Notificações de Segurança Técnica da Microsoft.](http://go.microsoft.com/fwlink/?linkid=21163)

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações**.

Resumos executivos
------------------

<span id="sectionToggle0"></span>
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter mais informações, consulte a seção **Softwares afetados**.

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
<td style="border:1px solid black;"><strong>ID do boletim</strong></td>
<td style="border:1px solid black;"><strong>Título do boletim e Resumo executivo</strong></td>
<td style="border:1px solid black;"><strong>Classificação máxima de gravidade<br />
e impacto da vulnerabilidade</strong></td>
<td style="border:1px solid black;"><strong>Requisito de reinicialização</strong></td>
<td style="border:1px solid black;"><strong>Problemas<br />
conhecidos</strong></td>
<td style="border:1px solid black;"><strong>Softwares afetados</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=823624">MS16-104</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança Cumulativa para Internet Explorer (3183038)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Internet Explorer. A vulnerabilidade mais grave poderá permitir execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O atacante que explorar com êxito as vulnerabilidades poderá ganhar os mesmos direitos de usuário que o usuário em questão. Se o usuário atual estiver conectado com direitos de usuário administrativo, o invasor poderá assumir o controle do sistema afetado. O atacante poderia instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítico</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/pt-br/kb/3185319">3185319</a></td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=823625">MS16-105</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança Cumulativa para Microsoft Edge (3183043)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Microsoft Edge. A vulnerabilidade mais grave poderá permitir execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Microsoft Edge. Um invasor que tenha conseguido explorar as vulnerabilidades pode obter os mesmos direitos que o usuário atual. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema podem correr menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítico</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=824814">MS16-106</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança Cumulativa para Microsoft Graphics Component (3185848)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Microsoft Windows. A mais grave das vulnerabilidades pode permitir a execução remota de código se um usuário visitar um site especialmente criado ou abrir um documento especialmente criado. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que têm direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítico</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=824817">MS16-107</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança para Microsoft Office (3185852)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Microsoft Office. A mais grave das vulnerabilidades pode permitir a execução remota de código se um usuário abrir um arquivo do Microsoft Office especialmente criado. Um invasor que tenha conseguido explorar as vulnerabilidades pode executar um código arbitrário no contexto do usuário atual. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítico</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Serviços do Microsoft Office e Aplicativos Web</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=824829">MS16-108</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança para Microsoft Exchange Server (3185883)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Microsoft Exchange Server. A mais grave das vulnerabilidades pode permitir a execução remota de código em algumas bibliotecas Oracle Outside In que são internas ao Exchange Server se um invasor envia um email com um anexo especialmente criado a um servidor Exchange vulnerável.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítico</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=824768">MS16-109</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança para Silverlight (3182373)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Silverlight. A vulnerabilidade poderá permitir a execução remota de código se um usuário visitar um site comprometido que contém um aplicativo Silverlight especialmente criado. Não há como um invasor forçar um usuário a visitar o site comprometido. Em vez disso, o invasor teria que persuadir o usuário a visitar o site, geralmente fazendo com que ele clique em um link em um email ou mensagem instantânea que leva o usuário ao site do invasor.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Não exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=821596">MS16-110</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança para Windows (3178467)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Microsoft Windows. A mais grave das vulnerabilidades pode permitir a execução remota de código se um invasor criar uma solicitação especialmente criada e executar código arbitrário com permissões elevadas em um sistema de destino.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/pt-br/kb/3187754">3187754</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=825142">MS16-111</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança para Kernel do Windows (3186973)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Microsoft Windows. As vulnerabilidades podem permitir a elevação de privilégios se um invasor executar um aplicativo especialmente criado em um sistema de destino.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Elevação de privilégios</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/pt-br/kb/3175024">3175024</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=821605">MS16-112</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança para Tela de Bloqueio do Windows (3178469)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a elevação de privilégio se o Windows permitir indevidamente que conteúdo da Web seja carregado da tela de bloqueio do Windows.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Elevação de privilégios</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=824825">MS16-113</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança para Modo de Kernel Seguro do Windows (3185876)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a divulgação de informações quando o Modo Kernel Seguro do Windows manipula indevidamente objetos na memória.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Divulgação de informações</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=824826">MS16-114</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança para SMBv1 Server (3185879)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. Nos em sistemas operacionais Windows Vista, Windows Server 2008, Windows 7 e Windows Server 2008 R2, a vulnerabilidade pode permitir a execução remota de código se um invasor autenticado enviar pacotes especialmente criados a um Microsoft Server Message Block 1.0 (SMBv1) Server afetado. A vulnerabilidade não afeta outras versões do SMB Server. Embora os sistemas operacionais posteriores sejam afetados, o impacto potencial é de negação de serviço.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=825727">MS16-115</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança para Biblioteca de PDF do Microsoft Windows (3188733)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Microsoft Windows. As vulnerabilidades podem permitir a divulgação não autorizada de informações se um usuário exibir conteúdo em PDF especialmente criado online ou abrir um documento PDF especialmente criado.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Divulgação de informações</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=825725">MS16-116</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança na Automação OLE para Mecanismo de Script VBScript (3188724)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a execução de código remoto se um invasor conseguir convencer um usuário de um sistema afetado a visitar um site mal-intencionado ou comprometido. Observe que você deve instalar duas atualizações para estar protegido da vulnerabilidade abordada neste boletim: A atualização neste boletim, MS16-116, e a atualização em <a href="http://go.microsoft.com/fwlink/?linkid=823624">MS16-104</a>.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítico</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows<br /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=825603">MS16-117</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança para Adobe Flash Player (3188128)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Adobe Flash Player quando instalado em todas as edições com suporte do Windows 8.1, do Windows Server 2012, do Windows Server 2012 R2, do Windows RT 8.1 e do Windows 10.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítico</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

Índice de exploração
--------------------

<span id="sectionToggle1"></span>
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidades estão listadas por ID do boletim e depois por ID do CVE. Estão incluídas nos boletins somente vulnerabilidades com classificação de gravidade Crítica ou Importante.

**Como devo usar esta tabela?**

Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que significam essas classificações e como elas são determinadas, consulte o [Índice de Exploração da Microsoft](http://technet.microsoft.com/pt-br/security/cc998259).

Nas colunas a seguir, "Versão mais recente de software" se refere ao software e "Versões mais antigas de software" se refere a todas as versões mais antigas do software compatíveis, conforme listado nas tabelas "Softwares afetados" e "Softwares não afetados" do boletim.

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**ID do CVE**                    
</td>
<td style="border:1px solid black;">
**Título da vulnerabilidade**
</td>
<td style="border:1px solid black;">
**Avaliação da capacidade de exploração da  
última versão de software**
</td>
<td style="border:1px solid black;">
**Avaliação da capacidade de exploração de  
versão mais antiga de software**
</td>
<td style="border:1px solid black;">
**Avaliação do risco de exploração  
para negação de serviço**
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-104: Atualização de segurança cumulativa para o Internet Explorer (3183038)**](http://go.microsoft.com/fwlink/?linkid=823624)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3247)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3291](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3291)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações no navegador da Microsoft
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3292](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3292)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do navegador da Microsoft
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3295](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3295)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
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
<td style="border:1px solid black;">
[CVE-2016-3297](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3297)
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
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3324](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3324)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3325](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3325)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações no navegador da Microsoft
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3351](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3351)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações no navegador da Microsoft
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
[CVE-2016-3353](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3353)
</td>
<td style="border:1px solid black;">
Bypass do recurso de segurança do Internet Explorer
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
<td style="border:1px solid black;">
[CVE-2016-3375](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3375)
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
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-105: Atualização de segurança cumulativa do Microsoft Edge (3183043)**](http://go.microsoft.com/fwlink/?linkid=823625)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3247)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3291](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3291)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações no navegador da Microsoft
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3294](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3294)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Edge
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3295](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3295)
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
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3297](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3297)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3325](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3325)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações no navegador da Microsoft
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3330](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3330)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Edge
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3350](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3350)
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
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3351](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3351)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações no navegador da Microsoft
</td>
<td style="border:1px solid black;">
0 - Exploração detectada
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3370](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3370)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações da Biblioteca de PDF
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3374](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3374)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações da Biblioteca de PDF
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3377](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3377)
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
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-106: Atualização de segurança para o componente gráfico da Microsoft (3185848)**](http://go.microsoft.com/fwlink/?linkid=824814)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3348](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3348)
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
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3349](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3349)
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
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3354](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3354)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações de GDI
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3355](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3355)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de Elevação de Privilégio de GDI
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3356](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3356)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código de GDI
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-107: Atualização de segurança para o Microsoft Office (3185852)**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0137](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0137)
</td>
<td style="border:1px solid black;">
Bypass de ASLR de Microsoft APP-V
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0141](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0141)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações da Microsoft
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
<td style="border:1px solid black;">
[CVE-2016-3357](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3357)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3358](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3358)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3359](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3359)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3360](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3360)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3361](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3361)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3362](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3362)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3363](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3363)
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
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3364](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3364)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3365](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3365)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3366](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3366)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de falsificação do Microsoft Office
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
<td style="border:1px solid black;">
[CVE-2016-3381](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3381)
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
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-108: Atualização de segurança para o Microsoft Exchange Server (3185883)**](http://go.microsoft.com/fwlink/?linkid=824829)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0138](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0138)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações no Microsoft Exchange
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
<td style="border:1px solid black;">
[CVE-2016-3378](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3378)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de Redirecionamento Aberto do Microsoft Exchange
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
<td style="border:1px solid black;">
[CVE-2016-3379](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3379)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de Elevação de Privilégio do Microsoft Exchange
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-109: Atualização de segurança para Silverlight (3182373)**](http://go.microsoft.com/fwlink/?linkid=824768)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3367](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3367)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Silverlight
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
[**MS16-110: Atualização de segurança para o Windows (3178467)**](http://go.microsoft.com/fwlink/?linkid=821596)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3346](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3346)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio de imposição de permissões do Windows
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3352](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3352)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações da Microsoft
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3368](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3368)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Windows
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3369](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3369)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de Negação de Serviço no Windows
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Permanente
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-111: Atualização de segurança para kernel do Windows (3186973)**](http://go.microsoft.com/fwlink/?linkid=825142)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3305](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3305)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio de objeto de sessão do Windows
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3306](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3306)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio de objeto de sessão do Windows
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3371](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3371)
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
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3372](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3372)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio de kernel do Windows
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
<tr>
<td style="border:1px solid black;">
[CVE-2016-3373](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3373)
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
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-112: Atualização de segurança para Tela de bloqueio (3178469)**](http://go.microsoft.com/fwlink/?linkid=821605)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3302](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3302)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio da tela de bloqueio do Windows
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
[**MS16-113: Atualização de segurança para o Modo Kernel Seguro do Windows (3185876)**](http://go.microsoft.com/fwlink/?linkid=824825)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3344](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3344)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações do Modo Kernel Seguro do Windows
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-114: Atualização de segurança para o SMBv1 Server (3185879)**](http://go.microsoft.com/fwlink/?linkid=824826)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3345](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3345)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código autenticado do Windows SMB
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Permanente
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-115: Atualização de segurança para a biblioteca de PDFs do Microsoft Windows (3188733)**](http://go.microsoft.com/fwlink/?linkid=825727)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3370](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3370)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações da Biblioteca de PDF
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3374](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3374)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações da Biblioteca de PDF
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-116: Atualização de segurança na automação OLE para Mecanismo de script VBScript (3188724)**](http://go.microsoft.com/fwlink/?linkid=825725)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3375](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3375)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações de mecanismo de scripting
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-117: Atualização de segurança para o Adobe Flash Player (3188128)**](http://go.microsoft.com/fwlink/?linkid=825603)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-29](http://helpx.adobe.com/br/security/products/flash-player/apsb16-29.html)
</td>
<td style="border:1px solid black;">
Consulte o Boletim de segurança da Adobe [APSB16-29](http://helpx.adobe.com/br/security/products/flash-player/apsb16-29.html) para ver classificações de prioridade da atualização e de gravidade da vulnerabilidade.
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
</table>
 

 Softwares afetados
-------------------

<span id="sectionToggle2"></span>
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.

Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, a classificação de gravidade da atualização do software também estará listada.

**Observação** Talvez seja necessário instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.

 

### Sistemas operacionais do Windows e componentes (Tabela 1 de 2)

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)
</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)
</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)
</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)
</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)
</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Internet Explorer 9   
(3185319)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3185319)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)
</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)
</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)
</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)
</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)
</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
(3185319)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3185319)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)
</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)
</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)
</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)
</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)
</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável                   
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)
</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)
</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)
</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)
</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)
</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)
</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)
</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)
</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)
</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)
</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3184471)  
(Importante)  
Windows 8.1 para sistemas de 32 bits  
(3187754)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3178539)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3184471)  
(Importante)  
Windows 8.1 para sistemas baseados em x64  
(3187754)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3178539)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 e Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)
</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)
</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)
</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)
</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)
</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3185319)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3178539)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)
</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)
</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)
</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)
</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)
</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3184471)  
(Importante)  
Windows RT 8.1  
(3187754)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3178539)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)
</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)
</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)
</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)
</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)
</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185611)  
(Crítico)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185611)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3185611)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3185611)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3185611)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3185611)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185611)  
(Crítico)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185611)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3185611)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3185611)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3185611)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3185611)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185614)  
(Crítico)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185614)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3185614)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185614)  
(Crítico)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185614)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3185614)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3189866)  
(Crítico)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3189866)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(3189866)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(3189866)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(3189866)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(3189866)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3189866)  
(Crítico)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3189866)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas baseados em x64  
(3189866)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas baseados em x64  
(3189866)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas baseados em x64  
(3189866)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(3189866)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1703 para sistemas de 32 bits
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
<td style="border:1px solid black;">
Windows 10 Versão 1703 para sistemas de 32 bits  
(4025342)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1703 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Não aplicável
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
Windows 10 Versão 1703 para sistemas com base em x64  
(4025342)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Opção de instalação Server Core**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)
</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)
</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)
</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)
</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)
</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para Sistemas baseados em x64  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
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
Windows Server 2012 R2 (instalação Server Core)  
(3185911)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3184471)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3175024)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3178539)  
(Importante)
</td>
</tr>
</table>
 
 

### Sistemas operacionais do Windows e componentes (Tabela 2 de 2)

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)
</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)
</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)
</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)
</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3184122)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3184122)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)
</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)
</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)
</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)
</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3184122)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3184122)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3184122)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)
</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)
</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)
</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)
</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3184122)  
(Critico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3184122)  
(Critico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)
</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)
</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)
</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)
</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3184122)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3184122)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)
</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)
</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)
</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)
</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3184943)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3184122)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3188128)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3184943)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3184122)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3188128)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 e Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)
</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)
</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)
</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)
</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3184943)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3184122)  
(Moderado)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3188128)  
(Moderado)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3184943)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3184122)  
(Moderado)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3188128)  
(Moderado)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)
</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)
</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)
</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)
</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3184943)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3184122)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3188128)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)
</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)
</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)
</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)
</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3185611)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3185611)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3185611)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3185611)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3188128)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3185611)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3185611)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3185611)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3185611)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3188128)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3185614)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3188128)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3185614)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3188128)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(3189866)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(3189866)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(3188128)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas baseados em x64  
(3185614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas baseados em x64  
(3189866)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas baseados em x64  
(3189866)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas baseados em x64  
(3188128)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1703 para sistemas de 32 bits
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
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1703 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Não aplicável
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
<td style="border:1px solid black;" colspan="6">
**Opção de instalação Server Core**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)
</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)
</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)
</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)
</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3184122)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3184122)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para Sistemas baseados em x64  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3184122)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3184122)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
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
Windows Server 2012 R2 (instalação Server Core)  
(3177186)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3184122)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não aplicável
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
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3118300)  
(Crítico)  
Microsoft Excel 2007 Service Pack 3  
(3115459)  
(Importante)  
Microsoft Outlook 2007  
(3118303)  
(Importante)  
Microsoft PowerPoint 2007 Service Pack 3  
(3114744)  
(Importante)
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
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(3118309)  
(Crítico)  
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(2553432)  
(Crítico)  
Microsoft Excel 2010 Service Pack 2 (edições de 32 bits)  
(3118316)  
(Importante)  
Microsoft Outlook 2010 Service Pack 2 (edições de 32 bits)  
(3118313)  
(Importante)  
Microsoft PowerPoint 2010 Service Pack 2 (edições de 32 bits)  
(3115467)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(3118309)  
(Crítico)  
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(2553432)  
(Crítico)  
Microsoft Excel 2010 Service Pack 2 (edições de 64 bits)  
(3118316)  
(Importante)  
Microsoft Outlook 2010 Service Pack 2 (edições de 64 bits)  
(3118313)  
(Importante)  
Microsoft PowerPoint 2010 Service Pack 2 (edições de 64 bits)  
(3115467)  
(Importante)
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
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 32 bits)  
(3118268)  
(Crítico)  
Microsoft Office 2013 Service Pack 1 (edições de 32 bits)<sup>[1]</sup>
(Importante)  
Microsoft Excel 2013 Service Pack 1 (edições de 32 bits)  
(3118284)  
(Importante)  
Microsoft Outlook 2013 Service Pack 1 (edições de 32 bits)  
(3118280)  
(Importante)  
Microsoft PowerPoint 2013 Service Pack 1 (edições de 32 bits)  
(3115487)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 64 bits)  
(3118268)  
(Crítico)  
Microsoft Office 2013 Service Pack 1 (edições de 64 bits)<sup>[1]</sup>
(Importante)  
Microsoft Excel 2013 Service Pack 1 (edições de 64 bits)  
(3118284)  
(Importante)  
Microsoft Outlook 2013 Service Pack 1 (edições de 64 bits)  
(3118280)  
(Importante)  
Microsoft PowerPoint 2013 Service Pack 1 (edições de 64 bits)  
(3115487)  
(Importante)
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
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3118268)  
(Crítico)  
Microsoft Excel 2013 RT Service Pack 1  
(3118284)  
(Importante)  
Microsoft Outlook 2013 RT Service Pack 1  
(3118280)  
(Importante)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3115487)  
(Importante)
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
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (edição de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (edição de 32 bits)<sup>[1]</sup>
Microsoft Office 2016 (edição de 32 bits)  
(3118292)  
(Crítico)  
Microsoft Excel 2016 (edição de 32 bits)  
(3118290)  
(Importante)  
Microsoft Outlook 2016 (edição de 32 bits)  
(3118293)  
(Importante)  
Microsoft Visio 2016 (edição de 32 bits)  
(Importante)<sup>[1]</sup>
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (edição de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (edição de 64 bits)<sup>[1]</sup>
Microsoft Office 2016 (edição de 64 bits)  
(3118292)  
(Crítico)  
Microsoft Excel 2016 (edição de 64 bits)  
(3118290)  
(Importante)  
Microsoft Outlook 2016 (edição de 64 bits)  
(3118293)  
(Importante)  
Microsoft Visio 2016 (edição de 64 bits)  
(Importante)<sup>[1]</sup>
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
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office para Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Word para Mac 2011  
(3186805)  
(Crítico)
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
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 para Mac
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 para Mac  
(3186807)  
(Importante)  
Microsoft PowerPoint 2016 para Mac  
(3186807)  
(Importante)  
Microsoft Word 2016 para Mac  
(3186807)  
(Crítico)  
Microsoft Outlook 2016 para Mac  
(3186807)  
(Importante)
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
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3
</td>
<td style="border:1px solid black;">
Pacote de Compatibilidade do Microsoft Office Service Pack 3  
(2597974)  
(Importante)  
Pacote de Compatibilidade do Microsoft Office Service Pack 3  
(3115462)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3115463)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer
</td>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer  
(3054969)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3118297)  
(Crítico)
</td>
</tr>
</table>
 
<sup>[1]</sup>Esta entrada faz referência apenas à versão C2R (Clique para Executar).

 

### Microsoft Office Services e Web Apps

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Serviços do Excel  
(3115112)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Serviços do Excel  
(3115112)  
(Importante)
</td>
</tr>
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
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Serviços do Excel  
(3115119)  
(Importante)  
Serviços de Automação do Word  
(3115466)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(3054862)  
(Crítico)  
Serviços de Automação do Excel  
(3115169)  
(Crítico)  
Serviços de Automação do Word  
(3115443)  
(Crítico)
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
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3115472)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítico**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3118270)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Servidor do Office Online
</td>
<td style="border:1px solid black;">
Servidor do Office Online  
(3118299)  
(Importante)
</td>
</tr>
</table>
 
 

### Microsoft Server Software

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-108**](http://go.microsoft.com/fwlink/?linkid=824829)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(3184711)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-108**](http://go.microsoft.com/fwlink/?linkid=824829)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(3184728)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-108**](http://go.microsoft.com/fwlink/?linkid=824829)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3184736)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Atualização cumulativa 12 do Microsoft Exchange Server 2013
</td>
<td style="border:1px solid black;">
Atualização cumulativa 12 do Microsoft Exchange Server 2013  
(3184736)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Atualização cumulativa 13 do Microsoft Exchange Server 2013
</td>
<td style="border:1px solid black;">
Atualização cumulativa 13 do Microsoft Exchange Server 2013  
(3184736)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-108**](http://go.microsoft.com/fwlink/?linkid=824829)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Atualização cumulativa 1 do Microsoft Exchange Server 2016
</td>
<td style="border:1px solid black;">
Atualização cumulativa 1 do Microsoft Exchange Server 2016  
(3184736)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Atualização cumulativa 2 do Microsoft Exchange Server 2016
</td>
<td style="border:1px solid black;">
Atualização cumulativa 2 do Microsoft Exchange Server 2016  
(3184736)  
(Importante)
</td>
</tr>
</table>
 
### Ferramentas e softwares para desenvolvedores Microsoft

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim             **
</td>
<td style="border:1px solid black;">
[**MS16-109**](http://go.microsoft.com/fwlink/?linkid=824768)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**                                                     
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 quando instalado no Mac  
(3182373)  
(Importante)  
Tempo de Execução do Microsoft Silverlight 5 Developer quando instalado no Mac  
(3182373)  
(Importante)  
Microsoft Silverlight 5 quando instalado em todas as versões com suporte de clientes Microsoft Windows  
(3182373)  
(Importante)  
Tempo de Execução do Microsoft Silverlight 5 Developer quando instalado em todas as versões com suporte de clientes Microsoft Windows  
(3182373)  
(Importante)  
Microsoft Silverlight 5 quando instalado em todas as versões com suporte de servidores Microsoft Windows  
(3182373)  
(Importante)
</td>
</tr>
</table>
 
 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

<span id="sectionToggle3"></span>
Vários recursos estão disponíveis para ajudar administradores a implantar atualizações de segurança.

O MBSA (Microsoft Baseline Security Analyzer) permite que os administradores verifiquem, em sistemas locais e remotos, se há atualizações de segurança ausentes e erros comuns de configuração de segurança.

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

-   [Artigo 894199 da Base de Dados de Conhecimento da Microsoft](https://support.microsoft.com/pt-br/kb/894199): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/pt-br/wsus/bb456965). Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do Microsoft Active Protections Program (MAPP)](http://go.microsoft.com/fwlink/?linkid=215201).

### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de segurança para gerenciamento de atualizações](http://go.microsoft.com/fwlink/?linkid=21168) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [artigo 913086 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e otimizar a infraestrutura de TI e participe de discussões sobre tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164).

### Suporte

O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida de suporte para sua versão de software, visite o site [Ciclo de vida de suporte da Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).

Soluções de segurança para profissionais de TI: [Suporte e solução de problemas de segurança do TechNet](http://technet.microsoft.com/pt-br/security/bb980617)

Ajuda a proteger seu computador executando o Windows contra vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/pt-br/contactus/cu_sc_virsec_master)

Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/pt-br/common/international.aspx)

### Aviso de isenção de responsabilidade

As informações fornecidas na Base de Dados de Conhecimento Microsoft são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

### Revisões

-   V1.0 ([terça-feira, 13 de setembro de 2016](https://technet.microsoft.com/pt-BR/library/bulletin+summary_publisheddate(v=Security.10))): Resumo do boletim publicado.
-   V2.0 (11 de julho de 2017): Para a MS16-111, inclusão do Windows 10 Versão 1703 para sistemas de 32 bits e do Windows 10 Versão 1703 para sistemas com base em x64 à tabela Softwares afetados, uma vez que estes são afetados pela CVE-2016-3305. A Microsoft recomenda que os clientes que executam o Windows 10 Versão 1703 instalem a atualização 4025342 para ficarem protegidos contra essa vulnerabilidade.

*Página gerada em 2017-07-03 16:05-07:00.*
