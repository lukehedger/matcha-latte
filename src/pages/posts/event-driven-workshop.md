---
title: "Workshop: Event-Driven Architecture"
description: "Learn about applying event-driven architecture to serverless applications on AWS through a hands-on workshop"
publishDate: "Monday, 6 December 2021"
author: "Luke Hedger"
heroImage: "/assets/blog/event-driven-workshop.jpg"
alt: "LEGO car by Eric & Niklas on Unsplash"
layout: "../../layouts/BlogPost.astro"
---

### Event-Driven Architecture

Before we dive into the workshop, let's clarify what we mean by event-driven architecture:

> Event-Driven Architecture is a software architecture paradigm promoting the production, detection, consumption of, and reaction to events.

Events move through event-driven applications in two ways:

- Choreography - Events **between** microservices
- Orchestration - Events **inside** microservices

Let's look at some of the advantages we gain from applying an event-driven architecture to our applications:

- **Asynchronous requests** allow resources to move freely to the next task once their unit of work is complete, without worrying about what happened before or will happen next
- **Loosely coupled** event-driven services operate independently, without knowledge of other services, including their implementation details and transport protocol
- **Simple scaling** of individual services thanks to decoupling
- **Recovery support** through “event replay”

### Workshop

Applying an event-driven architecture to serverless applications is a very powerful and natural design pattern.

But it can be a pretty abstract concept to grasp, particularly if you are new to serverless or AWS and trying to learn everything at once.

The **Event-Driven Architecture workshop** is a hands-on approach to form a mental model of how events flow through a serverless application and why this is a useful paradigm. We will cover:

- Amazon API Gateway
- Amazon EventBridge
- AWS Step Functions
- AWS Cloud Development Kit (CDK)

The workshop can be found at https://luke-hedger.gitbook.io/event-driven-architecture-workshop/

For a nice bonus we will prefer to use direct service integrations over Lambda functions.

And it is Christmas themed! 🎄

### Resources

- [Workshop](https://luke-hedger.gitbook.io/event-driven-architecture-workshop/)
- [Example workshop implementation](https://github.com/lukehedger/event-driven-workshop-example/)
