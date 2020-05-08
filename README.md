# ride_tracker_course_exer_chapter4
Original After Chapter 4 excercise files
Runnig in IntelliJ Ultimate

I have added Tomcat following instructions in your another course. See the screenshoot.
Server is running, Hello World! is shown in browser. 
Output when after Tomcat is executed:
C:\dev\tools\apache-tomcat-9.0.34\bin\catalina.bat run
[2020-05-08 05:54:08,505] Artifact ride_tracker.war: Waiting for server connection to start artifact deployment...
Using CATALINA_BASE:   "C:\Users\Pet\AppData\Local\JetBrains\IntelliJIdea2020.1\tomcat\Tomcat_9_0_34_ride_tracker_2"
Using CATALINA_HOME:   "C:\dev\tools\apache-tomcat-9.0.34"
Using CATALINA_TMPDIR: "C:\dev\tools\apache-tomcat-9.0.34\temp"
Using JRE_HOME:        "C:\Program Files\Java\jdk1.8.0_191"
Using CLASSPATH:       "C:\dev\tools\apache-tomcat-9.0.34\bin\bootstrap.jar;C:\dev\tools\apache-tomcat-9.0.34\bin\tomcat-juli.jar"
08-May-2020 17:54:09.298 WARNING [main] org.apache.catalina.core.AprLifecycleListener.init The APR based Apache Tomcat Native library failed to load. The error reported was [C:\dev\tools\apache-tomcat-9.0.34\bin\tcnative-1.dll: Can't load IA 32-bit .dll on a AMD 64-bit platform]
 java.lang.UnsatisfiedLinkError: C:\dev\tools\apache-tomcat-9.0.34\bin\tcnative-1.dll: Can't load IA 32-bit .dll on a AMD 64-bit platform
	at java.lang.ClassLoader$NativeLibrary.load(Native Method)
	at java.lang.ClassLoader.loadLibrary0(ClassLoader.java:1941)
	at java.lang.ClassLoader.loadLibrary(ClassLoader.java:1857)
	at java.lang.Runtime.loadLibrary0(Runtime.java:870)
	at java.lang.System.loadLibrary(System.java:1122)
	at org.apache.tomcat.jni.Library.<init>(Library.java:42)
	at org.apache.tomcat.jni.Library.initialize(Library.java:178)
	at org.apache.catalina.core.AprLifecycleListener.init(AprLifecycleListener.java:197)
	at org.apache.catalina.core.AprLifecycleListener.isAprAvailable(AprLifecycleListener.java:106)
	at org.apache.catalina.connector.Connector.setProtocol(Connector.java:564)
	at org.apache.catalina.connector.Connector.<init>(Connector.java:66)
	at org.apache.catalina.startup.ConnectorCreateRule.begin(ConnectorCreateRule.java:62)
	at org.apache.tomcat.util.digester.Digester.startElement(Digester.java:1178)
	at com.sun.org.apache.xerces.internal.parsers.AbstractSAXParser.startElement(AbstractSAXParser.java:509)
	at com.sun.org.apache.xerces.internal.parsers.AbstractXMLDocumentParser.emptyElement(AbstractXMLDocumentParser.java:182)
	at com.sun.org.apache.xerces.internal.impl.XMLDocumentFragmentScannerImpl.scanStartElement(XMLDocumentFragmentScannerImpl.java:1339)
	at com.sun.org.apache.xerces.internal.impl.XMLDocumentFragmentScannerImpl$FragmentContentDriver.next(XMLDocumentFragmentScannerImpl.java:2784)
	at com.sun.org.apache.xerces.internal.impl.XMLDocumentScannerImpl.next(XMLDocumentScannerImpl.java:602)
	at com.sun.org.apache.xerces.internal.impl.XMLDocumentFragmentScannerImpl.scanDocument(XMLDocumentFragmentScannerImpl.java:505)
	at com.sun.org.apache.xerces.internal.parsers.XML11Configuration.parse(XML11Configuration.java:842)
	at com.sun.org.apache.xerces.internal.parsers.XML11Configuration.parse(XML11Configuration.java:771)
	at com.sun.org.apache.xerces.internal.parsers.XMLParser.parse(XMLParser.java:141)
	at com.sun.org.apache.xerces.internal.parsers.AbstractSAXParser.parse(AbstractSAXParser.java:1213)
	at com.sun.org.apache.xerces.internal.jaxp.SAXParserImpl$JAXPSAXParser.parse(SAXParserImpl.java:643)
	at org.apache.tomcat.util.digester.Digester.parse(Digester.java:1451)
	at org.apache.catalina.startup.Catalina.load(Catalina.java:552)
	at org.apache.catalina.startup.Catalina.load(Catalina.java:603)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.catalina.startup.Bootstrap.load(Bootstrap.java:310)
	at org.apache.catalina.startup.Bootstrap.main(Bootstrap.java:484)

08-May-2020 17:54:09.399 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Server version:        Apache Tomcat/8.0.36
08-May-2020 17:54:09.399 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Server built:          Jun 9 2016 13:55:50 UTC
08-May-2020 17:54:09.399 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Server number:         8.0.36.0
08-May-2020 17:54:09.399 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log OS Name:               Windows 10
08-May-2020 17:54:09.399 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log OS Version:            10.0
08-May-2020 17:54:09.399 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Architecture:          amd64
08-May-2020 17:54:09.399 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Java Home:             C:\Program Files\Java\jdk1.8.0_191\jre
08-May-2020 17:54:09.399 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log JVM Version:           1.8.0_191-b12
08-May-2020 17:54:09.399 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log JVM Vendor:            Oracle Corporation
08-May-2020 17:54:09.399 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log CATALINA_BASE:         C:\Users\Pet\AppData\Local\JetBrains\IntelliJIdea2020.1\tomcat\Tomcat_9_0_34_ride_tracker_2
08-May-2020 17:54:09.399 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log CATALINA_HOME:         C:\dev\tools\apache-tomcat-9.0.34
08-May-2020 17:54:09.400 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Dcom.sun.management.jmxremote=
08-May-2020 17:54:09.400 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Dcom.sun.management.jmxremote.port=1099
08-May-2020 17:54:09.400 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Dcom.sun.management.jmxremote.ssl=false
08-May-2020 17:54:09.400 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Dcom.sun.management.jmxremote.password.file=C:\Users\Pet\AppData\Local\JetBrains\IntelliJIdea2020.1\tomcat\Tomcat_9_0_34_ride_tracker_2\jmxremote.password
08-May-2020 17:54:09.400 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Dcom.sun.management.jmxremote.access.file=C:\Users\Pet\AppData\Local\JetBrains\IntelliJIdea2020.1\tomcat\Tomcat_9_0_34_ride_tracker_2\jmxremote.access
08-May-2020 17:54:09.400 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Djava.rmi.server.hostname=127.0.0.1
08-May-2020 17:54:09.400 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Djdk.tls.ephemeralDHKeySize=2048
08-May-2020 17:54:09.400 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Djava.util.logging.config.file=C:\Users\Pet\AppData\Local\JetBrains\IntelliJIdea2020.1\tomcat\Tomcat_9_0_34_ride_tracker_2\conf\logging.properties
08-May-2020 17:54:09.401 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager
08-May-2020 17:54:09.401 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Djava.endorsed.dirs=C:\dev\tools\apache-tomcat-9.0.34\endorsed
08-May-2020 17:54:09.401 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Dcatalina.base=C:\Users\Pet\AppData\Local\JetBrains\IntelliJIdea2020.1\tomcat\Tomcat_9_0_34_ride_tracker_2
08-May-2020 17:54:09.401 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Dcatalina.home=C:\dev\tools\apache-tomcat-9.0.34
08-May-2020 17:54:09.401 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Command line argument: -Djava.io.tmpdir=C:\dev\tools\apache-tomcat-9.0.34\temp
08-May-2020 17:54:09.544 INFO [main] org.apache.coyote.AbstractProtocol.init Initializing ProtocolHandler ["http-nio-8080"]
08-May-2020 17:54:09.581 INFO [main] org.apache.tomcat.util.net.NioSelectorPool.getSharedSelector Using a shared selector for servlet write/read
08-May-2020 17:54:09.583 INFO [main] org.apache.coyote.AbstractProtocol.init Initializing ProtocolHandler ["ajp-nio-8009"]
08-May-2020 17:54:09.586 INFO [main] org.apache.tomcat.util.net.NioSelectorPool.getSharedSelector Using a shared selector for servlet write/read
08-May-2020 17:54:09.586 INFO [main] org.apache.catalina.startup.Catalina.load Initialization processed in 505 ms
08-May-2020 17:54:09.611 INFO [main] org.apache.catalina.core.StandardService.startInternal Starting service Catalina
08-May-2020 17:54:09.611 INFO [main] org.apache.catalina.core.StandardEngine.startInternal Starting Servlet Engine: Apache Tomcat/8.0.36
08-May-2020 17:54:09.624 INFO [main] org.apache.coyote.AbstractProtocol.start Starting ProtocolHandler ["http-nio-8080"]
08-May-2020 17:54:09.630 INFO [main] org.apache.coyote.AbstractProtocol.start Starting ProtocolHandler ["ajp-nio-8009"]
08-May-2020 17:54:09.632 INFO [main] org.apache.catalina.startup.Catalina.start Server startup in 45 ms
Connected to server
[2020-05-08 05:54:10,097] Artifact ride_tracker.war: Artifact is being deployed, please wait...
08-May-2020 17:54:12.118 INFO [RMI TCP Connection(3)-127.0.0.1] org.apache.jasper.servlet.TldScanner.scanJars At least one JAR was scanned for TLDs yet contained no TLDs. Enable debug logging for this logger for a complete list of JARs that were scanned but no TLDs were found in them. Skipping unneeded JARs during scanning can improve startup time and JSP compilation time.
[2020-05-08 05:54:12,181] Artifact ride_tracker.war: Artifact is deployed successfully
[2020-05-08 05:54:12,181] Artifact ride_tracker.war: Deploy took 2,084 milliseconds
08-May-2020 17:54:19.629 INFO [localhost-startStop-1] org.apache.catalina.startup.HostConfig.deployDirectory Deploying web application directory C:\dev\tools\apache-tomcat-9.0.34\webapps\manager
08-May-2020 17:54:19.715 INFO [localhost-startStop-1] org.apache.jasper.servlet.TldScanner.scanJars At least one JAR was scanned for TLDs yet contained no TLDs. Enable debug logging for this logger for a complete list of JARs that were scanned but no TLDs were found in them. Skipping unneeded JARs during scanning can improve startup time and JSP compilation time.
08-May-2020 17:54:19.723 INFO [localhost-startStop-1] org.apache.catalina.startup.HostConfig.deployDirectory Deployment of web application directory C:\dev\tools\apache-tomcat-9.0.34\webapps\manager has finished in 93 ms



Output after testCreateRide() is run:

org.springframework.web.client.HttpServerErrorException: 500 Internal Server Error

	at org.springframework.web.client.DefaultResponseErrorHandler.handleError(DefaultResponseErrorHandler.java:94)
	at org.springframework.web.client.RestTemplate.handleResponse(RestTemplate.java:700)
	at org.springframework.web.client.RestTemplate.doExecute(RestTemplate.java:653)
	at org.springframework.web.client.RestTemplate.execute(RestTemplate.java:613)
	at org.springframework.web.client.RestTemplate.postForObject(RestTemplate.java:380)
	at com.pluralsight.controller.RestControllerTest.testCreateRide(RestControllerTest.java:24)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
	at org.junit.internal.runners.statements.FailOnTimeout$CallableStatement.call(FailOnTimeout.java:298)
	at org.junit.internal.runners.statements.FailOnTimeout$CallableStatement.call(FailOnTimeout.java:292)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.lang.Thread.run(Thread.java:748)

Process finished with exit code -1




