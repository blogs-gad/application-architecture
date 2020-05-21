# Tips for Making Agile Less Fragile

Agile. You can’t avoid hearing it wherever you go even though “agile” means different things to different people.

In some shops, agile means extremely small sprints that are [continuously deployed](https://stackify.com/continuous-delivery-vs-continuous-deployment-vs-continuous-integration/), sometimes multiple times per day. For others, it means the same old waterfall-style development, but they have burndown charts, daily stand-up meetings, and maybe someone with the title of “SCRUM Master.”   Regardless of how teams define agile, their common goal is increased velocity meaning faster product delivery and better ROI.

Purely agile teams and barely agile teams have something else in common:  They forget to consider agile support.

[Agile development](https://stackify.com/agile-methodology/) and agile support go hand-in-hand.  Agile development can only save you so much time if you’re wasting time on the backend trying to [pinpoint errors](https://stackify.com/error-monitoring) and correct them.  I don’t know any developers who look forward to rework.  And they don’t exactly look forward to going to IT with their problems because IT doesn’t want to hear them.  IT is busy.  That means, you have to do more application support in addition to everything else you’re already doing in the same number of hours.

As you well know, building great software means more than just creating cool or useful features.  Users want a great experience.  And yet there you are:  You’re developing code and hopefully releasing it often but your shrinking development cycle may not account for the proper level of [load](https://stackify.com/what-is-load-testing/), acceptance and other testing because management thinks you should spend all of your time coding.  But because you know software has to be properly tested, you hope and pray your application will behave well in production after launch. Sometimes it does, sometimes it doesn’t. Sometimes it works for a while and then fails at an inconvenient time. When your application fails, you have to find out what went wrong, quickly.

## Leverage agile support to improve application quality and delivery

Agile support is similar to agile development in that it requires a simple plan for quick execution and accomplishing goals.  When you make agile support a part agile development, you can achieve higher levels of quality and get to market faster than ever before if you do it right.  I recommend three things:

## \#1:  Plan for Support

You already know your application is going to fail at some point and that your development team is going to have to respond.  But have you actually included support as part of your development plan?  Probably not because as I mentioned earlier management thinks you should be spending all of your time coding.

At the same time, the very same managers demand continuous productivity and efficiency improvements.  If you simply tell them that support is a bottleneck, they may not believe you.  But when a major outage occurs, the bottleneck becomes obvious.  You know.  You’ve been there before.

If you include agile support as part of your plan from the beginning, support will seem a lot less chaotic later.

## \#2:  Don’t Over-Architect or Under-Architect

Anyone familiar with agile development understands the concept of breaking a project into smaller pieces.  In practice, when your project has become a collection of agile pieces, it may be difficult to see the whole and therefore difficult to build a large architecture that will scale and work with the end product.

Many times, a SCRUM master or project manager will take the time to plan The World’s Greatest Application Architecture full of logging, well-calculated scalability and a high focus on easy maintainability.  But, because neither project deadlines nor budget requirements are infinite, The World’s Greatest Application Architecture ends up being little more than a pipe dream because at the end of the day, unless you are writing and selling software toolkits, business stakeholders don’t really care about software architecture.  They care about features that sell.

Even if you did build The World’s Greatest Application Architecture, you’d probably discover too late that you’ve over-built some aspect of your application that will take far too long to refactor. What’s important in architecting your application is that you:

**Don’t do dumb things.** If you’re doing agile development, you’re working in small increments and should have good visibility into the code that’s being produced. You should also think about how your code will scale and perform.

**Achieve consistency.** Try to use consistent logging, [error handling](https://stackify.com/csharp-exception-handling-best-practices/), and configuration management. In code reviews, make sure you adhere to these standards. If each developer has decided to handle errors and logging in a different way, supporting your application becomes a nightmare. Don’t allow unhandled exceptions to be caught and thrown away, for example. For most programming languages, there are tools available that can help enforce some of these basic rules.

**Document.** While you don’t need to detail every aspect of your application, you should include things done in the spirit of “get it to ship” that will cause pain in the future.  Go ahead and add a backlog item for it and try to prioritize it as soon as possible. After all, if you plan time for it, you should be able to improve it in an upcoming sprint.

**Don’t reinvent the wheel.** We all know “that developer” who will spend a lifetime crafting a better way to parse a Boolean value or do other things that allow [The Daily WTF](http://thedailywtf.com/) to exist. Don’t let it happen. If someone has already built a great framework or SDK that will help expedite your product’s architecture, embrace it.

## \#3:  Have a Disaster Plan

Even if you haven’t done what I suggest in points \#1 and \#2 \(Plan for Support and Don’t Over-Architect or Under-Architect\), you should know what to do when things go south.  This is where I often see developers hiding under their desks curled in a fetal position and begging for their mommies. Things have gone to hell, the boss is furious, and the phone won’t stop ringing.

Isolating and solving production issues is always a bit tricky, but isn’t that big of a deal if you at least think about how you’re going to handle it. You need a “go bag” and I’m going to help you build it. Here’s what you need:

**Be ready to reproduce.** So often, I see developers who don’t know how to troubleshoot a bug. Sometimes it just comes down to common sense: Get the steps to reproduce and use some basic tools to observe and troubleshoot the issue. You’d be amazed how many times my query, “have you used an HTTP proxy tool to inspect the results of the request” is met with a blank stare from the developer who is assigned to an Urgent production bug. I feel this aspect of development is often overlooked, and needs to be exercised often, just like any muscle.

**Know where to find your apps.** Your production environment shouldn’t be a complete mystery. You should know how many instances of your app are out there and how to access them. Ideally, you should also have a way to isolate the issue to a particular instance if at all possible. In some environments, none of this is available to developers. You should at least know who holds the keys, and be prepared to establish a good line of communication, or invest in a product like [Stackify](https://stackify.com/) to allow safe, secure access.

**Know how to get your data.** As mentioned in Tip \# 2 \(Don’t Over-Architect, Don’t Under-Architect\), you should at least decide on some consistent logging and error handling. Maybe you don’t have access, but you should be able to tell your support/operations team exactly where to get all the data you need to troubleshoot and analyze the issue.

**Have access to the right tools.** You will eventually find an issue that can’t be resolved through simple reproduction, [logging](https://stackify.com/log-management), and error handling. It will be a sporadic issue that seems to have no pattern or occurs completely unexpectedly and “resolves itself” just as quickly. When that happens, you need the tools available and at hand to perform a much more detailed analysis which may include advanced application health monitoring, code profiling, SQL profiling, failed request tracing, or memory/crash/process dumps. Regardless of the platform, there are tools out there to do all of these things, and you need to have them ready and at your disposal. Work with your Operations team to make sure they are installed and, if possible, configured to capture data automatically under certain conditions.

**Bottom Line:**

No one likes to plan for failures, but they’re inevitable. That’s why you have to sit through a short safety lecture before every commercial airline flight and why FEMA exists. With some simple planning, you will be able to easily support your application when disaster strikes and come out looking like a hero.

