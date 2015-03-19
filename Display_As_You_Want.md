The design go a MVC approach, based on which you can create your own format of the specs.

1. Get the models
```
	WebServiceStubSet serviceStubSet = WebServiceStubSetFactory.createWebServiceStubSet(webServiceClass);

```

2. Display the models using "DisplayEngine"
```
for (WebMethodStubSet methodStubSet : serviceStubSet.getMethodStubs()) {
			 
			DisplayEngine displayEnige = ... 
			String html = display.displayWebMethod();
			printHtml(html); 
		}
```

3. DisplayEngine is abstract. Create your own implementation and display the methods in any format your want (in HTML, Freemarker, Excel, etc.)