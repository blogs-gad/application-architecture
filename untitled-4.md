# State of the Union of Microservices and Containers: Docker and the Future

In 20 years, we will look back at the 2010’s as a time of massive development reformation. The late 18th century had the Industrial Revolution, we have the Development Revolution. Lean, lightweight, and rapid development and deployments have taken over the way we look at software development– and for good reason. It’s no longer viable to spend a year working on an application upgrade, climaxing in a massive deployment, followed by countless errors and glitches. We’ve reached greener pastures with [Agile](https://stackify.com/deployment-best-practices/) and [DevOps](https://stackify.com/top-devops-blogs/), and there’s no going back.

Microservices and containers have been at the forefront of this revolution, especially in recent memory. In fact, [DZone found](https://dzone.com/articles/how-developers-use-container-technologies?utm_source=Marketing%20to%20Developers%20eBook%20Campaign&utm_campaign=346271a0cb-AUTOMATION__2&utm_medium=email&utm_term=0_d077fa366a-346271a0cb-62686907) that 42% of developers are currently using container technology.

Unfortunately, 2017 was a rough year for the microservice and container revolution, which had skeptics running the other direction. We believe the future is still bright for microservices and containers, when applied correctly.

## What are Containers and Microservices?

[Microservices](https://stackify.com/what-are-microservices/) are a software architecture in which a larger application is broken down into smaller, single-use services, creating an application suite. The idea is that microservices should focus on one component of the application, and do that one thing exceptionally well.

Containers are the tools and methodology used to organize and develop microservices. Think of a container as the packaging of software, including everything it needs to run: code, runtime, system tools, system libraries, and settings. This container completely isolates the software from any other software in the same environment. This allows for different teams to work on different microservices simultaneously.

Both microservices and containers have become popular tools for DevOps teams due to their flexibility and power. Some teams, however, have struggled to incorporate them and are questioning if they are still viable solutions.

### Why the Concern?

As with all development technologies, concerns and hiccups arise. Teams implementing microservices for the first time might run into the first roadblock and called it quits. Growing pains are a natural part of any development process. The main concerns can be broken down into two categories: the complexity and security.

[![New call-to-action](https://no-cache.hubspot.com/cta/default/207384/a80f5690-310b-4ac1-b3ab-1d5ed4712e2a.png)](https://cta-redirect.hubspot.com/cta/redirect/207384/a80f5690-310b-4ac1-b3ab-1d5ed4712e2a)

#### Complexity

The benefits to microservices and containers are real and abundant, but at what cost? The complexity of having multiple containers, all storing one single service can create a team-wide headache if not done properly from day one. Too many moving parts can be scary. Scaling, reliability, and failsafes become much more complex.

The biggest complexity concern comes from lack of experience. Since microservices and containers are so new, it’s hard to find experienced developers to lead the team. The solution here is to ensure your team has a strong foundation in Agile or DevOps development. If you’re six months into DevOps, maybe this isn’t the right solution yet_._ If you’re six _years_ into DevOps, sit down with your team and layout clear guidelines for implementation.

#### Security

Security becomes more complicated with microservices. Multiple tiny apps means there are more chances for security lapses, and it is that much more difficult to identify the root problem. The solution, in short, is to [not reinvent the wheel when it comes to security](https://techbeacon.com/8-best-practices-microservices-security). Using a tool like [Retrace](https://stackify.com/retrace/) allows your team to identify when a specific deployment went out and how it affected different metrics.

Containers actually represent an upgrade in security in many cases. Containers, even lightly built, are by nature far more secure than even a robust VM \(virtual machine\) or a physical server. Still, it’s crucial that your containers are built with security at the top of mind. On top of Docker, utilize third-party [container tools](https://stackify.com/top-docker-tools/) to ensure high quality and high security. Since microservices are light and relatively easy to roll out, rolling out patches are even lighter.

## Is Docker \(Still\) the Future?

[Docker](https://www.docker.com/what-docker) is not only the most popular container platform, but also one of the [most funded](https://www.bloomberg.com/news/articles/2017-08-09/docker-is-said-to-be-raising-funding-at-1-3-billion-valuation) Silicon Valley startups in recent years. Docker has been at the forefront of the container movement and has a well-earned reputation of being best in class.

Still, 2017 was not a great year for Docker. Not only did they face [serious controversy](http://www.businessinsider.com/a-guy-accused-of-harassing-a-female-developer-gets-ejected-2017-5), but they actively resisted industry change in the form of Kubernetes. Resisting change can be the downfall of any company, but it’s particularly deadly in tech.

Designed by Google, Kubernetes has emerged as a solution to several container shortcomings. It is not necessarily a container alternative, but a container extension. Kubernetes is a platform to test, deploy, and monitor containerized microservices. Utilizing Kubernetes can help alleviate scalability, reliability, and performance issues common with containers.

From Kubernetes’ 2014 conception up until late 2017, Docker resisted all things Kubernetes. Docker introduced Docker Swarm, a direct competitor to Kubernetes, and did not support Kubernetes integration. This was the infamous start of the “[Is Docker Dead?](https://chrisshort.net/docker-inc-is-dead/)” movement.

As of October 2017, however, [Docker has fully embraced the Kubernetes way](https://www.docker.com/kubernetes). Developers can now build applications with Docker and use Kubernetes \(or Swarm\) to test and deploy.

![Developers can now build applications with Docker and use Kubernetes \(or Swarm\) to test and deploy.](https://stackify.com/wp-content/uploads/2018/02/word-image-6.jpeg)

_Photo source:_ [_https://www.docker.com/kubernetes_](https://www.docker.com/kubernetes)

So, is Docker dead? No, absolutely not. Docker is still the leading microservice containerization platform. Kubernetes didn’t kill Docker; Kubernetes _saved_ Docker.

## Set Your Team Up for Success with Microservices and Containers

Microservices and containers are still the future. As more and more enterprises continue to perfect the process, small to medium software companies are getting their microservice sea legs as well. There are a few key principles that teams can follow to get the most from microservices.

### Perfect the CI/CD pipeline

Adopting microservices, at its core, requires a complex continuous integration and continuous deployment process to be in place. [According to Petrica Martinescu, lead architect at Tremend](https://dzone.com/articles/the-future-of-containers-and-microservices), if you aren’t currently running any sort of [CI/CD pipeline](https://stackify.com/fundamentals-of-the-cd-ci-pipeline/), take some time to get that in place before moving to microservices.

### Incorporate Kubernetes with your Docker containers

There should be no subtlety surrounding the fact that Dockers gave in to the Kubernetes hype. Implementing Kubernetes on top of your Docker containers will give you access to tools and resources previously difficult to learn and acquire.

### Monitor Errors

One of the hardships of microservices is pinpointing where errors occur. Use a performance monitoring tool like [Retrace](https://stackify.com/retrace/) to monitor your containers and microservices. Understanding exactly when and where an error is occurring is essential to an effective and efficient microservices architecture. With Retrace, you can easily identify which deployment in what microservice is causing the error. Once identified, rolling back \(or patching\) is fast and easy.

## Revolutionize Your DevOps Team, Revolutionize the World

Entering the world of microservices and containers will revolutionize your DevOps team, and in turn, revolutionize your business. Microservices encourage experimentation and limit the risk of bold new releases since all of the software is isolated in its own container. As software companies aim for [faster deployments](https://stackify.com/software-trends-for-2018-continuous-delivery/), these tools will become vital parts of the DevOps toolkit.

We are full speed ahead with containers and microservices. You should be, too. Now get out there, build something great, and revolutionize the world!

