# Web Application Architecture Part-1 \(Guide to become Full Stack Developer\)

![](https://miro.medium.com/max/2000/1*sp68dtNAtjUEgFfBp0qIHQ.png)

So, till now we have gone through all the areas of designing & development be it coding or database. Now we will be going through Web Application Architecture. This can be considered as the base/foundation of our final product, where our product will be hosted and running.

_**What is Web Application Architecture?**_

Web Application Architecture is a framework that is comprised of the relationships and interactions between application components, such as middleware systems, user interfaces, and databases. In layman term, this is a pattern of interaction between web application components such as web server, database server, load balancer, etc.

The story begins by clicking the URL, When a user types in any URL and taps “Go,” the browser will find the URL over the network, the server will then send the data to the browser, then that data is executed by the browser to display the requested page. Now, the user gets to interact with the website. Of course, all of these actions are executed within a matter of seconds. Otherwise, users wouldn’t bother with websites.

Ever wondered!!, How all these things happen within a fraction of seconds? Is this just because of the code which has been parsed by the browser? Or is it because the website is made of smaller resolution images? Or is it because a powerful machine is used for executing things?

Actually, all of the above factors are responsible in a way they are used and linked together. These factors are known as the components. Web Application Architecture includes all components, sub-components and external application interchanges for an entire web application \(Final Product\).

As the tech world continues to evolve, applications are considered a spearhead in this transformational process. Modern application architecture and its development are continuously improving in both of its front-end and back-end capabilities. Specifically, on the back end or server side, there are numerous application development architecture approaches that are emerging to cope with and solve current development needs such as microservices, serverless architectures, and single page applications

### Components of Web Applications Architectures <a id="4822"></a>

![](https://miro.medium.com/max/3086/1*Hj6SXshSKb2COtcNWhlh1w.png)

Example of Microsoft Azure Cloud Architecture for Web Application

As previously stated, Web application architectures are comprised of several components that help build its digital makeup. These components can be categorized into two areas: user interface app components and structural components.

1. User interface app components refer to web pages displaying dashboards, logs, notifications, configuration settings, and more. They are not relevant to the structural development of the application and are more user interface/experience oriented.
2. The structural components, which are the real meat of the app development process, are:

> **A. The web browser or client.**
>
> The web browser or client is the interface rendition of a web app functionality, with which the user interacts with. This content delivered to the client can be developed using HTML, JavaScript, and CSS and doesn’t require operating system related adaptations. In essence, the web browser or client manages how end users interact with the application.
>
> **B. The web application server.**
>
> The web application server manages business logic and data persistence and can be built using PHP, Python, Java, Ruby, .NET, Node.js, among other languages. It’s comprised of at least a centralized hub or control center to support multi-layer applications.
>
> **C. The database server.**
>
> The database server provides and stores relevant data for the application. Additionally, it may also supply the business logic and other information that is managed by the web application server.

Talking more about structural development there are different approaches to creating a structural design, this all depends on the scope of work and the area of work \(Like e-Commerce, Chat Application, etc\). In the next part, we will discussing more about these types of architectures.

