### Requirements for the project

1. JDK
2. IDE: Netbeans, Eclipse
3. Java EE
4. Oracle or MySQL DB
5. Glassfish/Tomcat Server (Change Port Number if occupied by Oracle or others)

### Servlet
- API that interface and classes to create a web application.
- Need to implement the interfaces to create a Servlet.
- Extends capabiliities of server, response to incoming request by client etc.
- Servlet is a web component deployed on the server to create a dynamic web page.

Note: Servlets are used instead of Common Gateway Interface(CGI) because CGI creates processes and acts as a multi processes which easily overloads the server. In Servlets java itself converts servlets processes to threads and those threads are optimized by the Java Servlets. 

### Request Dispatcher in servlets
Interface that provides the facility of dispatching the request to another resource it may be html, servlet or jsp. Can be used to include content of another resource also.

Two methods:
Forward: Forwards a request from a servlet to another resource (servlet, JSP file, or HTML file)
Include: Includes the content of a resource (servlet, JSP page, or HTML file) in the response

### Servlet Important Parts

1. HTML/CSS/JS for Frontend
2. Java servlet program with backend part & logical methods
3. Web.xml file to control flow of web app & link particular servlet to specific web app page. This makes sure linking part is linked for the IDE and also manages dependencies.