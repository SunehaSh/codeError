# codeError


[RemoteTestNG] detected TestNG version 7.4.0
[Utils] [ERROR] [Error] org.testng.TestNGException: 
Data Provider public java.lang.String[][] SeleniumPackage.SeleniumGrid1.sendData() returned a null value
	at org.testng.internal.MethodInvocationHelper.invokeDataProvider(MethodInvocationHelper.java:148)
	at org.testng.internal.Parameters.handleParameters(Parameters.java:798)
	at org.testng.internal.Parameters.handleParameters(Parameters.java:740)
	at org.testng.internal.ParameterHandler.handleParameters(ParameterHandler.java:59)
	at org.testng.internal.ParameterHandler.createParameters(ParameterHandler.java:38)
	at org.testng.internal.TestInvoker$MethodInvocationAgent.invoke(TestInvoker.java:791)
	at org.testng.internal.TestInvoker.invokeTestMethods(TestInvoker.java:146)
	at org.testng.internal.TestMethodWorker.invokeTestMethods(TestMethodWorker.java:146)
	at org.testng.internal.TestMethodWorker.run(TestMethodWorker.java:128)
	at java.base/java.util.ArrayList.forEach(ArrayList.java:1511)
	at org.testng.TestRunner.privateRun(TestRunner.java:794)
	at org.testng.TestRunner.run(TestRunner.java:596)
	at org.testng.SuiteRunner.runTest(SuiteRunner.java:377)
	at org.testng.SuiteRunner.runSequentially(SuiteRunner.java:371)
	at org.testng.SuiteRunner.privateRun(SuiteRunner.java:332)
	at org.testng.SuiteRunner.run(SuiteRunner.java:276)
	at org.testng.SuiteRunnerWorker.runSuite(SuiteRunnerWorker.java:53)
	at org.testng.SuiteRunnerWorker.run(SuiteRunnerWorker.java:96)
	at org.testng.TestNG.runSuitesSequentially(TestNG.java:1212)
	at org.testng.TestNG.runSuitesLocally(TestNG.java:1134)
	at org.testng.TestNG.runSuites(TestNG.java:1063)
	at org.testng.TestNG.run(TestNG.java:1031)
	at org.testng.remote.AbstractRemoteTestNG.run(AbstractRemoteTestNG.java:115)
	at org.testng.remote.RemoteTestNG.initAndRun(RemoteTestNG.java:251)
	at org.testng.remote.RemoteTestNG.main(RemoteTestNG.java:77)

FAILED: grid
org.testng.TestNGException: 
Data Provider public java.lang.String[][] SeleniumPackage.SeleniumGrid1.sendData() returned a null value
	at org.testng.internal.MethodInvocationHelper.invokeDataProvider(MethodInvocationHelper.java:148)
	at org.testng.internal.Parameters.handleParameters(Parameters.java:798)
	at org.testng.internal.Parameters.handleParameters(Parameters.java:740)
	at org.testng.internal.ParameterHandler.handleParameters(ParameterHandler.java:59)
	at org.testng.internal.ParameterHandler.createParameters(ParameterHandler.java:38)
	at org.testng.internal.TestInvoker$MethodInvocationAgent.invoke(TestInvoker.java:791)
	at org.testng.internal.TestInvoker.invokeTestMethods(TestInvoker.java:146)
	at org.testng.internal.TestMethodWorker.invokeTestMethods(TestMethodWorker.java:146)
	at org.testng.internal.TestMethodWorker.run(TestMethodWorker.java:128)
	at java.base/java.util.ArrayList.forEach(ArrayList.java:1511)
	at org.testng.TestRunner.privateRun(TestRunner.java:794)
	at org.testng.TestRunner.run(TestRunner.java:596)
	at org.testng.SuiteRunner.runTest(SuiteRunner.java:377)
	at org.testng.SuiteRunner.runSequentially(SuiteRunner.java:371)
	at org.testng.SuiteRunner.privateRun(SuiteRunner.java:332)
	at org.testng.SuiteRunner.run(SuiteRunner.java:276)
	at org.testng.SuiteRunnerWorker.runSuite(SuiteRunnerWorker.java:53)
	at org.testng.SuiteRunnerWorker.run(SuiteRunnerWorker.java:96)
	at org.testng.TestNG.runSuitesSequentially(TestNG.java:1212)
	at org.testng.TestNG.runSuitesLocally(TestNG.java:1134)
	at org.testng.TestNG.runSuites(TestNG.java:1063)
	at org.testng.TestNG.run(TestNG.java:1031)
	at org.testng.remote.AbstractRemoteTestNG.run(AbstractRemoteTestNG.java:115)
	at org.testng.remote.RemoteTestNG.initAndRun(RemoteTestNG.java:251)
	at org.testng.remote.RemoteTestNG.main(RemoteTestNG.java:77)


===============================================
    Default test
    Tests run: 1, Failures: 1, Skips: 0
===============================================


===============================================
Default suite
Total tests run: 1, Passes: 0, Failures: 1, Skips: 0
===============================================

