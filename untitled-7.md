# What Is Function-as-a-Service? Serverless Architectures Are Here!

![](https://stackify.com/wp-content/uploads/2017/05/no-servers-793x397.jpg)

It has never been a better time to be a developer! Thanks to [cloud computing](https://stackify.com/4-ways-cloud-influenced-app-troubleshooting/), deploying our applications is much easier than it used to be. How we deploy our apps continues to evolve thanks to cloud hosting, Platform-as-a-Service \(PaaS\), and now Function-as-a-Service.

## What is Function-as-a-Service \(FaaS\)?

FaaS is the concept of serverless computing via serverless architectures. Software developers can leverage this to deploy an individual “function”, action, or piece of business logic. They are expected to start within milliseconds and process individual requests and then the process ends.

**Principles of FaaS:**

* Complete abstraction of servers away from the developer
* Billing based on consumption and executions, not server instance sizes
* Services that are event-driven and instantaneously scalable

![Timeline of moving to FaaS](https://stackify.com/wp-content/uploads/2017/05/what-is-function-as-a-service-serverless-architectures-are-here-11196.png)

At the basic level, you could describe them as a way to run some code when a “thing” happens. Here is a simple example below from Azure Functions. Shows how easy it is to process an HTTP request as a “Function”.

```text
using System.Net;

public static async Task Run(HttpRequestMessage req, TraceWriter log)
{
    log.Info("C# HTTP trigger function processed a request.");

    // Get request body
    dynamic data = await req.Content.ReadAsAsync
```

