# node-interactive-2015
notes, videos, and links from the conference in Portland, OR

### Convergence: Evolving Node.js with Open Governance and an Open Community

#### James Snell
(IBM’s open technologies architect)

First off was James Snell from IBM, with a presentation titled "Convergence: Evolving Node.js with Open Governance and an Open Community." Snell is IBM’s open technologies architect, and a member of the Node Core Technical Committee (CTC) and Technical Steering Committee (TSC). He observed that 2015 was an interesting year for Node, with the io.js fork generating some fear, doubt, and uncertainty.  Although there was a lot of excitement around Node, he said, there was a general belief that it could be better.

With the release of Node.js v4.0.0, the node.js and io.js projects resolved their differences and came back together. During the talk, he explored the events that led up to convergence, discussed how the Node.js project has evolved, and gave insight as to how developers can get involved to help the Node.js core continue to grow and mature.

Even more exciting is what’s happening in the ecosystem: npm module counts started increasing and npm downloads have gone up dramatically. Snell finished by saying he’s excited to see how people leverage Node to build great things in the coming year.

:movie_camera: [video](https://youtu.be/O28Knn00qYo)

# The World is being Reinvented in Code
Jason Gartner - vice-president of Interactive Services development, IBM

Started with a question: Why is IBM interested in Node, and how are we taking it forward? The answer, in a word (or rather, an acronym) is APIs. According to polls, the top use cases for Node are REST APIs and realtime services.

The next killer app, he said, isn’t going to be an app, its going to be an API, specifically a REST API. Every company is transforming into a digital business for which APIs are critically important to interact with customers, vendors, partners, and more. IBM refers to this as the "API economy." By 2018, he said, the API economy will be worth $2.2 trillion.

### IBM's focus on Node.js in 2015
- Acquiring StrongLoop.
- Continuing its support of the Node developer community.
- Working to bring Java and Node communities together to promote innovation.
- Expanding the number connectors to legacy systems where data currently resides.
- Making Node solutions available on IBM Bluemix and projects from Bluemix garage.

**Related Links**
[IBM Presence Highlights](http://www-03.ibm.com/software/products/en/ibm-presence-insights)
[Strongloop Arc](https://strongloop.com/node-js/arc/)
[IBM API Harmony for Bluemix](https://developer.ibm.com/bluemix/2015/07/01/api-harmony/)

:movie_camera: [video](https://youtu.be/iiLCWMoI6D0)

# Node.js at Uber
Tom Croucher - engineering manager, Uber

Tom spoke about his experiences using Node at Uber. He started by saying he likes the amount of power Node gives him and the things it enables him to do quickly and easily. Then he noted that the bulk of Uber’s $50 billion business is based on Node.js technology. Uber works because it’s a platform, he said, and that is largely enabled by Node.

He said "Let’s be real: Node is just an event loop with bits of JavaScript bolted on."

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

# Serving the Node.js Enterprise, Thus Serving the Community
Joe McCann, NodeSource

Spoke about the Node community and how to grow it by asking "How can we double the size of the Node community in one year?" The answer, he said was to embrace developers, ops engineers, and CIOs/CTOs.

He emphasized the importance of embracing the power of diversification: "diversity trumps ability." The more experiences, viewpoints, and perspectives that members of the Node community have, the better the outcome for the project itself.

Then he detailed some of the challenges facing people in various roles throughout the enterprise: developers, ops engineers, and executives.

:movie_camera: [VIDEO](https://youtu.be/wF1oNXeFnWI)

# Streams and You: A Love Story
Calvin Metcalf - Cartographer, AppGeo

Streams are a powerful part of the node.js ecosystem but can also be an intimidating part of node even for programmers who regularly use node. This talk would go over the basic concepts of streams such as pipes and back pressure and how to use them in real word ways with an aim for people to be able to leave the talk and be able to use the internal http module instead of the request module and pipe data around like a plumber.

:floppy_disk: [github](https://github.com/calvinmetcalf/streams-a-love-story)

:closed_book: [slides](http://streams.how/#1)

:movie_camera: [video](https://youtu.be/TyXgy5Wm948)


# Debugging Node.js in production
Yunong Xiao, Netflix

In this talk we learned about tools and methodologies we use in production at Netflix to diagnose and fix performance issues, bugs and memory leaks -- all without having to restart or change our Node application. Find out about profiling and post mortem tools such as perf events and mdb, visualizations like flame graphs and latency distributions, and how they help us keep our Node stack efficient.

:movie_camera: [video](https://youtu.be/CiqzuIUwHl8)

# Terminal Output to the Browser in Seconds, Using UNIX Pipes
Kilian Ciuffolo and Luca Orio, Lukibear

Whether you deploy your code on remote servers using multiple environments or simply have multiple projects, you must ssh to each machine running your code, in order to monitor the logs in realtime.

There are many log aggregation tools out there, but few of them are realtime. Most other tools require you to change your application source code to support their logging protocol/transport.

rtail is meant to be a replacement of logio, which isn't actively maintained anymore, doesn't support node v0.12., and uses TCP. (TCP requires strict client / server handshaking, is resource-hungry, and very difficult to scale.)

:movie_camera: [video](https://youtu.be/5IHWfgX3RJs)

# Getting a Handle On Your Dependencies
Dan Silivestru, bitHound

Here at bitHound we’ve analyzed almost all of the npm registry as well as thousands of other projects. We’ve learned some very interesting lessons with regards to managing our own dependencies and gained some great insights with respect to how dependencies are used across the JavaScript community.

:movie_camera: [video](https://youtu.be/2_aclLr3o5s)

# Hands on Hardware Workshop with Tessel
Kelsey Breseman, Tessel Project

Hacking on hardware with Node. Whether you've never touched hardware before or you're experienced with electronics, this workshop will let you use Node to build interactions with the physical world. You will be able to build something interesting in the allotted time. Kelsey will provide assistance, tools, and ideas.

:movie_camera: [video](https://youtu.be/uYcE4r0j8Zw)


# Building and Engaging High Performance Teams in the Node.js Ecosystem
Chanda Dharap, StrongLoop Inc, an IBM Company

There are many dimensions to building and working with teams in the Node.js stack. Hiring is one of the challenges, but hiring isn’t the only issue when moving development to the Nodejs stack. Some of the challenges are around understanding the open source culture - the passion for code hygenie and peer reviews, the semantics of versioning, and the ease with which the community updates to every latest version is unique.

The fast pace and prolific nature of StrongLoop’s module ecosystem forced us to recognize and optimize practices around tools, and processes needed to maintain over 150 repositories all packaged into a solution targeted at Enterprise.

:movie_camera: [video](https://youtu.be/OV2484MKwhw)

# Modernizing Winston for Node.js v4
Charlie Robbins - Directory of UX platform, GoDaddy
* also the founder of nodejitsu

Winston is the most popular logging library for node. Released in early 2011, it is almost old as node itself. Yet its popularity persists with over 2M monthly downloads and over 200 community contributed packages.

Over the years it has evolved as node and JavaScript have mature as platforms. Did you know that when winston was written there was no streams implementation as we know it today? And certainly no streams2 or streams3 specification. There were no good code coverage tools and mocha didn't even exist yet! But what's most want to know is how winston is better.

This talk will covers the road to winston@3.0.0 and highlight how the module ecosystem has evolved along side through hard work of a handful of dedicated core contributors, careful API design, utilizing ES6 features since node@0.12.x, and practical benchmarking and analysis.

Fun facts about Winston:
    - winston is 50% faster than Bunyan
    - winston no longer has a default transport for console.log

:movie_camera: [video](https://youtu.be/uPw7QIx3JZM)

# Node.js API pitfalls
:movie_camera: [video](https://youtu.be/jJaIwea8r2A)




