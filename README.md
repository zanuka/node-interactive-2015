### node-interactive-2015
notes, videos, and links from the conference in Portland, OR Dec. 9-10 2015

:closed_book: [keynotes](https://nodejs.org/en/blog/announcements/interactive-2015-keynotes/)

### TUESDAYS's talks (Dec. 8, 2015)

### Convergence: Evolving Node.js with Open Governance and an Open Community

#### James Snell
(IBM’s open technologies architect)

First off was James Snell from IBM, with a presentation titled "Convergence: Evolving Node.js with Open Governance and an Open Community." Snell is IBM’s open technologies architect, and a member of the Node Core Technical Committee (CTC) and Technical Steering Committee (TSC). He observed that 2015 was an interesting year for Node, with the io.js fork generating some fear, doubt, and uncertainty.  Although there was a lot of excitement around Node, he said, there was a general belief that it could be better.

With the release of Node.js v4.0.0, the node.js and io.js projects resolved their differences and came back together. During the talk, he explored the events that led up to convergence, discussed how the Node.js project has evolved, and gave insight as to how developers can get involved to help the Node.js core continue to grow and mature.

Even more exciting is what’s happening in the ecosystem: npm module counts started increasing and npm downloads have gone up dramatically. Snell finished by saying he’s excited to see how people leverage Node to build great things in the coming year.

:movie_camera: [video](https://youtu.be/O28Knn00qYo)

### The World is being Reinvented in Code
Jason Gartner - vice-president of Interactive Services development, IBM

Started with a question: Why is IBM interested in Node, and how are we taking it forward? The answer, in a word (or rather, an acronym) is APIs. According to polls, the top use cases for Node are REST APIs and realtime services.

The next killer app, he said, isn’t going to be an app, its going to be an API, specifically a REST API. Every company is transforming into a digital business for which APIs are critically important to interact with customers, vendors, partners, and more. IBM refers to this as the "API economy." By 2018, he said, the API economy will be worth $2.2 trillion.

### IBM's focus on Node.js in 2015
- Acquiring StrongLoop.
- Continuing its support of the Node developer community.
- Working to bring Java and Node communities together to promote innovation.
- Expanding the number connectors to legacy systems where data currently resides.
- Making Node solutions available on IBM Bluemix and projects from Bluemix garage.

##### Related Links
- [IBM Presence Highlights](http://www-03.ibm.com/software/products/en/ibm-presence-insights)
- [Strongloop Arc](https://strongloop.com/node-js/arc/)
- [IBM API Harmony for Bluemix](https://developer.ibm.com/bluemix/2015/07/01/api-harmony/)

:movie_camera: [video](https://youtu.be/iiLCWMoI6D0)

### Node.js at Uber
Tom Croucher - engineering manager, Uber

Tom spoke about his experiences using Node at Uber. He started by saying he likes the amount of power Node gives him and the things it enables him to do quickly and easily. Then he noted that the bulk of Uber’s $50 billion business is based on Node.js technology. Uber works because it’s a platform, he said, and that is largely enabled by Node.

**He said "Let’s be real: Node is just an event loop with bits of JavaScript bolted on."**

He recommended that everyone read Steve Yegge’s "platform rant" from 2001 that compares how things are done at Google and Amazon.

He also noted that Uber loves open source and contributing to the open source community. See http://uber.github.io/ for a list of projects.

:movie_camera: [video](https://youtu.be/ElI5QtUISWM)

# Node.js and npm by Numbers
Ashley Williams - developer community and content manager, npm

Every day around 1.8 million npm install events occur. Since each of these events downloads an average of 70 packages, that means that people download 126 million packages per day using npm.

She explained that npm is a package manager tool, but it’s also a community engagement tool. It creates a nexus of participants:

• Installers who want to download packages
• Packages that can take on a life of their own
• Publishers who write and publish code to the npm registry

In the last year, npm has served over 19 billion package downloads, over half of those in last three months. It has over 200,000 packages, each with an average of six versions, which gives it 1.2 million package versions. This makes it the largest package manager in the world.

Node’s success depends on its growth into the enterprise, and **"open source is the largest enterprise"** and concluded by saying they are excited to enable more, and more diverse, developers to collaborate and are humbled to be a part of Node’s success.

:movie_camera: [video](https://youtu.be/5ikjwX2ur2U)

### Serving the Node.js Enterprise, Thus Serving the Community
Joe McCann, NodeSource

The Node Community. Arguably one of the strongest and most vibrant of any open source project is rapidly expanding and becoming even more inclusive. How? With the rise of enterprise adoption of Node.

Why does this matter for the community? The presentation will cover how a community is not an "us vs. them" scenario but a "we" situation and how serving enterprise needs in return benefits the greater, ever-growing Node community while simultaneously creating an even more diverse group.

:movie_camera: [video](https://www.youtube.com/watch?v=wF1oNXeFnWI)

### Serving the Node.js Enterprise, Thus Serving the Community
Joe McCann, NodeSource

Spoke about the Node community and how to grow it by asking "How can we double the size of the Node community in one year?" The answer, he said was to embrace developers, ops engineers, and CIOs/CTOs.

He emphasized the importance of embracing the power of diversification: "diversity trumps ability." The more experiences, viewpoints, and perspectives that members of the Node community have, the better the outcome for the project itself.

Then he detailed some of the challenges facing people in various roles throughout the enterprise: developers, ops engineers, and executives.

:movie_camera: [VIDEO](https://youtu.be/wF1oNXeFnWI)

### Streams and You: A Love Story
Calvin Metcalf - Cartographer, AppGeo

Streams are a powerful part of the node.js ecosystem but can also be an intimidating part of node even for programmers who regularly use node. This talk would go over the basic concepts of streams such as pipes and back pressure and how to use them in real word ways with an aim for people to be able to leave the talk and be able to use the internal http module instead of the request module and pipe data around like a plumber.

:floppy_disk: [github](https://github.com/calvinmetcalf/streams-a-love-story)

:closed_book: [slides](http://streams.how/#1)

:movie_camera: [video](https://youtu.be/TyXgy5Wm948)


### Debugging Node.js in production
Yunong Xiao, Netflix

In this talk we learned about tools and methodologies we use in production at Netflix to diagnose and fix performance issues, bugs and memory leaks -- all without having to restart or change our Node application. Find out about profiling and post mortem tools such as perf events and mdb, visualizations like flame graphs and latency distributions, and how they help us keep our Node stack efficient.

:movie_camera: [video](https://youtu.be/CiqzuIUwHl8)

### Terminal Output to the Browser in Seconds, Using UNIX Pipes
Kilian Ciuffolo and Luca Orio, Lukibear

Whether you deploy your code on remote servers using multiple environments or simply have multiple projects, you must ssh to each machine running your code, in order to monitor the logs in realtime.

There are many log aggregation tools out there, but few of them are realtime. Most other tools require you to change your application source code to support their logging protocol/transport.

rtail is meant to be a replacement of logio, which isn't actively maintained anymore, doesn't support node v0.12., and uses TCP. (TCP requires strict client / server handshaking, is resource-hungry, and very difficult to scale.)

:movie_camera: [video](https://youtu.be/5IHWfgX3RJs)

### Getting a Handle On Your Dependencies
Dan Silivestru, bitHound

Here at bitHound we’ve analyzed almost all of the npm registry as well as thousands of other projects. We’ve learned some very interesting lessons with regards to managing our own dependencies and gained some great insights with respect to how dependencies are used across the JavaScript community.

:movie_camera: [video](https://youtu.be/2_aclLr3o5s)

### Hands on Hardware Workshop with Tessel
Kelsey Breseman, Tessel Project

Hacking on hardware with Node. Whether you've never touched hardware before or you're experienced with electronics, this workshop will let you use Node to build interactions with the physical world. You will be able to build something interesting in the allotted time. Kelsey will provide assistance, tools, and ideas.

:movie_camera: [video](https://youtu.be/uYcE4r0j8Zw)


### Building and Engaging High Performance Teams in the Node.js Ecosystem
Chanda Dharap, StrongLoop Inc, an IBM Company

There are many dimensions to building and working with teams in the Node.js stack. Hiring is one of the challenges, but hiring isn’t the only issue when moving development to the Nodejs stack. Some of the challenges are around understanding the open source culture - the passion for code hygenie and peer reviews, the semantics of versioning, and the ease with which the community updates to every latest version is unique.

The fast pace and prolific nature of StrongLoop’s module ecosystem forced us to recognize and optimize practices around tools, and processes needed to maintain over 150 repositories all packaged into a solution targeted at Enterprise.

:movie_camera: [video](https://youtu.be/OV2484MKwhw)

### Modernizing Winston for Node.js v4
Charlie Robbins - Directory of UX platform, GoDaddy
* also the founder of nodejitsu

Winston is the most popular logging library for node. Released in early 2011, it is almost old as node itself. Yet its popularity persists with over 2M monthly downloads and over 200 community contributed packages.

Over the years it has evolved as node and JavaScript have mature as platforms. Did you know that when winston was written there was no streams implementation as we know it today? And certainly no streams2 or streams3 specification. There were no good code coverage tools and mocha didn't even exist yet! But what's most want to know is how winston is better.

This talk will covers the road to winston@3.0.0 and highlight how the module ecosystem has evolved along side through hard work of a handful of dedicated core contributors, careful API design, utilizing ES6 features since node@0.12.x, and practical benchmarking and analysis.

Fun facts about Winston:
    - winston is 50% faster than Bunyan
    - winston no longer has a default transport for console.log

:movie_camera: [video](https://youtu.be/uPw7QIx3JZM)

### Go Ahead, Roll Your Own Framework
Ryan Stevens, LendingClub

Engineers are continually told throughout their career to not reinvent the wheel. Frameworks allow engineers to concentrate on domain specific logic and not worry about writing boilerplate code. But have you ever wondered why there are so many to choose from? Many of these frameworks have huge variances in design choices, patterns they enforce developers adhere to, and wildly dogmatic followers… Until a new one comes along and people justify yet another framework rewrite in the name of superior technology.

This talk will journey into the sometimes taboo subject of creating your own framework. Embracing a home grown framework can have its merits under the right circumstances and is worth exploring. This talk places an emphasis on valuing the process and understanding how it can bring out the best in a team with a diverse set of skills and backgrounds.

:movie_camera: [video](https://youtu.be/CIVhvhdISRI)


### Making Your Node.js Applications Debuggable
Patrick Mueller, NodeSource

No one writes perfect code. Everyone makes mistakes. The only question is, how easy is to find your mistakes? This presentation will cover tools and techniques you can use to make it easier to diagnose problems with your applications.

:movie_camera: [video](https://www.youtube.com/watch?v=gHrrgZmoY6E)

### Reaching Ludicrous Speed
Matteo Collina, nearForm

How can our code be faster? What does faster means? In this journey we would walk through different performance optimization techniques you can apply to your code. We will see start from --v8-options, and we will discover how to leverage what v8 tells us to optimize our code. We will discuss hidden classes, function optimizations and deoptimizations, and inlining. We will discuss the tools and the libraries you can use to do perf analysis on your code. In this journey, we will discover that the main villain is Lord GC, and we will fight him to reclaim our memory! At the very end, we would reach a point where even allocating a callback is too slow: Ludicrous Speed.

:movie_camera: [video](https://www.youtube.com/watch?v=_0W_822Dijg)

### FrontendFS: Creating a Filesystem for Web Development Using Node.js
Clay Smith, New Relic

Writing filesystems is for everyone, not just systems engineers.

This talk introduces the open-source project FrontendFS, a filesystem written in Node.js that provides a file and directory abstraction on top of front-end build tasks. Using the Linux FUSE library, modifying files on a mounted FrontendFS filesystem triggers build processes in the background so something as easy as dragging and dropping files into a directory can immediately minify and gzip a JavaScript file.

Starting with a high-level introduction to filesystems, this talk will cover the architecture of virtual filesystems in Linux written using FUSE Node.js bindings and important performance considerations. The talk will focus on the power, creativity and simplicity of building open-source virtual filesystems in Linux.

:movie_camera: [video](https://www.youtube.com/watch?v=SG10bZeYi6k)

### Building Twitter Bots in Node.js
Philip James, Eventbrite

Want to make an online art project with built-in sharing? Or give your IoT project a presence without building a full web interface? Twitter bots provide an amazing level of satisfaction for relatively little effort and code, if you know how to get started and how to get your bot running.

This presentation will explore how to get a twitter bot started, tips and tricks for working with the twitter api and client libraries, how to easily get your bot's credentials for posting to twitter, and how to get your bot deployed and posting easily.

:movie_camera: [video](https://www.youtube.com/watch?v=xkNOKSNSoVI)

### Lessons Learned: Extending Node.js with Another JavaScript Engine
Arunesh Chandra, Microsoft

At Microsoft, Node.js represents a true cross platform technology that is enabling solutions ranging from cloud computing to Internet of Things and beyond. Microsoft’s Chakra team started an initiative to support Chakra, Microsoft’s own Javascript engine, as an alternative VM for Node.js. Although maybe still surprising to someone, all of the work that our team has done to enable this support is being done in the open, wherein not only is the code open source but we have been actively looking for community feedback and participation to learn and improve. In this session we’ll discuss some of the learnings we had during the process, and in particular talk about:
• What motivated us to support Node.js with another VM?
• What key challenges the team met along the way to support a different VM and how we overcame the same?
• Where are we with the current support and what’s next?

:movie_camera: [video](https://www.youtube.com/watch?v=Zbc3SwMDWf0)

### WEDNESDAY's talks (Dec. 9, 2015)

### Resource Management in Node.js
Bradley Meck, NodeSource

Node.js has immense strength when it comes to routing resources between each other. One of the ways that this impressive coordination has progressed is through asynchronous callbacks, and streaming. As with any abstraction, there is a need to safely ensure the abstraction does not cause leaks in resource management. In this presentation, Bradley Meck will discuss basic tools for checking resource usage, using generators to create safe resource life-cycles, using callbacks to track resource invalidation, and techniques to handle cancellation of requests that hold onto resources.

### Rebuilding the Ship as it Sails: Making Large Legacy Sites Responsive
Philip James, Eventbrite

Yes, making sites responsive can be a pain, especially larger, older sites that have been touched by many hands and which might have dark corners that people would prefer to avoid. But we all know how crucial it is to make more and more of our work responsive, and there are things you can do to make big pushes towards responsiveness easier. This talk will cover:

- The problem of making large sites responsive
- Techniques you can use in planning to help divide the work in a sane way
- Tools you can use and develop to make responsifying pages easier
- Tips on how to train all your engineers, backend, frontend, and otherwise, to be able to make pages responsive.

These lessons will be drawn from the example of Eventbrite, who went through a major responsive overhaul last year.

:movie_camera: [video](https://www.youtube.com/watch?v=D9TUU5bK0iE)

### NodeBots at Scale
Matteo Collina, nearForm

The NodeBots movement aims to help everybody control robots with Node, but all the examples online focus on controlling a single machine. At NodeConf.eu we built 4 robots that were able to serve 134 cocktails in 1 hour and a half. They were all wifi controlled and we are able to order drinks from our smartphones. In the process, we fried 2 Raspberry Pi2, fried 4 transistors, burned two fingers, live deployed bug-fixes but ultimately made four robots that could serve 2 drinks each. For this scaled-up prototype, we used Johnny-Five, MQTT.js, some other popular JS libraries (express, socket.io, and many others), we open sourced all our code and our blueprints, so you can build one yourself! This is the story of this journey, from inception to the event.

:movie_camera: [video](https://www.youtube.com/watch?v=CGGGklIfigc)

### Node.js API Pitfalls: Can You Spot Them?
Sam Roberts, Strongloop

It’s quiz time. What would you expect to get back from a call to url.encode? The answer may surprise you. This session will be a walk through some of the pitfalls in the Node.js core API, how to avoid them, and a discussion of whether they can or should be fixed. Sam will discuss why these APIs behave the way they do and how they might be changed, along with the arguments for keeping them the same.

The session will conclude with thoughts on Node.js core API stability, including who it helps, who it hurts, and whether as a community we should value improving the core API for the benefit of emerging users over keeping it stable for the benefit of existing users and their existing code bases.

:movie_camera: [video](https://www.youtube.com/watch?v=jJaIwea8r2A)

### NPM Everywhere
Mike MacCana, CertSimple

npm everywhere: all the things we wish we'd known earlier. This talk is a look at a real world production app using
npm on the front end, npm on the back end, and npm for all code - no lib dirs, no anything else. Including:

- Benefits of using modules for your own original code
- Benefits of using npm for front end developers
- Including non-JavaScript code in your bundles
- Tools to analyse and reduce frontend bundle size
- Ensuring repeatable deploys
- Reducing module fatigue

:movie_camera: [video](https://www.youtube.com/watch?v=d_5SXW3a1-I)

###Home Automation with Node.js and RasperryPi
Mariano Campo, MercadoLibre

Building your own home automation system has never been easier with Node 4.x landing with ARM support.

In this presentation Mariano will explain how you can build a central hub for any home automation device you can think of. All you need is a RaspberryPi and your good old friend Node.js.

Mariano will cover an architecture based on a central hub talking to multiple smaller devices (arduino based, for example), all securely accessed from an interface deployed in the cloud.

:movie_camera: [video](https://www.youtube.com/watch?v=N8lFHdM5pIk)

### Peer-to-Peer Numeric Computing with JavaScript
Athan Reines, Verbify, Inc.

Traditionally, if you wanted to write fast code for numeric computation, you used Fortran or C. Within the past two decades, we have seen an enormous shift toward languages which favor expressiveness over absolute speed. Much of scientific computing is now performed using dynamic, loosely typed languages, such as R or Python. Taking into account JavaScript's expressiveness, why not do your computing in Node? In this talk, Athan Reines will discuss numeric computation in JavaScript, libraries currently available, and what makes these libraries competitive with and even superior to alternatives on other platforms. He will discuss how to leverage Node libraries when building P2P compute applications, culminating in a demo showcasing WebRTC and RPC over a peer network. Finally, he will outline future steps and identify opportunities for community development of next-generation tools.

:movie_camera: [video](https://www.youtube.com/watch?v=CbYDU1XFhHg)

### Node.js Intl: Where We Are and What's Next
Steven Loomis, IBM

Node.js v0.12 - and once again v3.1 after the merge - supports the "Intl" object out of the box for the Ecma-402 Internationalization API. What is Internationalization? Why is it important for developers?

This presentation will give a very brief history of the efforts to improve internationalization in JavaScript in general and Node.js in particular, including the work of the Node.js Intl working group. It will give you some resources and best practices you can use now, as well as look at what's next in the world of Node Intl.

:movie_camera: [video](https://www.youtube.com/watch?v=U0z_yO5gFP8)

### Microservice Developer Experience
Peter Elger, nearForm

Whilst micro-service based architectures promise many benefits in production, such as rapid continuous deployment cycles, current developer tools are lagging behind. Irrespective of platform our current toolchains are very much oriented around the construction of monolithic application stacks and are unwieldy and cumbersome when applied to micro-service based systems. This talk will demonstrate a dynamic and responsive developer toolchain
for micro-services that is more aligned with this architectural style, with live coding examples and deployment through to staging.

This talk will cover the tools that nearForm use to develop micro-services in the wild, something we've discovered and iterated on over the last three years.

:movie_camera: [video](https://www.youtube.com/watch?v=jm75pxsb80c)

### How to Build and Deploy Open Source Application Monitoring Solutions
Chris Bailey, IBM

Even the most innovative and groundbreaking applications risk failure if they do not provide an engaging and responsive user experience. Performance and scalability both require access to real-time performance data that lets developers optimize code, allows the infrastructure to scale automatically, enables operations teams to identify issues, and gives business owners insights into the success of the application.

This session will show you how to add application performance monitoring and analytics capabilties to your application, using the open source Node Application Metrics data collector, alongside open source monitoring stacks like StatsD with Graphite, and Elasticsearch with Kibana.

:movie_camera: [video](https://www.youtube.com/watch?v=ix3tRagIpwA)

### Building Interactive npm Command Line Modules -- All The Things.
Irina Shestak

Here you are coding away, when you realize you're in desperate need of a quick shell script to get your project cleaned up. You're standing at a fork in the road: Bash or Node? You choose the road less travelled by (for some reason) -- Node. I congratulate you on this decision. You've written it, you may have published it, and it certainly works. But what now? Is this all a command line module Node is good for: a project clean up and some data manipulation?

Let's take it a step further. Let's make a command line module that's more than just your compiling script. I am, of course, talking about making it more interactive.

In this talk Irina wants to take you on an adventure that will require cunning, bravery, and maybe some magic. We will walk through obtaining and parsing data, using Node's process functions, and finally improving your module's user experience.

:movie_camera: [video](https://www.youtube.com/watch?v=QLat0Y3jqUA)

### Node.js at PayPal
Matt Edelman, PayPal

:movie_camera: [video](https://www.youtube.com/watch?v=-00ImeLt9ec)



