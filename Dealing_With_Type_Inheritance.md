**wsdl2html**  automatically deals with inheritance among stub classes or schema types. Product/FunProduct/NotFunProduct shown in the following diagram is an example of inheritance among stub classes.

![https://wsdl2html.googlecode.com/svn/trunk/wsdl2html/doc/image/product.png](https://wsdl2html.googlecode.com/svn/trunk/wsdl2html/doc/image/product.png)

Note:
> B is considered the child type of A, if and only if
> > a. A is assignable from B in terms of Java language


> b. and A is annotated as @XmlSeeAlso(B.class)