2025-02-06 14:48:27,404 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:196) - ■SoapSender#fire() - start
2025-02-06 14:48:27,404 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:397) - ■SoapSender#makeCsvFile() - start
2025-02-06 14:48:27,404 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SQLFinder.java:113) - findByNamedSQL(String) - start
2025-02-06 14:48:27,404 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SQLFinder.java:114) - SQL名=sql.tekkyohinnhennnoujyohokyoutusyutoku
2025-02-06 14:48:27,406 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SQLFinder.java:150) - findByNamedSQL(String) - end
2025-02-06 14:48:27,406 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (N5BuiSoapSendCommonEntity.java:144) - jp.co.nttcom.scorpion.core.db.query.Query@3b8ffde2[sql=SELECT A.SOAP_NUM, A.GPNUM, '0' AS CTRL, A.SRICLS, A.HNUYTIDEN, A.KJI, A.KOS_SKSCD, A.KOS_HKCD, A.HNUM_TAT, A.HNUM_TEL, TO_CHAR(A.HNUYT_YMD, 'YYYYMMDD') AS HNUYT_YMD, A.HIS_CD, A.CNT_CD, A.KST_SCD, A.KST_HKCD FROM N5_BUISOAPHNU_H A WHERE A.SOAP_NUM = ? ORDER BY SOAP_NUM, GPNUM,params={121175}]
2025-02-06 14:48:27,406 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (XADAO.java:103) - JNDI_NAME=N502
2025-02-06 14:48:27,406 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (AbstractDAO.java:320) - select(Query) - start
2025-02-06 14:48:27,406 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (XADAO.java:224) - getConnection() - start
2025-02-06 14:48:27,406 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (XADAO.java:242) - getConnection() - end
2025-02-06 14:48:27,406 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (AbstractDAO.java:348) - select(Query) - end
2025-02-06 14:48:27,406 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:527) - ●●propertiesName=[02.cm_bu_jiko_ippan_send]
2025-02-06 14:48:27,407 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:528) - ●●path=[/home/KOUKAI02/TASYS_WEB/ECCSS/IPPAN/SEND/]
2025-02-06 14:48:27,407 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:456) - ■SoapSender#openCsvFile() Open Csvfile for SoapSend.path=[/home/KOUKAI02/TASYS_WEB/ECCSS/IPPAN/SEND/S2IP121175AC0B30SP20250206144827.txt]
2025-02-06 14:48:27,421 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:469) - ■SoapSender#openCsvFile() -end
2025-02-06 14:48:27,422 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SQLFinder.java:113) - findByNamedSQL(String) - start
2025-02-06 14:48:27,422 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SQLFinder.java:114) - SQL名=sql.tekkyohinnhennnoujyohomeisaisyutoku
2025-02-06 14:48:27,422 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SQLFinder.java:150) - findByNamedSQL(String) - end
2025-02-06 14:48:27,422 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (N5BuiSoapSendCommonEntity.java:180) - jp.co.nttcom.scorpion.core.db.query.Query@1266482a[sql=SELECT A.GPNUM, A.SEQNUM, '1' AS CTRL, A.HNUYTIDENMEIBAN, A.BUTU_CD, A.AB_LEN, A.STIJIK001, A.STIJIK002, A.STIJIK003, A.MEMO, A.ZSBFLG, A.SRO, A.GAK, A.SKS_CNT_CD, A.KOJ_CLS, A.SKS_CD, A.SKJBAN, A.SKS_KKN, A.SKS_HNK, A.SKS_BIL_CD, A.NS_BAN, A.SASOKNO, TRIM(TO_CHAR(A.YND, 'YYYY')) AS YND, A.HCCHNO, TRIM(TO_CHAR(A.KOJ_YMD, 'YYYY-MM-DD')) AS KOJ_YMD, A.SONO, A.SKS_TEL, A.BUTREC, A.SOAP_NUM, A.SKS_KJR FROM N5_BUISOAPHNU_D A WHERE A.SOAP_NUM = ? AND A.GPNUM = ? ORDER BY A.SOAP_NUM, A.GPNUM, A.SEQNUM,params={121175,1}]
2025-02-06 14:48:27,422 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (XADAO.java:103) - JNDI_NAME=N502
2025-02-06 14:48:27,422 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (AbstractDAO.java:320) - select(Query) - start
2025-02-06 14:48:27,422 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (XADAO.java:224) - getConnection() - start
2025-02-06 14:48:27,422 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (XADAO.java:242) - getConnection() - end
2025-02-06 14:48:27,423 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (AbstractDAO.java:348) - select(Query) - end
2025-02-06 14:48:27,430 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:437) - ■SoapSender#makeCsvFile() - end
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:527) - ●●propertiesName=[02.cm_bu_jiko_ippan_send]
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:528) - ●●path=[/home/KOUKAI02/TASYS_WEB/ECCSS/IPPAN/SEND/]
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:527) - ●●propertiesName=[02.cm_bu_jiko_ippan_send]
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:528) - ●●path=[/home/KOUKAI02/TASYS_WEB/ECCSS/IPPAN/SEND/]
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:214) - ■SoapSender#fire() - EAIClient 設定情報------------------
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:215) - ■SoapSender#fire() -   ・SOAP種別    =[AC0B30SP]
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:216) - ■SoapSender#fire() -   ・組織ｺｰﾄﾞ    =[20150621]
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:217) - ■SoapSender#fire() -   ・組織付加ｺｰﾄﾞ=[131]
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:527) - ●●propertiesName=[02.cm_bu_jiko_ippan_send]
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:528) - ●●path=[/home/KOUKAI02/TASYS_WEB/ECCSS/IPPAN/SEND/]
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:218) - ■SoapSender#fire() -   ・ﾌｧｲﾙ        =[/home/KOUKAI02/TASYS_WEB/ECCSS/IPPAN/SEND/S2IP121175AC0B30SP20250206144827.txt]
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:219) - ■SoapSender#fire()
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:222) - ■SoapSender#fire() - EAIClient calling!.......
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:527) - ●●propertiesName=[02.cm_bu_jiko_ippan_send]
2025-02-06 14:48:27,431 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (SoapSender.java:528) - ●●path=[/home/KOUKAI02/TASYS_WEB/ECCSS/IPPAN/SEND/]
2025-02-06 14:48:27,432 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (EAIClient.java:522) -  start sendData=jp.co.nttcom.nn.eai.ea.tb.bean.ButuExecSysSendDataASync@2de4c25,file=/home/KOUKAI02/TASYS_WEB/ECCSS/IPPAN/SEND/S2IP121175AC0B30SP20250206144827.txt,sendFileCharSet=UTF8
2025-02-06 14:48:27,434 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (CallCommand.java:129) - CallCommand#callRemoteShell() cmd=/home/CCuser/CC0E/COMM/bin/cm70sK06.sh %1% %2% %3% %4% %5% params=/share01/KOUKAI02/TASYS_WEB/ECCSS/IPPAN/SEND/S2IP121175AC0B30SP20250206144827.txt,/share01/KOUKAI02/TASYS_WEB/ECCSS/IPPAN/SEND/S2IP121175AC0B30SP20250206144827.txt,UTF8,SJIS,BUTSU
2025-02-06 14:48:27,434 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (CallCommand.java:130) - CallCommand#callRemoteShell() callCommand=/home/CCuser/CC0E/COMM/bin/cm70sK06.sh /share01/KOUKAI02/TASYS_WEB/ECCSS/IPPAN/SEND/S2IP121175AC0B30SP20250206144827.txt /share01/KOUKAI02/TASYS_WEB/ECCSS/IPPAN/SEND/S2IP121175AC0B30SP20250206144827.txt UTF8 SJIS BUTSU
2025-02-06 14:48:27,439 DEBUG [Thread-222] (CallCommand.java:203) - CallCommand#ProcessWatchThread#run() start.
2025-02-06 14:48:27,543 DEBUG [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (CallCommand.java:141) - コマンド実行時の戻り値 = 2
2025-02-06 14:48:27,544 ERROR [[ACTIVE] ExecuteThread: '4' for queue: 'weblogic.kernel.Default (self-tuning)'] (TraceLog.java:98) - 
jp.co.nttcom.scorpion.exception.SystemException: cm70sK06.shでエラー発生 return code=2
	at jp.co.nttcom.nn.base.util.FileUtil.convertFileCharSet(FileUtil.java:947)
	at jp.co.nttcom.nn.base.util.FileUtil.convertFileCharSet(FileUtil.java:837)
	at jp.co.nttcom.nn.base.eai.client.EAIClient.getFileBinaryArray(EAIClient.java:625)
	at jp.co.nttcom.nn.base.eai.client.EAIClient.requestForButuExecSysASync(EAIClient.java:535)
	at jp.co.nttcom.nn.business.n5.n532.common.SoapSender.fire(SoapSender.java:228)
	at jp.co.nttcom.nn.business.n5.n532.n5328X40.logic.RikatuyoNinteiSendSoapLogic.sendSoap(RikatuyoNinteiSendSoapLogic.java:2511)
	at jp.co.nttcom.nn.business.n5.n532.n5328X40.logic.RikatuyoNinteiSendSoapLogic.sendHenkoIkkatsu(RikatuyoNinteiSendSoapLogic.java:1817)
	at jp.co.nttcom.nn.business.n5.n532.n5328X40.logic.RikatuyoNinteiBuppinItiranLogic.sendHenkoIkkatsu(RikatuyoNinteiBuppinItiranLogic.java:1378)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.base/java.lang.reflect.Method.invoke(Method.java:566)
	at jp.co.nttcom.scorpion.core.control.Reflection.runMethod(Reflection.java:297)
	at jp.co.nttcom.scorpion.core.control.BusinessExecutor.execute(BusinessExecutor.java:261)
	at jp.co.nttcom.nn.base.online.gw.Gateway.doPost(Gateway.java:395)
	at javax.servlet.http.HttpServlet.service(HttpServlet.java:665)
	at javax.servlet.http.HttpServlet.service(HttpServlet.java:750)
	at weblogic.servlet.internal.StubSecurityHelper$ServletServiceAction.run(StubSecurityHelper.java:295)
	at weblogic.servlet.internal.StubSecurityHelper$ServletServiceAction.run(StubSecurityHelper.java:260)
	at weblogic.servlet.internal.StubSecurityHelper.invokeServlet(StubSecurityHelper.java:137)
	at weblogic.servlet.internal.ServletStubImpl.execute(ServletStubImpl.java:353)
	at weblogic.servlet.internal.TailFilter.doFilter(TailFilter.java:25)
	at weblogic.servlet.internal.FilterChainImpl.doFilter(FilterChainImpl.java:82)
	at jp.co.nttcom.nn.base.online.gw.CharsetFilter.doFilter(CharsetFilter.java:94)
	at weblogic.servlet.internal.FilterChainImpl.doFilter(FilterChainImpl.java:82)
	at weblogic.servlet.internal.WebAppServletContext$ServletInvocationAction.wrapRun(WebAppServletContext.java:3869)
	at weblogic.servlet.internal.WebAppServletContext$ServletInvocationAction.run(WebAppServletContext.java:3832)
	at weblogic.security.acl.internal.AuthenticatedSubject.doAs(AuthenticatedSubject.java:344)
	at weblogic.security.service.SecurityManager.runAsForUserCode(SecurityManager.java:197)
	at weblogic.servlet.provider.WlsSecurityProvider.runAsForUserCode(WlsSecurityProvider.java:203)
	at weblogic.servlet.provider.WlsSubjectHandle.run(WlsSubjectHandle.java:71)
	at weblogic.servlet.internal.WebAppServletContext.processSecuredExecute(WebAppServletContext.java:2505)
	at weblogic.servlet.internal.WebAppServletContext.doSecuredExecute(WebAppServletContext.java:2354)
	at weblogic.servlet.internal.WebAppServletContext.securedExecute(WebAppServletContext.java:2329)
	at weblogic.servlet.internal.WebAppServletContext.execute(WebAppServletContext.java:2307)
	at weblogic.servlet.internal.ServletRequestImpl.runInternal(ServletRequestImpl.java:1798)
	at weblogic.servlet.internal.ServletRequestImpl.run(ServletRequestImpl.java:1752)
	at weblogic.servlet.provider.ContainerSupportProviderImpl$WlsRequestExecutor.run(ContainerSupportProviderImpl.java:272)
	at weblogic.invocation.ComponentInvocationContextManager._runAs(ComponentInvocationContextManager.java:352)
	at weblogic.invocation.ComponentInvocationContextManager.runAs(ComponentInvocationContextManager.java:337)
	at weblogic.work.LivePartitionUtility.doRunWorkUnderContext(LivePartitionUtility.java:57)
	at weblogic.work.PartitionUtility.runWorkUnderContext(PartitionUtility.java:41)
	at weblogic.work.SelfTuningWorkManagerImpl.runWorkUnderContext(SelfTuningWorkManagerImpl.java:651)
	at weblogic.work.ExecuteThread.execute(ExecuteThread.java:420)
	at weblogic.work.ExecuteThread.run(ExecuteThread.java:360)
