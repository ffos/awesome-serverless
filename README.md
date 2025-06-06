<img src="http://i.imgur.com/zq0LJAl.png" align="right" height=300>

# :cloud: Awesome Serverless

A curated list of awesome services, solutions and resources for serverless / nobackend applications.

***“No server is easier to manage than no server”***

## Table of contents

- [What is "serverless" computing?](#what-is-serverless-computing)
- [All in one solutions](#all-in-one-solutions)
- [Hosting and code execution in the cloud](#hosting-and-code-execution-in-the-cloud)
- [Isomorphic Engines](#isomorphic-engines)
- [Frameworks](#frameworks)
- [Security](#security)
- [CI/CD](#cicd)
- [Cost calculators](#cost-calculators)
- [Logging / Monitoring / Performance / Tracing](#logging--monitoring--performance--tracing)
- [Authentication and authorization](#authentication-and-authorization)
- [IAM](#iam)
- [Payments](#payments)
- [eCommerce](#ecommerce)
- [Content Management Systems](#content-management-systems)
- [Forms](#forms)
- [Media management and File storage](#media-management-and-file-storage)
- [Realtime](#realtime)
- [Scheduling](#scheduling)
- [Email sending, subscriptions and newsletters](#email-sending-subscriptions-and-newsletters)
- [SMS sending](#sms-sending)
- [Push notifications](#push-notifications)
- [Databases](#databases)
- [Others](#others)
- [Related articles](#related-articles)
- [Books](#books)
- [Courses](#courses)
- [Workshops](#workshops)
- [Newsletters](#newsletters)
- [AWS re:Invent videos](#aws-reinvent-videos)
- [Videos from conferences](#videos-from-conferences)
- [Contributing](#contributing)
- [License](#license)

## What is "serverless" computing?

> The phrase “serverless” doesn’t mean servers are no longer involved. It simply means that developers no longer have to think "that much" about them. Computing resources get used as services without having to manage around physical capacities or limits.
> Let's take for example AWS Lambda. "Lambda allows you to NOT think about servers. Which means you no longer have to deal with over/under capacity, deployments, scaling and fault tolerance, OS or language updates, metrics, and logging."

[Quora: What is Serverless Computing?](https://www.quora.com/What-is-serverless-computing)

## All in one solutions

* [AppDrag](https://appdrag.com) - Cloud Backend with SQL database and serverless API builder, Cloud CMS with domain management and email marketing tools
* [Firebase](https://www.firebase.com) - Realtime database, authentication, hosting. A powerful platform for your mobile or web application.
* [Klotho](https://github.com/KlothoPlatform/klotho) - Serverless-enabled Infrastructure-from-Code tool that transforms plain code into cloud native code.
* [Back4App](https://www.back4app.com) - A Backend as a Service platform powered by Parse Open Source which you can use to build your app faster, host it with no hassles and keep full control over your Backend.
* [LeanCloud](https://leancloud.app) - Serverless cloud for lightning-fast development.
* [Nitric](https://nitric.io) - An Open Source framework for rapidly building serverless applications.
* [Backendless](https://backendless.com) - Realtime database, authentication, hosting.
* [Kinvey](http://www.kinvey.com) - Build your digital business faster with mobile Backend as a Service.
* [Substation](https://github.com/brexhq/substation) - Substation is a cloud native data pipeline and transformation toolkit written in Go.
* [Syncano](https://syncano.io) - An all-in-one platform to create realtime apps without a server.
* [Hoodie](http://hood.ie) - Hoodie is a complete backend for your apps: develop your frontend code.
* [Para](https://paraio.com) - Flexible and lightweight backend service for rapid prototyping, based on open source software.
* [Parse Server](https://parseplatform.org/) - Parse Server is an open source version of the Parse backend that can be deployed to any infrastructure that can run Node.js. You can find the source on the [GitHub repo](https://github.com/parse-community/parse-server).
* [wolkenkit](https://www.wolkenkit.io) - wolkenkit is a CQRS and event-sourcing framework for JavaScript and Node.js which fits perfectly with domain-driven design (DDD).
* [Kuzzle](https://kuzzle.io) - High performance cloud agnostic backend solution including persistence, authentication, realtime database and geofencing with a full featured cluster mode.
* [serverless-cqrs](https://www.serverless-cqrs.com) - A collection tools to help you build a fully functioning backend based on the principles of CQRS, Event Sourcing, Domain Driven Design, and Onion Architecture.
* [ops](https://ops.city) - A free open source tool that allows anyone to build, run and deploy normal linux applications as unikernels.
* [codehooks.io](https://codehooks.io) - A modern, lightweight serverless backend platform tailored for building data-powered APIs fast using JavaScript/TypeScript and NoSQL. Free plan.

## Hosting and code execution in the cloud

* [Tau](https://github.com/taubyte/tau) - Easily Build Cloud Computing Platforms with features like Serverless WebAssembly Functions, Frontend Hosting, Object Storage, K/V Database, and Pub-Sub Messaging.
* [FaaStRuby](https://faastruby.io) - Serverless Software Development Platform for Ruby and Crystal developers.
* [AWS Lambda](https://aws.amazon.com/lambda) - Run code without thinking about servers. Pay for only the compute time you consume.
* [Google Cloud Functions](https://cloud.google.com/functions/docs) - Lightweight, event-based, asynchronous compute solution that allows you to create small, single-purpose functions that respond to cloud events without the need to manage a server or a runtime environment.
* [MongoDB Stitch](https://www.mongodb.com/cloud/stitch) - Serverless platform from MongoDB.
* [Spotinst Functions](https://spotinst.com/products/spotinst-functions/) - Deploy serverless functions with our easy to use framework that launch onto the Spot Market for cheap and convenient use.
* [Azure Functions](https://azure.microsoft.com/en-us/services/functions) - Listen and react to events across your stack.
* [Fission](http://fission.io) - Fast, extensible, open source serverless functions on any Kubernetes cluster
* [IBM Cloud Functions](https://console.bluemix.net/openwhisk/) - Distributed compute service to execute application logic in response to events.
* [Knative](https://knative.dev/) - Kubernetes-based platform to build, deploy, and manage modern serverless workloads
* [Kubeless](https://kubeless.io/) - is a Kubernetes-native serverless solution.
* [iron.io](https://www.iron.io/platform/ironworker) - Isolates code and dependencies of individual tasks so they can be processed on demand.
* [weblab.io](https://weblab.io) - Microservices at your fingertips.
* [Peer5](https://www.peer5.com) - The serverless CDN. Limitless, affordable video delivery. More traffic means a stronger network.
* [StdLib](https://stdlib.com) - Function as a service library and platform.
* [Webscripts](https://www.webscript.io)~~ - Scripting on the web. (Shutting down December 15, 2017)
* [Surge](http://surge.sh) - Deploy static sites from the command line.
* [Netlify](https://netlify.com) - All-in-one platform for automating modern web projects. Build and host static sites, deploy AWS lambda functions, and more, all from git repositories.
* [Aerobatic](https://www.aerobatic.com) - Deploy static sites from the command line with plugins including password protection, CORS proxy, and [more](https://www.aerobatic.com/docs/plugins).
* [Effe](https://github.com/siscia/effe) - a simple Open Source building block to emulate AWS Lambda.
* [Vercel](https://vercel.com) - Build and deploy 40 different web frameworks with zero configuration along with Node.js, Python, Go, and Ruby Serverless Functions
* [OpenComponents](https://opencomponents.github.io) - Serverless microservices for front-end components.
* [OpenFaaS Cloud](https://github.com/openfaas/openfaas-cloud) - OpenFaaS Cloud: multi-user serverless functions driven by git.
* [Stackery](https://www.stackery.io/) - Stackery enables teams of developers to design, deploy, and monitor their serverless infrastructure on cloud services providers like AWS.
* [Algorithmia](https://algorithmia.com/) - Automating the use of AI/ML models at every scale with the Serverless AI Layer.
* [TriggerMesh](https://www.triggermesh.com) - Serverless Management Platform with advanced event triggers.
* [Cloudflare Workers](https://www.cloudflareworkers.com) - Workers allow you to deploy Serverless apps to 165+ data centers across the globe simultaneously, along with the ability to agument or alter exsisting websites and APIs on the fly.
* [fn](https://fnproject.io) - The container native, cloud agnostic serverless platform.
* [TinyFunction](https://tinyfunction.com) - Fastest way to create cloud functions. Write your function, deploy and call them from anywhere.
* [Cycle.io](https://cycle.io) -  A Devops platform with integrated serverless-like functionality, alongside other DevOps features like container orchestration, load-balancing, monitoring and more.

## Isomorphic Engines

* [lychee.js](https://github.com/Artificial-Engineering/lycheejs) - Isomorphic adapters allow peer-to-peer event-graphed WebSockets and HTTP1.1, SPDY and HTTP2.0 sockets for node, node-sdl, html, html-nwjs and html-webview (both native and embedded).

## Frameworks

* [Aegis](https://github.com/tmaiaroto/aegis) - A Golang serverless application development framework for AWS with deploy tool.
* [Apache OpenWhisk](https://openwhisk.apache.org) - Open source and enterprise-ready serverless platform that executes functions in any language (including Docker Containers) in response to events, powering IBM Cloud Functions, Adobe I/O Runtime and a number of on-prem deployments worldwide.
* [Architect](http://arc.codes) - Provision and deploy from a super simple plaintext manifest.
* [AWS Amplify](https://aws-amplify.github.io/) - A declarative JavaScript library for application development using cloud services.
* [Booster](https://www.booster.cloud) - An Open Source framework for developing event-driven serverless applications with TypeScript.
* [Browser Functions](https://github.com/IBM/browser-functions) - A lightweight serverless platform that uses Web Browsers as execution engines.
* [Up](https://up.docs.apex.sh/) - Deploy infinitely scalable serverless apps, apis, and sites in seconds.
* [Chalice](https://github.com/awslabs/chalice) - Python serverless microframework from Amazon for AWS lambda.
* [CIM](https://github.com/thestackshack/cim) - A CloudFormation first approach to AWS Lambdas.
* [ClaudiaJS](https://github.com/claudiajs/claudia) - Deploy Node.js microservices to AWS easily.
* [DEEP](https://github.com/MitocGroup/deep-framework) - Full-stack Web Framework for Cloud-Native Applications and Platforms using Microservices Architecture.
* [FaasJS](https://faasjs.com) - A Node.js Serverless Application Framework.
* [flowbject](https://github.com/alex20465/flowbject) - A high-level library whose aim is to help with writing state-machine flows.
* [FunctionShield](https://github.com/puresec/FunctionShield) - A security library that equips developers with the ability to easily enforce strict security controls on AWS Lambda function runtime by addressing 3 common use cases: 1) Disable outbound internet connectivity. 2) Disable read/write on the /tmp/ directory 3) Disable child process execution.
* [genezio](https://genez.io/?utm_source=awesome-serverless-github&utm_medium=website&utm_campaign=awesome-serverless) - a platform for developers to write, deploy and use a serverless API.
* [Gordon](https://github.com/jorgebastida/gordon) - λ Gordon is a tool to create, wire and deploy AWS Lambdas using CloudFormation.
* [IronFunctions](https://github.com/iron-io/functions) - The Serverless Microservices platform.
* [Jets](https://rubyonjets.com) - Ruby Serverless Framework for AWS. Jets allows you to create serverless applications with a beautiful language: Ruby. It includes everything required to build an application and deploy it to AWS Lambda.
* [Kappa](https://github.com/garnaat/kappa) - a command line tool that (hopefully) makes it easier to deploy, update, and test functions for AWS Lambda.
* [Laconia](http://laconiajs.io) - A microframework for building Node.js serverless applications (AWS Lambda). Create well-crafted serverless applications, effortlessly!
* [Lambda API](https://github.com/jeremydaly/lambda-api) - Lightweight web framework for your serverless applications.
* [Lambda Forest](https://github.com/tdsis/lambda-forest) - Microframework that makes it easier to develop REST API's using AWS Lambda Function and API Gateway.
* [Lambada Framework](https://github.com/lambadaframework/lambadaframework) - JAX-RS implementation for AWS Lambda.
* [lambda-restify](https://github.com/kksharma1618/lambda-restify) - A restify/expressjs like interface for aws lamda with api gateway event.
* [Lambdoku](https://github.com/kubek2k/lambdoku) - Heroku-like experience when using AWS Lambda.
* [lgw](https://github.com/ebridges/lgw) - Simply & easily configure an AWS Gateway & domain name in front of a Lambda.
* [Lovage](https://github.com/CloudSnorkel/lovage) - Python-only serverless framework that's more RPC-like and less HTTP service oriented.
* [Mantil](https://github.com/mantil-io/mantil) - Golang serverless development kit for AWS Lambda. Tool for developers that removes ops work for them, not just another infrastructure tool.
* [middy](https://middy.js.org/) - Node.js middleware engine for AWS Lambda.
* [modofun](https://modofun.js.org) - A lightweight no-dependencies function router for both AWS Lambda and Google Cloud Functions, and that supports Connect/Express middleware.
* [OpenFaaS](https://www.openfaas.com) - Serverless Functions Made Simple for Docker and Kubernetes.
* [Pulumi](https://pulumi.io) - A cloud development platform for serverless, containers, infrastructure. Multi-cloud (and Kubernetes) and works with JS, TS, Python, Go
* [Python-λ](https://github.com/nficano/python-lambda) - A toolkit for developing and deploying serverless Python code in AWS Lambda.
* [Serverless Framework](http://www.serverless.com) - Build and maintain web, mobile and IoT applications running on AWS Lambda, Azure Cloud Functions, IBM Cloud Functions, Apache OpenWhisk, and Google Cloud Functions (formerly known as JAWS).
* [Serverless Compose](https://github.com/DavidJFelix/serverless-compose) - A lightweight, functional, composable, middleware framework for AWS lambda that stays out of the way.
* [serverless.tf](https://serverless.tf) - A framework for developing, building, deploying, and securing serverless applications and infrastructures on AWS using Terraform ([read more](https://github.com/antonbabenko/serverless.tf)).
* [Shep](https://github.com/bustlelabs/shep) - A framework for building APIs using AWS API Gateway and Lambda.
* [Sigma](https://www.slappforge.com/sigma) - An all-in-one, browser-based IDE toolkit for drag-n-drop composing, testing and deploying of serverless applications, with fully automated configuration management.
* [Sparta](http://gosparta.io) - A framework that transforms a Go application into an AWS Lambda powered microservice.
* [Stacktape](https://stacktape.com) - DevOps-free cloud framework. Deploy lambdas, containers, databases & more to AWS with 98% less config.
* [SAM Local](https://github.com/awslabs/aws-sam-local) - Is the AWS CLI tool for managing Serverless applications written with [AWS Serverless Application Model (SAM)](https://github.com/awslabs/serverless-application-model)
* [Turtle](https://github.com/iopipe/turtle/) - library for building functional and actor-driven NodeJS apps on Lambda.
* [Zappa](https://github.com/Miserlou/Zappa) - Serverless Python WSGI with AWS Lambda + API Gateway.
* [λambdify](http://zhukovalexander.github.io/lambdify) - AWS Lambda automation and integration for Python
* [Squeezer Framework](https://squeezer.io) - Event-driven APIs & Web apps on microservices, serverless.
* [Spring Cloud Function](https://github.com/spring-cloud/spring-cloud-function) - Java framework for doing Functions using Spring ecosystem.
* [Fission Workflows](https://github.com/fission/fission-workflows) - Fast workflow-based function composition for serverless functions.
* [azure-functions-express](https://github.com/yvele/azure-function-express) - Allows Express.js usage with Azure Functions.
* [Riff](https://projectriff.io/) - Kubernetes based serverless framework supporting multiple languages.
* [FuseLess](https://fuseless.org/) - toolkit for running functions written in CFML (ColdFusion Markup Language) on AWS Lambda.
* [DropFaaS](https://dropfaas.com/) - Serverless framework for running functions written in any languages.

## Security

* [PureSec](https://www.puresec.io) - Enabling Secure and Reliable Serverless Applications.
* [Serverless Security Top 10 Guide](https://github.com/puresec/sas-top-10) - The Ten Most Critical Risks for Serverless Applications.
* [AWS Lambda Security Best-Practices eBook](https://www.puresec.io/aws-lambda-security-best-practices) - An AWS Lambda security best-practices eBook
* [AWS Lambda Security Quick-Start Guide](https://www.puresec.io/blog/aws-lambda-security-quick-guide) - A Quick-Start guide for AWS Lambda Security
* [AWS Security Best Practices: Config Rules for AWS Lambda Security](https://www.puresec.io/blog/aws-security-best-practices-config-rules-lambda-security) - A guide on how to use AWS Config rules for governing and securing your Lambda functions, with a free set of 4 open source rules developed in SAM.
* [Using AWS CloudTrail to enhance your serverless application security](https://serverless.com/blog/cloudtrail-security) - A guide on how to use CloudTrail to improve AWS Lambda security posture.
* [OWASP ServerlessGoat](https://www.owasp.org/index.php/OWASP_Serverless_Goat) - OWASP ServerlessGoat is a deliberately insecure realistic AWS Lambda serverless application, maintained by OWASP and contributed by PureSec. Install ServerlessGoat and learn about the vulnerabilities, how to exploit them, and how to remediate each issue. Installation is just a 1-click through the [AWS Serverless Application Repository](https://serverlessrepo.aws.amazon.com/applications/arn:aws:serverlessrepo:us-east-1:761130837472:applications~serverless-goat)
* [Awesome-Serverless-Security](https://github.com/puresec/awesome-serverless-security/) - A curated list of awesome serverless security resources such as (e)books, articles, whitepapers, blogs and research papers.
* [Protego](https://www.protego.io) - your apps became serverless. Your security also need to be serverless too.
* [Nuweba](https://www.nuweba.com) - Unified solution for serverless security, monitoring and performance.

## CI/CD

* [seed.run](https://seed.run) - Seed manages pipelines, configures environments, and monitors deployments for Serverless Framework projects.
* [AWS Lambda Test Runner](https://github.com/automatictester/lambda-test-runner) - Run your unit tests with Maven or SBT directly on AWS Lambda.
* [LambCI](https://github.com/lambci/lambci) - A continuous integration system built on AWS Lambda
* [Serverless Framework Pro](https://www.serverless.com/pro/) - Serverless Framework Pro provides CI/CD, troubleshooting and monitoring for serverless applications
* [Stackery CICD](https://docs.stackery.io/docs/using-stackery/verification-pipeline/) - Stackery Verification and Deployment Pipelines

## Cost calculators

* [serverlesscalc](http://serverlesscalc.com) - Calculating cost for AWS Lambda, Azure Functions, Google Cloud Functions, and IBM Cloud Functions.
* [servers.lol](https://servers.lol) - calculator to decide Lambda vs EC2.

## Observability Tools (Logging / Monitoring / Performance / Tracing)

* [AWS IoT Button logger to git](https://github.com/kachkaev/aws-iot-button-logger-to-git/) - A simple and customisable AWS Lambda function that logs events from IoT devices into a git repository of your choice.
* [AWS Xray](https://aws.amazon.com/xray/) - Analyze and debug production, distributed applications.
* [Axiom](https://axiom.co/) - Serverless first logging with a generous free tier.
* [Dashbird](https://www.dashbird.io) - Performance Tracking and Error Alerting for serverless applications.
* [functionmetric](https://functionmetric.com) - Unlimited AWS Lambda monitoring via a self hosted CloudFormation template. All metrics and logs remain in your own AWS account.
* [New Relic](https://newrelic.com/products/serverless-aws-lambda) - Monitor, visualize, troubleshoot, and alert on all your AWS Lambda functions.
* [Thundra](https://www.thundra.io) - Thundra brings observability into your AWS Lambda functions by bringing metrics, logs, distributed tracing, and alerting together.
* [Epsagon](https://www.epsagon.com) - Epsagon automatically analyses your serverless application, identifies potential issues, and allows fast troubleshooting.
* [Lambda Live Debugger](https://www.srvrlss.io/blog/lambda-live-debugger/) - Real-time debugging tool for AWS Lambda functions, enabling live troubleshooting and observability without redeployment delays. Streamline your serverless development and catch issues as they happen.
* [Lumigo](https://www.lumigo.io) - Lumigo provides a visual debugging platform for serverless monitoring, tracing and troubleshooting (Free tier available).
* [serverless-es-logger](https://github.com/ccverak/serverless-es-logger) - serverless-es-logger is a package which allows you to send logs directly to Elasticsearch.
* [Serverless Framework Pro](https://www.serverless.com/pro/) - Serverless Framework Pro give you detailed invocation/request troubleshooting and monitoring tools for serverless applications
* [SLIC Watch](https://github.com/fourTheorem/slic-watch) - Automatic alarms and dashboards for Lambda, Kinesis and more AWS services.
* [sls-dev-tools](https://github.com/Theodo-UK/sls-dev-tools) - In terminal developer dashboard for AWS Serverless architectures. *(Does not replace your framework or logging/monitoring, it's used in addition)*
* [SenseDeep](https://www.sensedeep.com) - SenseDeep serverless developer studio helps to quickly diagnose, debug and deliver reliable serverless apps.

## Optimization and Management
* [Epsagon](https://www.epsagon.com) - Epsagon automatically analyses your serverless application, identifies potential issues, and allows fast troubleshooting.
* [Sedai] https://www.sedai.io) - Sedai autnonomously manages your serverless application, optimizing for performance and cost, remediating potential issues, and providing release intelligence on each new version.

## Authentication and authorization

* [Auth0](https://auth0.com) - Single Sign On & Token Based Authentication.
* [Amazon Cognito](https://aws.amazon.com/cognito/) - Amazon Cognito lets you easily add user sign-up and sign-in to your mobile and web apps.
* [DailyCred](https://www.dailycred.com/) - Registration, user management, single-sign-on.
* [Firebase](https://firebase.com/).
* [MojoAuth](https://mojoauth.com) - Passwordless authentication on your web, mobile or any application in minutes.
* [OAuth.io](https://oauth.io/) - OAuth integration, user management, provides OAuth 2.0 layer to existing APIs.
* [Okta](https://developer.okta.com/) - Provides authentication, authorization, and user management, merged with [Stormpath](https://stormpath.com/) in August 2017.
* [Serverless Authentication Boilerplate with FaunaDB](https://serverless.com/blog/faunadb-serverless-authentication/) - Single sign on using Amazon API Gateway custom authorizer to provision database access tokens for your Lambda functions. [See TodoMVC integration in this meetup talk video.](https://fauna.com/blog/developing-serverless-authentication-and-persistence)

## IAM

* [PureSec CLI](https://github.com/puresec/serverless-puresec-cli) - Magically creates least privileged IAM roles for you.

## Payments

* [Stripe Serverless webhook](https://github.com/eahefnawy/serverless-stripe-webhook) - Serverless Module that creates a webhook for Stripe.
* [Stripe Lambda function](https://github.com/TaylorBriggs/stripe-lambda) - A Lambda function for charging cards with Stripe.
* [GCF-Stripe](https://github.com/rldaulton/GCF-Stripe) - serverless use of Stripe over Google Cloud Functions.
* [Stripe Azure function](https://github.com/sdras/sample-stripe-handler) - An Azure Function that uses the Stripe api for a checkout process in a Vue application

## eCommerce

* [Snipcart](https://snipcart.com) - Fully customizable, HTML and JavaScript-based shopping cart for any website.
* [CommerceJS](http://commercejs.com/) - Full-stack ecommerce api for developers & designers.
* [EndlessCommerce](https://github.com/endless-commerce/endless) - Open source ecommerce platform based on Serverless framework.
* [Medusa](https://medusajs.com/) - Medusa is an open-source headless commerce engine that enables developers to create amazing digital commerce experiences.



## Content Management Systems

* [Contentful](https://www.contentful.com/) - A content infrastructure that enables teams to power content in any digital product via a RESTful API.
* [Cosmicjs](https://cosmicjs.com) - API-first CMS for building content-powered apps in any programming language.
* [GraphCMS](https://graphcms.com/) - GraphQL based, no opinion CMS for your digital products.
* [Sanity](https://sanity.io) - A hosted backend for structured content with a real-time API, globally distributed CDN, and a powerful, but simple query language.
* [Storyblok](https://www.storyblok.com/) - API based & Headless CMS - Clean and structured JSON for you as developer and a CMS your editors will fall in love with. Unlimited extensibility through custom plugins.
* [TakeShape](https://www.takeshape.io/) - Content-as-a-Service via a powerful GraphQL API and integrated SSG for teams that want to stay focused on their product.
* [Tipe](https://tipe.io/) - Next generation serverless CMS. Create your content with powerful editing tools and access it from anywhere with a GraphQL or REST API.
* [Webiny](https://www.webiny.com/) - Developer-friendly Serverless CMS powered by GraphQL and React.
* [Stiva](https://github.com/anddimario/stiva) - Stiva is a headless CMS for multisite and dynamic multicontent, based on lambda, dynamodb and s3.
* [Forestry](https://forestry.io/) - Git-backed CMS for Static Site Generators like Gatsby, Gridsome, Eleventy, Hugo, VuePress, Jekyll, etc.

## Forms

* [Airform.io](https://airform.io) - Functional HTML forms for Front-End Developers.
* [Form.io](https://form.io) - JSON Powered Form and Data Management Platform for Serverless applications.
* [Formcake](https://formcake.com) - Form backend built for developers with spam protection, Zapier integration, and API access.
* [Formcarry](https://formcarry.com) - Hassle-free HTML form endpoints for your form, powerful dashboard, reliable spam blocking, attachment uploads and Zapier integrations.
* [Formspark](https://formspark.io) - A backend for your HTML forms.
* [Formspree](https://formspree.io) - Functional HTML forms.
* [FormKeep](https://formkeep.com) - Form endpoints for designers and developers. No iframes, JavaScript embeds, or CSS overrides.
* [Formplug](https://github.com/danielireson/formplug-serverless) - Form forwarding service for AWS Lambda.
* [FormAssembly](http://www.formassembly.com/).
* [Getform](http://getform.io/) - Free form backend platform for your HTML forms and static websites. Provides Zapier and Webhook support and submissions API.
* [Google Forms](https://docs.google.com/forms/) - Create and analyze online forms and surveys.
* [Pageclip](https://pageclip.co/) - A Server for your HTML Forms - Collect info from users without a server—Pageclip is your server. Lead capture forms, surveys, newsletter forms, contact forms, etc. Setup any form in seconds.
* [SurveyVista](https://surveyvista.com) - Salesforce Survey, Form, and Assessment - Turn Survey & Form Data into Actionable Insights.
* [Typeform](https://www.typeform.com/) - Pretty, intuitive, slick forms for almost any use.
* [Tectite FormMail](http://www.tectite.com/) - FormMail, form Encryption, hosted Forms.
* [Wufoo](http://www.wufoo.com/).

## Media management and File storage

* [Filestack](https://www.filestack.com) - Image management system with Filestack - upload files, transform images, videos, and documents, store content and deliver fast via CDN.
* [Kloudless](https://kloudless.com) - Integrate with one, universal API and connect to many file storage and CRM services.
* [Letter Avatar](https://github.com/kevincolemaninc/letter-avatar-serverless) - Generates Google-like binary avatar images
* [Mux](https://mux.com) - Streaming video infrastructure for developers. Add a live stream or upload a video file, then get thumbnails, animated gifs and more via simple API calls.
* [Uploadcare](https://uploadcare.com) - HTML5 widget, API to manage files in cloud storage, smart and fast CDN to deliver them to your end users. Crop, resize and transform uploaded images using URL commands.

## Realtime

* [Ably](https://www.ably.io/) - Global distributed realtime data delivery platform with pub/sub, presence, device awareness, history, connection state recovery, authentication and encryption.
* [Pusher](https://pusher.com/) - Build Apps, Not Infrastructure.
* [Pubnub](https://www.pubnub.com/) - PubNub utilizes a Publish/Subscribe[2] model for realtime data streaming.

## Scheduling

* [Posthook](https://posthook.io/) - Run code only when you need to by scheduling webhooks for later. Set up workflows from your functions and run them on a repeating schedule.
* [qStash](https://upstash.com/qstash) - Push based messaging and scheduling over HTTP for serverless and edge runtimes with 50 requests per day for free.

## Email sending, subscriptions and newsletters

* [Lambda Mailer](https://github.com/eahefnawy/lambda-mailer) - AWS Lambda for sending emails.
* [Serverless Mailer](https://github.com/eahefnawy/serverless-mailer) - Serverless Module for sending emails.
* [Mailchimp Lambda](https://github.com/TaylorBriggs/mailchimp-lambda) - A Lambda function for subscribing to a MailChimp list.
* [Mailchimp Lambda Single Opt-in](https://github.com/anaibol/lambda-mailchimp-single-opt-in) - An Amazon Lambda function for creating MailChimp subscriptions with single opt-in.

## SMS sending

* [serverless-twilio](https://github.com/eahefnawy/serverless-twilio) - Serverless Module to send SMS via twilio.
* [Amazon SNS](https://aws.amazon.com/sns) - A flexible, fully managed pub/sub messaging and mobile notifications service (including SMS) for coordinating the delivery of messages to subscribing endpoints and clients.

## Push notifications

* ~~[Ionic Push Service](http://docs.ionic.io/services/push/)~~ - Notifications for Android, iOS with Ionic Cloud.
* [Pushover](https://pushover.net/) Notifications for Android, iOS, and Desktop.
* [ZeroPush](https://zeropush.com) Transactional Push Notifications for Developers.
* [PushWizard](https://pushwizard.com/) Multi-platform Push Notification Service.
* [Pushed](https://pushed.co/) Send push notifications without developing your own app.
* [Plot Projects](http://www.plotprojects.com/) Geofencing push notifications.
* [XtremePush](https://xtremepush.com/) Web Push Notifications.

## Databases

* [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) - Flexible NoSQL database service
* [Amazon Aurora Serverless](https://aws.amazon.com/rds/aurora/serverless/) - Serverless MySQL Database service
* [Algolia](https://www.algolia.com) - Hosted cloud search as a service.
* [FaunaDB](https://fauna.com/) - Pay-as-you-go cloud database with ACID transactions and on-premise licensing available.
* [Cloudant](https://cloudant.com/) - Based on the Apache-backed CouchDB, Cloudant is the distributed database as a service (DBaaS) built from the ground up to deliver fast-growing application data to the edge.
* [Cloudflare Workers KV](https://developers.cloudflare.com/workers/reference/storage) - Global, low-latency, key-value data store for Cloudflare Workers.
* [Azure CosmosDB](https://azure.microsoft.com/en-us/services/cosmos-db/) - Globally distributed, multi-model database service
* [Cube.js](https://cube.dev/) - Hosted analytics platform for serverless apps.
* [Google Cloud Datastore](https://cloud.google.com/datastore/) - Hosted NoSQL database service by Google
* [ParanoidGuy Databunker](https://github.com/paranoidguy/databunker) - Personally identifiable information (PII) storage service built to comply with GDPR and CCPA
* [Deta Base](https://deta.sh) - A super easy to use production-grade NoSQL database.that supports complex queries and search.
* [Upstash](https://upstash.com/) - Serverless Database for Redis
* [HarperDB](https://www.harperdb.io/) - Peer-to-peer database that is independent of hardware and network providers, accommodates both NoSQL and SQL workloads. 
* [Neon](https://neon.tech) - fully managed serverless PostgreSQL. Neon separates storage and compute to offer modern developer features such as serverless, branching, bottomless storage, and more.

## Others

* [Azure Function Library](http://functionlibrary.azurewebsites.net) - An open source set of common use cases for Azure Functions that are ready to deploy!
* [Argonaut](https://argonaut.dev/) - Deploy apps and infrastructure on your cloud in minutes. Support for custom and third-party app deployments on Kubernetes and Lambda environments. Free tier allows unlimited apps and deployments for 5 environments and 2 users.
* [Backstage Functions](https://github.com/backstage/functions) - An Open Source Serverless Platform able to store and execute code maintained by [Globo.com](http://www.globo.com)
* [remoteStorage](https://remotestorage.io) - An open protocol for per-user storage.
* [SCAR](https://github.com/grycap/scar) - Serverless Container-aware ARchitectures (e.g. run containers out of your Docker images in AWS Lambda).
* [Sockethub](http://sockethub.org) - A polyglot (speaking many different protocols and APIs) messaging service for social and other interactive messaging applications.
* [serverless-slack-webhook](https://github.com/eahefnawy/serverless-slack-webhook) - Serverless Module that creates a webhook for Slack.
* [Daggy](https://github.com/synacker/daggy) - Data Aggregation Utility. Remote or local data aggregation and streaming
* [Docker Lambda](https://github.com/lambci/docker-lambda) - Docker images and test runners that replicate the live AWS Lambda environment
* [faas](https://github.com/alexellis/faas) - Run Docker containers as functions on Swarm Mode ([blog post](http://blog.alexellis.io/functions-as-a-service/))
* [FunctionCI](https://github.com/rgfindl/functionci) - Continuous Integration for AWS Lambdas.
* [gofn](https://github.com/nuveo/gofn) - Go package for function process via container provider (serverless minimalist)
* [kube-fledged](https://github.com/senthilrch/kube-fledged) - A K8S add-on for creating and managing a cache of container images directly on cluster worker nodes
* [Lambda Comments](https://github.com/jimpick/lambda-comments) - Blog commenting system built with AWS Lambda
* [AWS Lambda Debugger](https://github.com/trek10inc/aws-lambda-debugger) - Remote debugging tool for Lambda functions running on Node 6.10
* [Local stack](https://localstack.cloud/) - A fully functional local AWS cloud stack
* [Project Flogo](https://github.com/TIBCOSoftware/flogo) - Project Flogo is an open source framework to simplify building efficient & modern serverless functions and edge microservices.
* [Serverless Examples](https://www.serverless.com/examples/) - A collection of boilerplates and examples of serverless architectures built with the Serverless Framework
* [serverless.tf playground](https://github.com/antonbabenko/serverless.tf-playground) - serverless.tf playground to show Terraform with Serverless in action.
* [Terraform AWS Lambda module](https://github.com/terraform-aws-modules/terraform-aws-lambda/) - Terraform module, which takes care of a lot of AWS Lambda/serverless tasks (build dependencies, packages, updates, deployments) in countless combinations.
* [Lambda Shim](https://github.com/ffleet/shim) - A node.js shim library to simplify Lambda function development
* [Mutton](https://github.com/hmngwy/mutton) - A Python shim library for better AWS Lambda Handlers
* [Serverless Permission Policy Generator](https://github.com/Open-SL/serverless-permission-generator) - An Online Application to generate AWS IAM permissions required for deploying a Serverless stack.
* [DynamoDB Onetable](https://www.npmjs.com/package/dynamodb-onetable) - DynamoDB access library for single-table designs using NodeJS.

## Related articles

* [Serverless Framework (CloudAcademy)](http://cloudacademy.com/blog/serverless-framework-aws-lambda-api-gateway-python) -  A Deep Overview of the Best AWS Lambda + API Gateway Automation Solution
* [AWS Lambda Microservices Architecture for Node.js](https://medium.com/getty-logs/a-aws-lambda-microservices-architecture-for-node-js-4513799101d4#.k99m6yvvz)
* [Designing Teams around Microservices](https://www.nginx.com/blog/adopting-microservices-at-netflix-lessons-for-team-and-process-design/)
* [The Serverless Start-Up - Down With Servers!](http://highscalability.com/blog/2015/12/7/the-serverless-start-up-down-with-servers.html)
* [Think Serverless!](https://medium.com/think-serverless) - Publications encompassing a deep insight into the future of serverless application development
* [Microservices without the Servers](https://aws.amazon.com/blogs/compute/microservices-without-the-servers)
* [A startup journey on AWS: from bare metal monolith to serverless microservices](https://medium.com/@benorama/a-startup-journey-on-aws-from-bare-metal-monolith-to-serverless-microservices-80231624fbd9)
* [nobackend.org](http://nobackend.org)
* [unhosted.org](https://unhosted.org/) - unhosted web apps. freedom from web 2.0's monopoly platforms
* [Static Web Applications](https://staticapps.org)
* [Serverlesscode](https://serverlesscode.com)
* [Serverless Architectures](http://martinfowler.com/articles/serverless.html)
* [Serverless Stack](http://serverless-stack.com/) - A step-by-step guide to creating full-stack serverless apps.
* [Migrating a Native JAVA REST API to a Serverless Architecture with the Lambada Framework for AWS](https://aws.amazon.com/blogs/compute/migrating-a-native-java-rest-api-to-a-serverless-architecture-with-the-lambada-framework-for-aws/)
* [Using Kotlin with AWS Lambda](https://medium.com/tech-travelstart/using-kotlin-in-a-serverless-architecture-with-aws-lambda-part-1-setting-up-the-project-87033790e2f4) - Using Kotlin in a serverless architecture with AWS Lambda.
* [Serverless Architectures Security Top 10](https://github.com/puresec/sas-top-10) - The Ten Most Critical Security Risks in Serverless Architectures.
* [Continuous Delivery Patterns with Serverless Applications](https://semaphoreci.com/blog/2018/08/22/continuous-delivery-patterns-with-serverless.html) - patterns for effective Continuous Delivery when building Serverless applications.
* [Level up your serverless game with a GraphQL data-as-a-service layer](https://hasura.io/blog/level-up-your-serverless-game-with-a-graphql-data-as-a-service-layer/)
* [Serverless White Paper](https://www.unusual.vc/post/unusual-tech-serverless-white-paper) - Informative White Paper on Serverless with deep analysis by Unusual VC.
* [Receiving Webhooks with Netlify Functions](https://www.svix.com/blog/receive-webhooks-with-netlify-functions/) - Using Netlify's serverless functions to receive webhooks and verify the signature.

## Books

* [Serverless](https://leanpub.com/serverless) - Patterns of Modern Application Design Using Microservices (Amazon Web Services Edition).
* [Serverless Single Page Apps](https://pragprog.com/book/brapps/serverless-single-page-apps) - The Pragmatic Bookshelf.
* [Going Serverless](https://www.goingserverless.co/) - Practical guide to building applications with the Serverless Framework.
* [Serverless Architectures on AWS](https://www.manning.com/books/serverless-architectures-on-aws). Teaches you how to build, secure and manage serverless architectures that can power the most demanding web and mobile apps. Written by Peter Sbarski
* [Building Serverless Architectures](https://www.amazon.co.uk/Building-Serverless-Architectures-Cagatay-Gurturk/dp/1787129195) Book about building serverless applications  in JAVA.
* [AWS Lambda in Action](https://www.manning.com/books/aws-lambda-in-action) An example-driven tutorial that teaches you how to build applications that use an event-driven approach on the back end.
* [The Pulumi Book](https://thepulumibook.com) - A book that shows you how to use Pulumi, an open-source infrastructure-as-code platform, to build serverless applications of all kinds using TypeScript and Amazon Web Services.
* [Serverless Applications with Node.js](https://www.manning.com/books/serverless-apps-with-node-and-claudiajs) A book that walks you through building serverless apps on AWS using Node.js and Claudia.js.
* [Agile Development for Serverless Platforms](https://www.manning.com/books/agile-development-for-serverless-platforms) free eBook: how to apply Agile practices in fully serverless architectures.
* [Cloud Native Applications](https://www.manning.com/books/cloud-native-applications) free eBook: an introduction into the world of cloud computing and insights into what is possible with cloud services.
* [Exploring Cloud Computing](https://www.manning.com/books/exploring-cloud-computing) free eBook: an introduction to the two most popular cloud providers, Amazon and Google, and insights to help you get started.
* [Developing Serverless Applications - A Practical Introduction with Apache OpenWhisk](http://www.oreilly.com/programming/free/developing-serverless-applications.csp) free ebook focused on doing serverless with OpenWhisk.
* [Docker in Action, Second Edition](https://www.manning.com/books/docker-in-action-second-edition) A book that teaches you the skills and knowledge you need to create, deploy, and manage applications hosted in Docker containers and it has been fully updated with new examples, best practices, and entirely new chapters.
* [Docker in Practice, Second Edition](https://www.manning.com/books/docker-in-practice-second-edition) A book that teaches rock-solid, tested Docker techniques, enabling microservices architecture, efficient network modeling, offline productivity, and establishing a container-driven continuous delivery process.
* [Azure Serverless Computing Cookbook](https://azure.microsoft.com/en-us/resources/azure-serverless-computing-cookbook) free eBook: Learn how to build scalable, serverless apps with these easy-to-follow recipes
* [AI as a Service](https://www.manning.com/books/ai-as-a-service) A book that teaches you how to harness the power of cloud-based AI services and serverless computing. An engineering approach to serverless AI.
* [Azure Data Engineering](https://www.manning.com/books/azure-data-engineering) - This book teaches you to build high-capacity data analytics systems using Azure cloud services for storing, collecting and analyzing data.
* [Google Cloud Platform in Action](https://www.manning.com/books/google-cloud-platform-in-action) - A book that teaches you to to deploy scalable cloud applications on Google Cloud Platform.
* [Cloud Native Patterns](https://www.manning.com/books/cloud-native-patterns) - A guide to developing cloud-native applications, along with the patterns, practices, and tooling that set them apart.
* [Cloud Native Spring in Action](https://www.manning.com/books/cloud-native-spring-in-action) - A hands-on guide to cloud native application development using Spring Boot, Spring Cloud, Docker, and Kubernetes.
* [Learn Azure in a Month of Lunches](https://www.manning.com/books/learn-azure-in-a-month-of-lunches) - A book that teaches you the foundational techniques for writing, deploying, and running cloud-based applications in Azure.
* [Learn Amazon Web Services in a Month of Lunches](https://www.manning.com/books/learn-amazon-web-services-in-a-month-of-lunches) - A book that guides you through the process of building a robust and secure web application using the core AWS services you really need to know.
* [Build a Serverless React Application](https://buttercms.com/blog/what-is-serverless-and-how-to-use-it-in-practice) - A full understanding of serverless architecture and how to use it in practice.
* [Learn Azure in a Month of Lunches, Second Edition](https://www.manning.com/books/learn-azure-in-a-month-of-lunches-second-edition) - In this fully updated and new edition, you’ll get hands-on practice with the basics, including setting up cloud-based virtual machines, deploying web servers, and using hosted data stores.
* [Learn Docker in a Month of Lunches](https://www.manning.com/books/learn-docker-in-a-month-of-lunches) - A tutorial to get essential skills to use Docker in Linux, Windows, and Mac environments.
* [Knative in Action](https://www.manning.com/books/knative-in-action) - A book on how to build more complex and capable serverless applications with Knative.
* [Getting Started with Kubernetes](https://www.manning.com/books/getting-started-with-kubernetes) - A hands-on guide to Kubernetes using Google Kubernetes Engine service.
* [Cloud Operations](https://www.manning.com/books/cloud-operations) - A book that provides a holistic approach to CloudOps.
* [Serverless Machine Learning in Action](https://www.manning.com/books/serverless-machine-learning-in-action) - A book on how to build serverless machine learning applications on public clouds like AWS, Azure, and GCP.
* [Spring Microservices in Action, Second Edition](https://www.manning.com/books/spring-microservices-in-action-second-edition) - A book on how to build microservice-based applications using Java and the Spring platform and how to efficiently monitor and log your microservices operations.
* [Spring Quickly](https://www.manning.com/books/spring-quickly) - A book that teaches you how to build professional-quality applications using Spring and Spring Boot.
* [Azure Data Engineering](https://www.manning.com/books/azure-data-engineering) - A book that teaches the architectural, operational, and data management techniques that power cloud-based data infrastructure built on the Microsoft Azure platform
* [AWS Security](https://www.manning.com/books/aws-security) - A guide to solving common AWS security issues.
* [Kubernetes Native Microservices with Quarkus, and MicroProfile](https://www.manning.com/books/kubernetes-native-microservices-with-quarkus-and-microprofile) - An introduction to a modern approach to enterprise Java development using new tools designed for cloud-native applications.
* [Pipeline as Code](https://www.manning.com/books/pipeline-as-code) - A hands-on experience on how to build CI/CD pipelines with Jenkins for cloud-native applications (including Serverless apps).
* [Serverless Security](https://ServerlessSecurityBook.com) - An Apress book that discusses serverless security on AWS, Azure and Google Cloud.
* [Mastering AWS Serverless](https://MasteringAWSServerlessBook.com) - Learn Serverless Step by Step.
Build an event-driven architecture and application in the AWS cloud.
* [Azure Infrastructure as Code](https://www.manning.com/books/azure-infrastructure-as-code) - Master ARM templates, Bicep scripting, and other Azure Infrastructure-as-Code tools, techniques, and practices to run application infrastructure on the Azure cloud.
* [Securing Kubernetes Secrets](https://www.manning.com/books/securing-kubernetes-secrets) - Securing Kubernetes Secrets is a compact hands-on guide to storing and protecting sensitive data in a Kubernetes environment.
* [Kubernets on Windows](https://www.manning.com/books/kubernetes-on-windows) - Guide to successfully running windows and .NET applications on a Kubernetes cluster.
* [Serverless Architectures on AWS, Second Edition](https://www.manning.com/books/serverless-architectures-on-aws-second-edition) - Book that teaches you how to design, secure and manage serverless backends that can power the most demanding web and mobile apps.
* [Designing Cloud Data Platforms](https://www.manning.com/books/designing-cloud-data-platforms) - A hands-on guide to envisioning and designing a modern scalable data platform that takes full advantage of the flexibility of the cloud.
* [Terraform in Action](https://www.manning.com/books/terraform-in-action) - Use Terraform to programmatically create, test, and manage infrastructure using the efficient infrastructure-as-code approach.
* [Securing Cloud Applications](https://www.manning.com/books/securing-cloud-applications) - This book demonstrates effective real-world practices to keep your cloud and Kubernetes-deployed applications safe and sound.
* [Google Anthos in Action](https://www.manning.com/books/google-anthos-in-action) - A book about Google Anthos created by the Google development team.
* [Kubernetes in Action, Second Edition](https://www.manning.com/books/kubernetes-in-action-second-edition) - A fully-updated and comprehensive guide to developing and running applications in a Kubernetes environment.
* [Cloud Observability in Action](https://www.manning.com/books/cloud-observability-in-action) - A book that teaches you how to set up an observability system that learns from a cloud application’s signals, logging, and monitoring using free and open source tools.
* [Podman in Action](https://www.manning.com/books/podman-in-action) - A book about developing and managing rootless containers using Podman.
* [Terraform in Depth](https://www.manning.com/books/terraform-in-depth) - A book about developing and managing rootless containers using Podman.

## Courses

* [Serverless JavaScript by Example](https://www.packtpub.com/web-development/serverless-javascript-example-video) - Become dexterous with live demonstrations on serverless web development.
* [AWS Lambda in Motion](https://www.manning.com/livevideo/aws-lambda-in-motion) - An example-driven tutorial that focuses on helping you understand and tackle the operational challenges with running AWS Lambda in production.
* [Serverless Applications with AWS](https://www.manning.com/livevideo/serverless-applications-with-AWS) - Serverless Applications with AWS teaches you to build serverless applications using AWS Lambda and other cloud-based services.
* [Serverless-stack](https://serverless-stack.com) - Learn to Build complete Full-Stack Apps with Serverless and React on AWS.
* [Develop a Serverless Backend using Node.js on AWS Lambda](https://egghead.io/courses/develop-a-serverless-backend-using-node-js-on-aws-lambda) - Learn how to create a serverless API and connecting it to DynamoDB using leveraging Lambda's new async/await syntax
* [AWS in Motion](https://www.manning.com/livevideo/aws-in-motion) - A liveVideo course that guides you through your first steps of deploying a web application on AWS, teaching you the basics of the AWS ecosystem.
* [Production-Ready Serverless](https://www.manning.com/livevideo/production-ready-serverless) - This liveVideo teaches you how to build applications that take advantage of AWS Lambda and other AWS platform features like API Gateway and Kinesis.

## Workshops

* [Apache OpenWhisk Workshop](https://www.npmjs.com/package/openwhisk-workshop) - Interactive workshop to learn about building serverless applications with OpenWhisk.

## Newsletters

* [Serverless Status](https://serverless.email/) - A weekly digest of the latest serverless news and articles.
* [Serverless Insights](https://symphonia.us15.list-manage.com/subscribe?u=8fe3a0d260ada7ca9aafdbf14&id=d4b4244107) - Symphonia's Serverless Insights.
* [Off-by-none](https://www.jeremydaly.com/newsletter/) - Weekly newsletter that focuses on using serverless technology to build products in the cloud
* [Serverless Transformation](https://www.getrevue.co/profile/serverless-transformation) - Weekly newsletter of a limited set of articles about serverless. Each article is graded on complexity level.
* [Shipped](https://faun.dev) - A weekly newsletter from FAUN: Hand-curated tutorials, news and stories from the Serverless space.

## AWS re:Invent videos

* [↑↑↓↓←→←→ BA Lambda Start](https://www.youtube.com/watch?v=iz90fHia-Wk&index=4&list=PLhr1KZpdzukcLUKD2ej8AKYR-nryjGGnF)
* [Application Lifecycle Management in a Serverless World](https://www.youtube.com/watch?v=8Zd-8GV-1mY&index=11&list=PLhr1KZpdzukcLUKD2ej8AKYR-nryjGGnF)
* [bots + serverless = ❤](https://www.youtube.com/watch?v=rvi2Jm4eQdM&index=5&list=PLhr1KZpdzukcLUKD2ej8AKYR-nryjGGnF)
* [Coca-Cola: Running Serverless Applications with Enterprise Requirements](https://www.youtube.com/watch?v=yErmil00DYs&index=10&list=PLhr1KZpdzukcLUKD2ej8AKYR-nryjGGnF)
* [Content and Data Platforms at Vevo: Rebuilding and Scaling from Zero](https://www.youtube.com/watch?v=EI7pwRMc6zM&index=12&list=PLhr1KZpdzukcLUKD2ej8AKYR-nryjGGnF)
* [Operating Your Production API](https://www.youtube.com/watch?v=tNIl_Wb12sE&index=8&list=PLhr1KZpdzukcLUKD2ej8AKYR-nryjGGnF)
* [Optimizing the Data Tier in Serverless Web Applications](https://www.youtube.com/watch?v=n5Jf6Vi2whI&index=9&list=PLhr1KZpdzukcLUKD2ej8AKYR-nryjGGnF)
* [Real-time Data Processing Using AWS Lambda](https://www.youtube.com/watch?v=VFLKOy4GKXQ)
* [Serverless Apps with AWS Step Functions](https://www.youtube.com/watch?v=75MRve4nv8s&index=7&list=PLhr1KZpdzukcLUKD2ej8AKYR-nryjGGnF)
* [Serverless Computing Patterns at Expedia](https://www.youtube.com/watch?v=gT9x9LnU_rE&index=3&list=PLhr1KZpdzukcLUKD2ej8AKYR-nryjGGnF)
* [Using AWS Lambda to Build Control Systems for Your AWS Infrastructure](https://www.youtube.com/watch?v=vkWGZ3uY0p0&index=2&list=PLhr1KZpdzukcLUKD2ej8AKYR-nryjGGnF)
* [What’s New with AWS Lambda](https://www.youtube.com/watch?v=CwxWhyGteNc)

## Videos from conferences

* [Serverlessconf](https://www.youtube.com/channel/UCqlcVgk8SkUmve4Kw4xSlgw)
* [ServerlessDays](https://www.youtube.com/channel/UCYzAnR_SebAmLRkKIbK_YoQ)
* [GOTO Conferences](https://www.youtube.com/playlist?list=PLEx5khR4g7PJNproQQ4SZ96Qeu-kr-Xbn)

## Contributing

You want to contribute to this project? [Please follow these recommendations](CONTRIBUTING.md).

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
