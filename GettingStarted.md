1. [Download](http://code.google.com/p/wsdl2html/downloads/list) it

2. Extract it. Add wsdl2html-xxx.jar to the classpath of which you are going to run a java program.

3. Also add commons-io-1.4.jar, commons-lang-2.4.jar and freemarker-2.3.16 to the classpath

4. Generate HTML specs by running the main program:
**`org.jaxws.wsdl2html.ui.Wsdl2HtmlMain     wsdlUrl  [outputDir]`**


5. To Generate HTML specs from jax-ws stubs, run the main program:  `org.jaxws.stub2html.ui.Stub2HtmlSimpleMain` , with your web service stub as its argument.
> (Note: jax-ws-stub2html-xxx-exampleWebService.jar has a sample web-service-stub --   org.jaxws.stub2html.exampleWebService.OrderSOAPService)

