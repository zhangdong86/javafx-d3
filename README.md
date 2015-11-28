# javafx-d3 #

Provides a Java API for using the JavaScript library d3.js with JavaFx Applications.

Many thanks to the authors of the projects **gwt-d3** [[1]](https://github.com/gwtd3/gwt-d3 "gwt-d3")  and **d3.js** [[2]](http://d3js.org "d3.js") !!! 

Most of the source code of javafx-d3 originates from gwt-d3. If you use the original
gwt-d3 project your result will be a web application that is written in JavaScript. 

If you use javafx-d3, your aim is to end up with Java code that can be applied 
for JavaFx desktop applications.

![alt tag](https://github.com/stefaneidelloth/javafx-d3/blob/master/javafx-d3-demo/src/test/resources/javafxd3.png)

## Current state

* Most code from gwt-d3 has been transformed.
* The remaining parts will be implemented/corrected on request. 
* So please create a feature request or issue ticket if you have a need in that direction.

=> Please also feel free to jump in and directly contribute to the code of javafx-d3.  

## How it works: ##

Javafx-d3 uses the JavaFx WebView [[3]](https://docs.oracle.com/javafx/2/webview/jfxpub-webview.htm "JavaFx WebView") to display an html page and to execute JavaScript.
The JavaScript library d3.js is injected into the WebView. The communication between Java and JavaScript is based on  
so called JSObjects [[4]](http://docstore.mik.ua/orelly/web/jscript/ch19_06.html "Using JavaScript from Java"). 

With this straregy of javafx-d3 you are able to use the full power of d3.js for your Java desktop applications. 

## How to get started: ##

* Get the source code 
* You can use the main folder as an Eclipse workspace including two projects:
* Import the two Eclipse Maven projects **javafx-d3** and **javafx-d3-demo**
* Build the maven projects
* Run the demo suite **com.github.javafxd3.demo.client.JavaFxD3DemoSuite**
* If you do not get javafx-d3 up and running please create an issue ticket. 

## License ##

This project is licensed under BSD:
* javafx-d3: https://github.com/stefaneidelloth/javafx-d3/blob/master/LICENSE

Javafx-d3 is based on third party code which is licensed under BSD as well:
* d3.js: https://github.com/mbostock/d3/blob/master/LICENSE
* gwt-d3: https://github.com/gwtd3/gwt-d3/blob/master/LICENSE

----  
 
[1]: gwt-d3: https://github.com/gwtd3/gwt-d3<br>
[2]: d3.js: http://d3js.org<br>
[3]: JavaFx WebView: https://docs.oracle.com/javafx/2/webview/jfxpub-webview.htm<br>
[4]: Using JavaScript from Java: http://docstore.mik.ua/orelly/web/jscript/ch19_06.html<br>
[5]: d3.js gallery: https://github.com/mbostock/d3/wiki/Gallery<br>

