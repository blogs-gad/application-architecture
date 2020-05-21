# What is N-Tier Architecture? Examples, Tutorials & More

Great products are often built on multi-tier architecture – or n-tier architecture, as it’s often called. At [Stackify](https://stackify.com/), we love to talk about the many tools, resources, and concepts that can help you build better. \(check out more of our tips and tricks [here](https://stackify.com/developers/)\)  So in this post, we’ll discuss n-tier architecture, how it works, and what you need to know to build better products using multi-tier architecture.

## Definition of N-Tier Architecture

N-tier architecture is also called multi-tier architecture because the software is engineered to have the processing, data management, and presentation functions physically and logically separated.  That means that these different functions are hosted on several machines or clusters, ensuring that services are provided without resources being shared and, as such, these services are delivered at top capacity.  The “N” in the name n-tier architecture refers to any number from 1.

Not only does your software gain from being able to get services at the best possible rate, but it’s also easier to manage.  This is because when you work on one section, the changes you make will not affect the other functions.  And if there is a problem, you can easily pinpoint where it originates.

### A More In-Depth Look at N-Tier Architecture

N-tier architecture would involve dividing an application into [three different tiers](https://msdn.microsoft.com/en-us/library/bb384398.aspx).  These would be the

1. logic tier,
2. the presentation tier, and
3. the data tier.

![N-Tier Architecture](https://stackify.com/wp-content/uploads/2017/05/N-Tier-Architecture-min.png)

_Image via_ [_Wikimedia Commons_](https://commons.wikimedia.org/wiki/File:Overview_of_a_three-tier_application_vectorVersion.svg)

The separate physical location of these tiers is what differentiates n-tier architecture from the model-view-controller framework that only separates presentation, logic, and data tiers in concept.  N-tier architecture also differs from MVC framework in that the former has a middle layer or a logic tier, which facilitates all communications between the different tiers.  When you use the MVC framework, the interaction that happens is triangular; instead of going through the logic tier, it is the control layer that accesses the model and view layers, while the model layer accesses the view layer.  Additionally, the control layer makes a model using the requirements and then pushes that model into the view layer.

This is not to say that you can only use either the MVC framework or the n-tier architecture.  There are a lot of software that brings together these two frameworks.  For instance, you can use the n-tier architecture as the overall architecture, or use the MVC framework in the presentation tier.

### What are the Benefits of N-Tier Architecture?

There are several benefits to using n-tier architecture for your software.  These are scalability, ease of management, flexibility, and security.

* **Secure:** You can secure each of the three tiers separately using different methods.
* **Easy to manage:** You can manage each tier separately, adding or modifying each tier without affecting the other tiers.
* **Scalable:** If you need to add more resources, you can do it per tier, without affecting the other tiers.
* **Flexible:** Apart from isolated scalability, you can also [expand each tier](https://www.codeproject.com/Articles/430014/N-Tier-Architecture-and-Tips#Tier%20and%20Layer%20Relationship) in any manner that your requirements dictate.

In short, with n-tier architecture, you can adopt new technologies and add more components without having to rewrite the entire application or redesigning your whole software, thus making it easier to scale or maintain.  Meanwhile, in terms of security, you can store sensitive or confidential information in the logic tier, keeping it away from the presentation tier, thus making it more secure.

Other benefits include:

* **More efficient development.** N-tier architecture is very friendly for development, as different teams may work on each tier.  This way, you can be sure the design and presentation professionals work on the presentation tier and the database experts work on the data tier.
* **Easy to add new features.** If you want to introduce a new feature, you can add it to the appropriate tier without affecting the other tiers.
* **Easy to reuse.** Because the application is divided into independent tiers, you can easily reuse each tier for other software projects.  For instance, if you want to use the same program, but for a different data set, you can just replicate the logic and presentation tiers and then create a new data tier.

### How It Works and Examples of N-Tier Architecture

When it comes to n-tier architecture, a [three-tier architecture](http://tutorials.jenkov.com/software-architecture/n-tier-architecture.html) is fairly common.  In this setup, you have the presentation or GUI tier, the data layer, and the application logic tier.

**The application logic tier.**  The application logic tier is where all the “thinking” happens, and it knows what is allowed by your application and what is possible, and it makes other decisions.  This logic tier is also the one that writes and reads data into the data tier.

**The data tier.** The data tier is where all the data used in your application are stored.  You can securely store data on this tier, do transaction, and even search through volumes and volumes of data in a matter of seconds.

**The presentation tier.**  The presentation tier is the user interface.  This is what the software user sees and interacts with.  This is where they enter the needed information.  This tier also acts as a go-between for the data tier and the user, passing on the user’s different actions to the logic tier.

Just imagine surfing on your favorite website.  The presentation tier is the Web application that you see.  It is shown on a Web browser you access from your computer, and it has the CSS, JavaScript, and HTML codes that allow you to make sense of the Web application.  If you need to log in, the presentation tier will show you boxes for username, password, and the submit button.  After filling out and then submitting the form, all that will be passed on to the logic tier.  The logic tier will have the JSP, Java Servlets, Ruby, PHP and other programs.  The logic tier would be run on a Web server.  And in this example, the data tier would be some sort of database, such as a MySQL, NoSQL, or PostgreSQL database.  All of these are run on a separate database server.  Rich Internet applications and mobile apps also follow the same three-tier architecture.

And there are n-tier architecture models that have [more than three tiers](http://stackoverflow.com/questions/10761440/example-of-4-tier-for-n-tier-architecture).  Examples are applications that have these tiers:

* **Services** – such as print, directory, or database services
* **Business domain** – the tier that would host Java, DCOM, CORBA, and other application server object.
* **Presentation tier**
* **Client tier** – or the thin clients

One good instance is when you have an enterprise service-oriented architecture.  The enterprise service bus or ESB would be there as a separate tier to facilitate the communication of the basic service tier and the business domain tier.

### Considerations for Using N-Tier Architecture for Your Applications

Because you are going to work with several tiers, you need to make sure that network bandwidth and hardware are fast.  If not, the application’s performance might be slow.  Also, this would mean that you would have to pay more for the network, the hardware, and the maintenance needed to ensure that you have better network bandwidth.

Also, use as fewer tiers as possible.  Remember that each tier you add to your software or project means an added layer of complexity, more hardware to purchase, as well as higher maintenance and deployment costs.  To make your n-tier applications make sense, it should have the minimum number of tiers needed to still enjoy the scalability, security and other benefits brought about by using this architecture.  If you need only three tiers, don’t deploy four or more tiers.

### N-Tier Architecture Tutorials and Resources

For more information on n-tier architecture, check out the following resources and tutorials:

* [Walkthrough: Creating an N-Tier Data Application](https://msdn.microsoft.com/en-us/library/bb384570.aspx)
* [N-Tier Architecture – System Concepts & Tips](http://www.guru99.com/n-tier-architecture-system-concepts-tips.html)
* [Distributed Architecture](https://www.tutorialspoint.com/software_architecture_design/distributed_architecture.htm)
* [N-Tier Architecture. ASP.NET Example](https://dotnetdaily.net/featured/n-tier-architecture-asp-net)
* [n-layered Architecture Using Entity Framework, Generic Repository And Unit-Of-Work](http://www.c-sharpcorner.com/article/n-layered-architecture-using-entity-framework-generic-repository-and-unit-of-wo/)
* [Creating N-Tier ASP.NET Web API application](https://weblogs.asp.net/sukumarraju/creating-n-tier-web-api-application)
* [NET N-Layered Applications – Introduction \(Part 1\)](http://imar.spaanjaars.com/573/aspnet-n-layered-applications-introduction-part-1)
* [DBMS – Architecture](https://www.tutorialspoint.com/dbms/dbms_architecture.htm)

