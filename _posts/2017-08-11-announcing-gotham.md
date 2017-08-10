---
layout: post
title: Announcing Gotham
date: 2017-08-09 18:00:00 +1000
published: true

author:
  name: Bradley Beddoes
  twitter: bradleybeddoes
  github: bradleybeddoes
  avatar: bradleybeddoes
---

For the last eight months, we've been hard at work on a project that we're 
thrilled to be able to share with the wider Rust community. 

We know it as [Gotham](https://gotham.rs) and today we're releasing 0.1.

Gotham is a flexible web framework that does not sacrifice 
safety, security or speed. The Gotham core team loves many of the elegant 
concepts that are found in dynamically typed web application frameworks, 
such as Rails/Phoenix/Django and aspire to achieve them with the 
type and memory safety guarantees provided by Rust.

Gotham is stability focused. With our release of Gotham 0.1, we're 
compatible with Rust stable and every future release of Gotham will 
maintain that contract. Naturally, we build on beta and nightly as well so 
if you're on the bleeding edge Gotham is good to go.

Gotham leverages async extensively thanks to the [Tokio](https://tokio.rs) project and is 
further enhanced by being built directly on top of async
[Hyper](https://hyper.rs). 
Completing web requests in **µs** with almost non-existent memory footprints 
is still taking some getting used to.

We wanted to get Gotham in the hands of the Rust community early with 
regular smaller iterations to follow. The Gotham 0.1 release includes the 
following features:

* Handlers and Controllers
* Advanced Routing
* Type Safe Extractors
* Middleware and Pipelines
* Request State
* Sessions
* Request and Response helpers
* Test helpers
* Thoroughly documented code and the beginnings of a Gotham book

There are some important features still to be built and we hope that the 
community will help us define even more. Right now our roadmap includes:

* Enhancing our Router API with builders/macros to make this much more comfortable for folks used to defining routes in Rails or Phoenix
* Compiled Templates
* Form extraction
* First class Diesel integration
* Async static file serving
* i18n
* Hot reload during development
* Structured logging

You can find out more about Gotham at [https://gotham.rs](https://gotham.rs). We look forward to 
welcoming you into the Gotham community.

Finally, we'd like to say a very sincere thank you to the developers and 
communities of every dependency we've built Gotham on top of, 
including of course, Rust itself. Your work is amazing and we could not have 
gotten here without it. We look forward to working with you all in the future.

Bradley and Shaun

